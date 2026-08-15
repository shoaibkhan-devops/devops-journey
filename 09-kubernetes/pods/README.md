# 🧱 Kubernetes Pods

A Pod is the smallest deployable unit in Kubernetes and usually contains one primary application container.

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: demo
spec:
  containers:
    - name: nginx
      image: nginx:latest
```

In production, Pods are typically managed by higher-level controllers such as Deployments rather than created directly.
