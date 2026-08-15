# 🔄 Git & GitHub Workflows

A good workflow should make changes reviewable, traceable and safe.

## Infrastructure workflow

```text
Issue → Branch → Code → Local validation → Pull Request → Review → Merge → Pipeline → Deploy
```

## Recommended controls

- Protected `main` branch
- Pull-request review
- Status checks
- Secret scanning
- Dependabot / dependency updates
- CI validation before merge
- Release tags for important versions

## Future lab

Create a pull request that runs `terraform fmt`, `terraform validate` and `terraform plan` before merge.
