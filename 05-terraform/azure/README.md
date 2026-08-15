# ☁️ Terraform with Azure

The AzureRM provider allows Terraform to define Azure resources declaratively.

## Typical project layout

```text
azure-project/
├── main.tf
├── variables.tf
├── outputs.tf
├── versions.tf
├── terraform.tfvars.example
└── README.md
```

## Common resources

- Resource Group
- Storage Account
- VNet / Subnet
- NSG
- Virtual Machine
- Key Vault
- RBAC assignments

## Practice principle

Start with one resource, then introduce dependencies, variables, modules, state management and CI/CD.
