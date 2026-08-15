# 🔑 Azure Key Vault

Key Vault provides centralized storage and controlled access for secrets, keys and certificates.

## Good pattern

```text
Application / Pipeline
        ↓
Managed Identity / Workload Identity
        ↓
RBAC
        ↓
Key Vault
        ↓
Secret / Key / Certificate
```

## Rules

❌ Do not commit secrets to Git

❌ Do not place production passwords in `.tfvars`

✅ Use identity-based access

✅ Rotate secrets and audit access
