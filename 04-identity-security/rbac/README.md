# 🛡️ Azure RBAC

Role-Based Access Control defines who can perform what actions on which Azure resources.

## Scope hierarchy

```text
Management Group
      ↓
Subscription
      ↓
Resource Group
      ↓
Resource
```

## Common roles

- Owner
- Contributor
- Reader
- Service-specific roles

## Least privilege

Grant the smallest role at the narrowest practical scope. Review assignments regularly and prefer managed identities for workload access.
