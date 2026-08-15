# 📁 Azure Resource Groups

A resource group is a management boundary for related Azure resources. It is useful for lifecycle management, access control, tagging and organization.

## Example

```text
rg-devops-demo
│
├── Virtual Network
├── Network Security Group
├── Virtual Machine
└── Storage Account
```

## CLI

```bash
az group create \
  --name rg-devops-demo \
  --location centralindia

az group list -o table
```

## Good practices

- Use a consistent naming standard
- Apply tags such as `Environment`, `Owner`, `CostCenter`
- Keep lifecycle-related resources together
- Avoid using resource groups as a substitute for proper Azure governance
