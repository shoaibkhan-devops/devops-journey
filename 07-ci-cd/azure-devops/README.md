# 🔵 Azure DevOps Pipelines

Azure Pipelines can automate application and infrastructure delivery using YAML or classic pipelines.

## Typical structure

```yaml
stages:
  - Build
  - Test
  - Deploy
```

## Key concepts

- Agents
- Jobs and steps
- Variables
- Variable groups
- Service connections
- Environments
- Approvals
- Artifacts

## Terraform use case

PR → validate/plan → approval → apply.
