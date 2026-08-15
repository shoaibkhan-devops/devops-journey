# 🌍 Azure Application Gateway

Application Gateway is a Layer 7 web traffic load balancer with routing and security features.

## Key capabilities

- HTTP/HTTPS routing
- Host-based routing
- Path-based routing
- TLS termination
- Health probes
- Web Application Firewall (WAF) capability

## Example

```text
Internet
   ↓
Application Gateway
   ├── /app   → App backend
   ├── /api   → API backend
   └── /admin → Admin backend
```

## DevOps connection

Application Gateway configuration can be managed through Terraform and validated as part of CI/CD.
