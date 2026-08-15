# 🪪 Managed Identity

Managed identities allow Azure resources to authenticate to supported services without application-managed passwords or client secrets.

## Pattern

```text
Azure VM / App / Automation
          ↓
   Managed Identity
          ↓
       RBAC
          ↓
 Azure Resource / Key Vault
```

## Benefits

- No hard-coded credentials
- Centralized access control
- Reduced secret rotation burden
- Better workload identity hygiene
