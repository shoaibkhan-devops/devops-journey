# 🗄️ Terraform Backend

A Terraform backend determines where state is stored. For team environments, remote state is preferred over keeping state only on a developer laptop.

## Azure backend concept

```text
Terraform CLI
     ↓
Azure Storage Account
     ↓
Blob container
     ↓
terraform.tfstate
```

## Why remote state?

- Shared access
- Better collaboration
- Centralized state
- State locking support through the backend
- Better operational recovery

Never commit `terraform.tfstate` to a public repository.
