# 🔐 Azure Bastion

Azure Bastion provides browser-based RDP/SSH connectivity to VMs without exposing the VM's public IP for management access.

## Traffic concept

```text
Administrator
      ↓ HTTPS
Azure Bastion
      ↓
Private VNet
      ↓
VM (Private IP)
```

## Troubleshooting checklist

- Bastion is deployed in `AzureBastionSubnet` with the required sizing
- VM has a healthy network interface
- NSG rules permit required traffic
- VNet / peering / routing is correct
- VM is running and responsive
- Identity / credential details are valid

## Security benefit

The key benefit is reducing direct exposure of administrative services such as RDP and SSH to the public internet.
