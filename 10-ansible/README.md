# ⚙️ Ansible

Ansible is a configuration-management and automation tool that can configure systems, deploy software and orchestrate operational tasks.

## Concepts

- Inventory
- Playbooks
- Tasks
- Modules
- Variables
- Roles
- Handlers
- Idempotency

## Pattern

```text
Provision infrastructure → Configure operating system → Deploy application → Validate
```

Terraform creates infrastructure; Ansible can configure what lives inside it. The tools can complement each other.
