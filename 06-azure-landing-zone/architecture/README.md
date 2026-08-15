# 🧭 Landing Zone Architecture

A mature Azure foundation separates **platform concerns** from **workload concerns**.

```text
Azure Tenant
│
├── Platform / Management Groups
│     ├── Identity
│     ├── Connectivity
│     ├── Management
│     └── Security
│
└── Workload Subscriptions
      ├── Production
      ├── Non-Production
      └── Sandbox
```

## Design questions

- Where should workloads live?
- Who owns networking?
- How is access granted?
- How are policies inherited?
- How are logs centralized?
- How is cost allocated?
