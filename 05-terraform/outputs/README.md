# 📤 Terraform Outputs

Outputs expose useful values from a Terraform deployment.

```hcl
output "resource_group_name" {
  value = azurerm_resource_group.demo.name
}
```

## Use cases

- Display deployment information
- Feed module outputs to parent modules
- Provide values to automation workflows
- Surface IDs, names and endpoints

> Sensitive outputs should be marked `sensitive = true` when appropriate.
