```markdown
# Understanding the Basics of Kubernetes

Kubernetes, often abbreviated as K8s, is an open-source container orchestration platform that automates many of the processes involved in deploying, scaling, and managing containerized applications. It groups containers that make up an application into logical units for easy management and discovery.

## Key Concepts

*   **Pods:** The smallest deployable units in Kubernetes. A pod is a group of one or more containers, sharing storage and network, and a specification for how to run the containers.

*   **Deployments:** Deployments declare a desired state for your application. They manage the deployment of pods, ensuring that the desired number of replicas are running. Deployments are declarative, meaning you specify what you want, and Kubernetes figures out how to achieve it.

*   **Services:** Services expose your application to the network. They provide a single IP address and DNS name for a set of pods. Services allow you to access your application without needing to know the individual IP addresses of the pods.

*   **Namespaces:** Namespaces allow you to logically partition your Kubernetes cluster into multiple virtual clusters. This is useful for organizing resources across different teams or environments.

## Common `kubectl` Commands

Here are some common `kubectl` commands you'll use to interact with your Kubernetes cluster:

*   `kubectl get pods`: Lists all the pods in the current namespace.
*   `kubectl describe pod <pod-name>`: Provides detailed information about a specific pod.
*   `kubectl create deployment <deployment-name> --image=<image-name>`: Creates a new deployment.
*   `kubectl expose deployment <deployment-name> --port=<port-number> --type=LoadBalancer`: Exposes a deployment as a service.
*   `kubectl apply -f <yaml-file>`: Applies a configuration defined in a YAML file.

## Example Deployment YAML

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

This example defines a deployment named `my-app-deployment` with 3 replicas. It uses the `nginx:latest` image and exposes port 80.

## Further Learning

*   [Kubernetes Documentation](https://kubernetes.io/docs/): The official Kubernetes documentation.
*   [Kubernetes Tutorials](https://kubernetes.io/docs/tutorials/): Hands-on tutorials to get you started.
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._