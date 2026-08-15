# 🟣 GitHub Actions

GitHub Actions provides CI/CD workflows directly inside a GitHub repository.

## Example

```yaml
name: Terraform CI

on:
  pull_request:

jobs:
  validate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - run: terraform fmt -check -recursive
      - run: terraform init
      - run: terraform validate
```

## Areas to learn

- Workflow triggers
- Jobs and steps
- Secrets / environments
- Reusable workflows
- Artifacts
- Matrix builds
- OIDC authentication to Azure
