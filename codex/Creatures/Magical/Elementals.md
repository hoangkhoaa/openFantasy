```markdown
# Understanding the Basics of Kubernetes

Kubernetes, often shortened to K8s, is an open-source container orchestration platform that automates many of the manual processes involved in deploying, managing, and scaling containerized applications.

## Key Concepts

*   **Pods:** The smallest deployable units of computing that you can create and manage in Kubernetes. A Pod is a group of one or more containers, with shared storage/network, and a specification for how to run the containers.
*   **Services:** An abstraction which defines a logical set of Pods and a policy by which to access them. Services enable loose coupling between dependent Pods.
*   **Deployments:** A Deployment provides declarative updates for Pods and ReplicaSets. You describe a desired state in a Deployment, and the Deployment Controller changes the actual state to the desired state at a controlled rate.
*   **Namespaces:** Provide a mechanism to isolate groups of resources within a single cluster.

## Common kubectl Commands

*   `kubectl get pods`: Lists all pods in the current namespace.
*   `kubectl describe pod <pod-name>`: Displays detailed information about a specific pod.
*   `kubectl apply -f <filename.yaml>`: Applies a configuration change to the cluster based on the YAML file.
*   `kubectl logs <pod-name>`: Fetches logs from a pod.

## Example YAML Configuration (Deployment)

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: my-app-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
      - name: my-app-container
        image: nginx:latest
        ports:
        - containerPort: 80
```

## Further Learning

*   [Kubernetes Documentation](https://kubernetes.io/docs/home/)
*   [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)
```
```vi
# Tìm hiểu những điều cơ bản về Kubernetes

Kubernetes, thường được viết tắt là K8s, là một nền tảng điều phối container mã nguồn mở tự động hóa nhiều quy trình thủ công liên quan đến việc triển khai, quản lý và mở rộng các ứng dụng container hóa.

## Các khái niệm chính

*   **Pods:** Các đơn vị tính toán triển khai nhỏ nhất mà bạn có thể tạo và quản lý trong Kubernetes. Pod là một nhóm gồm một hoặc nhiều container, với bộ nhớ/mạng dùng chung và một đặc tả về cách chạy các container.
*   **Services:** Một trừu tượng định nghĩa một tập hợp logic các Pod và một chính sách để truy cập chúng. Services cho phép sự kết hợp lỏng lẻo giữa các Pod phụ thuộc.
*   **Deployments:** Một Deployment cung cấp các bản cập nhật khai báo cho Pods và ReplicaSets. Bạn mô tả một trạng thái mong muốn trong một Deployment, và Deployment Controller thay đổi trạng thái thực tế thành trạng thái mong muốn với tốc độ được kiểm soát.
*   **Namespaces:** Cung cấp một cơ chế để cô lập các nhóm tài nguyên trong một cụm duy nhất.

## Các lệnh kubectl phổ biến

*   `kubectl get pods`: Liệt kê tất cả các pod trong namespace hiện tại.
*   `kubectl describe pod <pod-name>`: Hiển thị thông tin chi tiết về một pod cụ thể.
*   `kubectl apply -f <filename.yaml>`: Áp dụng một thay đổi cấu hình cho cluster dựa trên file YAML.
*   `kubectl logs <pod-name>`: Lấy nhật ký từ một pod.

## Ví dụ cấu hình YAML (Deployment)

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: my-app-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
      - name: my-app-container
        image: nginx:latest
        ports:
        - containerPort: 80
```

## Học thêm

*   [Kubernetes Documentation](https://kubernetes.io/docs/home/)
*   [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/)
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._