```markdown
# Understanding Kubernetes Pods

Kubernetes Pods are the smallest deployable units of computing that you can create and manage in Kubernetes.  A Pod represents a single instance of a running process in your cluster.

## What is a Pod?

A Pod can contain one or more containers, such as Docker containers.  These containers share the same network namespace, IPC namespace, and PID namespace.  This means they can communicate with each other via `localhost` and can signal each other (e.g., using signals like `SIGTERM`).

*   **Single Container Pods:** The most common case is a Pod with a single container. This is analogous to running a single process.
*   **Multi-Container Pods:**  Pods can also contain multiple containers that need to work together.  A typical example is a web application along with a helper container that retrieves logs and publishes them to a monitoring service.

## Pod Configuration

You define a Pod using a YAML or JSON file. Here's an example:

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: my-pod
spec:
  containers:
  - name: my-container
    image: nginx:latest
    ports:
    - containerPort: 80
```

This configuration defines a Pod named `my-pod` that contains a single container named `my-container`. The container runs the `nginx:latest` image and exposes port 80.

## Pod Lifecycle

Pods have a defined lifecycle, from creation to termination.  Key stages include:

*   **Pending:** The Pod has been accepted by the system, but one or more of the containers has not been created.
*   **Running:**  All containers in the Pod have been created and at least one container is running.
*   **Succeeded:** All containers in the Pod have terminated successfully.
*   **Failed:** All containers in the Pod have terminated, and at least one container has terminated in failure.
*   **Unknown:** The state of the Pod could not be determined for some reason.

## Interacting with Pods

You can interact with Pods using the `kubectl` command-line tool.  For example, to list all Pods in a namespace:

```bash
kubectl get pods -n my-namespace
```

To view the logs of a specific Pod:

```bash
kubectl logs my-pod
```

## Considerations

*   Pods are ephemeral. They are not designed to be persistent. If a Pod fails, it will be recreated (typically by a ReplicaSet or Deployment).
*   Use controllers like ReplicaSets or Deployments to manage Pods and ensure high availability.
*   Understand the relationship between Pods, Services, and Deployments for effective Kubernetes application management.  Refer to the [Kubernetes documentation](https://kubernetes.io/docs/concepts/workloads/pods/) for more information.
```

```ko
# Kubernetes Pod 이해하기

Kubernetes Pod는 Kubernetes에서 생성하고 관리할 수 있는 가장 작은 배포 단위입니다. Pod는 클러스터에서 실행 중인 프로세스의 단일 인스턴스를 나타냅니다.

## Pod란 무엇입니까?

Pod는 Docker 컨테이너와 같은 하나 이상의 컨테이너를 포함할 수 있습니다. 이러한 컨테이너는 동일한 네트워크 네임스페이스, IPC 네임스페이스 및 PID 네임스페이스를 공유합니다. 즉, `localhost`를 통해 서로 통신할 수 있으며 서로에게 신호를 보낼 수 있습니다 (예 : `SIGTERM`과 같은 신호 사용).

*   **단일 컨테이너 Pod:** 가장 일반적인 경우는 단일 컨테이너가 있는 Pod입니다. 이는 단일 프로세스를 실행하는 것과 유사합니다.
*   **다중 컨테이너 Pod:** Pod는 함께 작동해야 하는 여러 컨테이너를 포함할 수도 있습니다. 일반적인 예는 웹 애플리케이션과 로그를 검색하여 모니터링 서비스에 게시하는 도우미 컨테이너입니다.

## Pod 구성

YAML 또는 JSON 파일을 사용하여 Pod를 정의합니다. 다음은 예입니다.

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: my-pod
spec:
  containers:
  - name: my-container
    image: nginx:latest
    ports:
    - containerPort: 80
```

이 구성은 `my-container`라는 단일 컨테이너를 포함하는 `my-pod`라는 Pod를 정의합니다. 컨테이너는 `nginx:latest` 이미지를 실행하고 포트 80을 노출합니다.

## Pod 라이프사이클

Pod는 생성부터 종료까지 정의된 라이프사이클을 갖습니다. 주요 단계는 다음과 같습니다.

*   **Pending:** Pod가 시스템에 의해 수락되었지만 하나 이상의 컨테이너가 생성되지 않았습니다.
*   **Running:** Pod의 모든 컨테이너가 생성되었으며 하나 이상의 컨테이너가 실행 중입니다.
*   **Succeeded:** Pod의 모든 컨테이너가 성공적으로 종료되었습니다.
*   **Failed:** Pod의 모든 컨테이너가 종료되었으며 하나 이상의 컨테이너가 실패했습니다.
*   **Unknown:** 어떤 이유로 Pod의 상태를 확인할 수 없습니다.

## Pod와 상호 작용하기

`kubectl` 명령줄 도구를 사용하여 Pod와 상호 작용할 수 있습니다. 예를 들어 네임스페이스의 모든 Pod를 나열하려면 다음을 수행하십시오.

```bash
kubectl get pods -n my-namespace
```

특정 Pod의 로그를 보려면 다음을 수행하십시오.

```bash
kubectl logs my-pod
```

## 고려 사항

*   Pod는 일시적입니다. 지속되도록 설계되지 않았습니다. Pod가 실패하면 다시 생성됩니다 (일반적으로 ReplicaSet 또는 Deployment에 의해).
*   ReplicaSet 또는 Deployment와 같은 컨트롤러를 사용하여 Pod를 관리하고 고가용성을 보장하십시오.
*   효과적인 Kubernetes 애플리케이션 관리를 위해 Pod, Service 및 Deployment 간의 관계를 이해하십시오. 자세한 내용은 [Kubernetes 문서](https://kubernetes.io/docs/concepts/workloads/pods/)를 참조하십시오.
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._