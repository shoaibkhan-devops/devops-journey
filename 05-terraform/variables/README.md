# 🔧 Terraform Variables

Variables keep configuration reusable and prevent environment-specific values from being hard-coded.

```hcl
variable "location" {
  type        = string
  description = "Azure region"
  default     = "Central India"
}
```

## Common types

- `string`
- `number`
- `bool`
- `list(...)`
- `set(...)`
- `map(...)`
- `object(...)`

## Environment pattern

```text
main.tf
   +
variables.tf
   +
terraform.tfvars (local / secure)
   =
Reusable configuration
```

Never commit sensitive values merely because they are stored in a variable file.
