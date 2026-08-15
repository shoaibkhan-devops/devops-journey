# 🖥️ Azure Virtual Machines

Azure VMs provide configurable compute while still requiring traditional administration disciplines: OS management, networking, identity, patching, backup and monitoring.

## VM lifecycle

```text
Plan → Network → Provision → Harden → Patch → Monitor → Backup → Decommission
```

## Key decisions

- VM size and workload profile
- Managed disk type
- Availability requirements
- Network placement
- NSG rules
- Identity and access
- Backup / DR
- Monitoring and alerting

## CLI example

```bash
az vm list -o table
az vm show -g rg-devops-demo -n vm-devops-demo
```
