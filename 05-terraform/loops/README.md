# 🔁 Terraform Loops & Expressions

Terraform supports iteration and collection expressions for building reusable infrastructure.

## Topics

- `for` expressions
- Conditional expressions
- `count`
- `for_each`
- `flatten`
- `merge`
- `lookup`
- `try`

## Example

```hcl
locals {
  names = [for env in ["dev", "test", "prod"] : "rg-${env}"]
}
```

The objective is to model patterns without creating repetitive blocks that are difficult to maintain.
