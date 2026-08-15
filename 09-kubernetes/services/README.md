# 🌐 Kubernetes Services

Services provide stable networking to reach Pods even though Pod IPs can change.

## Types

- ClusterIP
- NodePort
- LoadBalancer

```text
Client → Service → Selector → Pods
```

This abstraction is central to service discovery and resilient application networking.
