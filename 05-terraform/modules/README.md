# 📦 Terraform Modules

Modules package reusable infrastructure patterns.

## Example

```text
root module
│
├── module.network
├── module.compute
└── module.monitoring
```

## A good module should

- Have a clear responsibility
- Expose useful variables and outputs
- Avoid hidden dependencies
- Be versioned
- Be easy to test and document

Modules help teams standardize how infrastructure is built.
