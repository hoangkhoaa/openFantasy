```markdown
# Understanding Kubernetes Networking

Kubernetes networking can be complex, but understanding its core principles is crucial for deploying and managing applications effectively. This document provides an overview of key concepts.

## Pod Networking

*   **Each Pod gets its own IP address:** This is fundamental. Pods in a Kubernetes cluster communicate with each other using their assigned IP addresses, not through Network Address Translation (NAT).

*   **Pods share a network namespace:** Containers within a Pod share the same network namespace, meaning they can communicate with each other via `localhost`.

*   **Services act as a stable endpoint:** Services provide a consistent IP address and port for accessing Pods, even as Pods are created and destroyed.

## Service Types

Kubernetes offers different types of Services to expose your applications:

*   **ClusterIP:** Exposes the Service on a cluster-internal IP. Only reachable from within the cluster. This is the default Service type.

*   **NodePort:** Exposes the Service on each Node's IP at a static port (the NodePort).  This makes the Service accessible from outside the cluster, using the Node's IP address and the assigned NodePort.

*   **LoadBalancer:** Exposes the Service externally using a cloud provider's load balancer. The cloud provider creates a load balancer that routes traffic to the Service.  Requires a cloud provider integration (e.g., AWS, GCP, Azure).

*   **ExternalName:** Maps the Service to the contents of the `externalName` field (e.g., to an external database).

## Networking Plugins (CNI)

The Container Network Interface (CNI) is a standard interface that allows Kubernetes to work with various networking providers.  Popular CNI plugins include:

*   **Calico:** Provides network policy enforcement and advanced networking features.

*   **Flannel:** A simple and widely used overlay network solution.

*   **Weave Net:** Another popular overlay network solution that simplifies networking in Kubernetes.

## Network Policies

Network Policies allow you to control traffic flow between Pods.  They provide a way to isolate applications and enforce security rules at the network layer.

Example Network Policy:

```yaml
apiVersion: networking.k8s.io/v1
kind: NetworkPolicy
metadata:
  name: my-network-policy
spec:
  podSelector:
    matchLabels:
      app: my-app
  policyTypes:
  - Ingress
  ingress:
  - from:
    - podSelector:
        matchLabels:
          app: allowed-app
```

This Network Policy allows traffic only from Pods with the label `app: allowed-app` to Pods with the label `app: my-app`.
```


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._