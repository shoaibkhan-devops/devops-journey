# 💾 Azure Storage

Azure Storage provides durable cloud storage for data, state, logs and application content.

## Main services

| Service | Typical use |
|---|---|
| Blob | Object data, backups, artifacts |
| Files | Managed file shares |
| Queue | Asynchronous messaging |
| Table | Key-value / NoSQL style data |

## Blob access tiers

```text
Hot → frequent access
Cool → less frequent access
Archive → long-term retention
```

## DevOps use cases

- Terraform remote state
- Build artifacts
- Backup repositories
- Log retention
- Static content

## Security

Prefer Azure AD / Entra-based access, RBAC and managed identity over sharing long-lived access keys wherever practical.
