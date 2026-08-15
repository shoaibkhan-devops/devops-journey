# 🚀 Kubernetes Deployments

Deployments manage replicated application Pods and support rolling updates.

```text
Deployment
    ↓
ReplicaSet
    ↓
Pods
```

## Key ideas

- Desired replica count
- Rolling updates
- Rollbacks
- Labels and selectors
- Health probes

Example command:

```bash
kubectl get deployments
kubectl rollout status deployment/demo
kubectl rollout history deployment/demo
```
