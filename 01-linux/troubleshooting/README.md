# 🔎 Linux Troubleshooting

The troubleshooting mindset is often more valuable than knowing a single command.

## A practical sequence

```text
1. Define the symptom
2. Check scope and impact
3. Check recent changes
4. Inspect logs
5. Validate CPU / memory / disk
6. Validate network connectivity
7. Reproduce safely
8. Fix and verify
9. Document the root cause
```

## Common checks

| Symptom | First checks |
|---|---|
| Server is slow | `top`, `free -h`, `df -h` |
| Service unavailable | `systemctl status`, `journalctl` |
| Port unreachable | `ss -tulpn`, `curl`, `nc` |
| DNS issue | `nslookup`, `dig` |
| Disk full | `df -h`, `du -sh` |
| Authentication issue | SSH logs, permissions, user/group membership |

## DevOps lesson

Good operations teams do not only restore service. They capture the cause, the fix, the prevention and the automation opportunity.
