# ⚖️ Azure Load Balancer

Azure Load Balancer provides Layer 4 traffic distribution for highly available workloads.

## Typical flow

```text
Client
  ↓
Public / Internal Load Balancer
  ↓
Backend Pool
  ├── VM 1
  ├── VM 2
  └── VM 3
```

## Concepts

- Frontend IP
- Backend pool
- Health probe
- Load-balancing rule
- Inbound NAT rule
- Public vs internal load balancer

## Compare with Application Gateway

Load Balancer is primarily Layer 4. Application Gateway provides Layer 7 routing features such as host/path-based routing and web application firewall capabilities.
