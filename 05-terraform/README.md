# 🏗️ Terraform & Infrastructure as Code

Terraform is a major part of my DevOps journey because it turns infrastructure into version-controlled, reviewable and repeatable code.

## Workflow

```text
Write → Format → Init → Validate → Plan → Review → Apply → Monitor
```

## Topics

- Providers
- Resources
- Variables
- Outputs
- Locals
- Data sources
- Expressions and functions
- `count` / `for_each`
- Modules
- State
- Backends
- Remote state
- Import
- Dependency management
- CI/CD

## Sub-sections

- [Basics](./basics/)
- [Azure](./azure/)
- [Variables](./variables/)
- [Outputs](./outputs/)
- [Loops](./loops/)
- [`for_each`](./for-each/)
- [Modules](./modules/)
- [Backend](./backend/)
- [Remote State](./remote-state/)

## Commands

```bash
terraform fmt -recursive
terraform init
terraform validate
terraform plan
terraform apply
terraform destroy
```
