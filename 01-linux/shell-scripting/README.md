# 🐚 Shell Scripting

Shell scripting turns repeatable administrative work into automation.

## Core concepts

- Variables and environment variables
- Exit codes
- Conditions and loops
- Functions
- Arguments
- Input/output redirection
- Pipes
- Logging
- Error handling
- Cron scheduling

## Example

```bash
#!/usr/bin/env bash
set -euo pipefail

HOSTNAME=$(hostname)
DATE=$(date '+%Y-%m-%d %H:%M:%S')

echo "[$DATE] Running on $HOSTNAME"

if systemctl is-active --quiet ssh; then
  echo "SSH service is running"
else
  echo "SSH service is not running" >&2
  exit 1
fi
```

## DevOps use cases

```text
Health checks → log collection → backup scripts → deployment helpers → CI/CD jobs
```

## Practice ideas

- Disk-space alert script
- Service health checker
- Log cleanup script
- User onboarding script
- Azure CLI wrapper scripts
