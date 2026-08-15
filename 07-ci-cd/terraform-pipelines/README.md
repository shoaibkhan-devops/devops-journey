# 🏗️ Terraform CI/CD Pipelines

The goal is to move Terraform from a laptop workflow into a controlled engineering process.

## Pull Request stage

```text
terraform fmt
      ↓
terraform validate
      ↓
security / policy checks
      ↓
terraform plan
```

## Deployment stage

```text
Review → Approval → terraform apply → Verification
```

## Guardrails

- Do not auto-apply unreviewed changes to production
- Use workload identity / OIDC where supported
- Protect state
- Keep secrets out of the repository
