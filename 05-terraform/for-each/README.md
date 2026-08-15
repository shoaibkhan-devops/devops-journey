# 🔁 Terraform `for_each`

`for_each` is useful when multiple resources have distinct, stable keys.

```hcl
variable "storage_accounts" {
  type = map(string)

  default = {
    logs = "Standard_LRS"
    data = "Standard_GRS"
  }
}
```

A resource can then iterate through the map so that each instance has a meaningful key.

## Why use it?

- Stable resource addressing
- Clear instance identity
- Better for maps and objects
- Easier selective changes

## Compare

```text
count    → usually positional instances
for_each → keyed instances
```
