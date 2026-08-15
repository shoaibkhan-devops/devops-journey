# 🚀 DevOps Journey | Infrastructure → Cloud → Automation

<p align="center">
  <img src="https://img.shields.io/badge/Azure-Cloud%20Engineering-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-Infrastructure%20as%20Code-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-System%20Administration-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/DevOps-Automation-326CE5?style=for-the-badge&logo=azuredevops&logoColor=white" />
</p>

<p align="center">
  <b>20 Years of IT Infrastructure & Operations → Cloud → IaC → Automation → DevOps</b>
</p>

---

## 👋 About This Journey

Welcome to my **DevOps & Cloud Engineering journey**.

I come from an enterprise **IT Infrastructure & Operations** background with 20 years of experience across infrastructure management, cloud operations, virtualization, networking, identity, cybersecurity, backup, disaster recovery, IT service delivery and vendor management.

My DevOps journey is about bringing that infrastructure experience into modern engineering practices:

> **Cloud + Automation + Infrastructure as Code + CI/CD + Containers + Security + Observability**

Rather than treating DevOps as a completely new career path, I see it as the natural evolution of infrastructure engineering.

```text
Traditional Infrastructure
        │
        ▼
   Virtualization
        │
        ▼
   Cloud Computing
        │
        ▼
 Infrastructure as Code
        │
        ▼
     Automation
        │
        ▼
       CI/CD
        │
        ▼
 Containers & Kubernetes
        │
        ▼
 DevSecOps & Observability
        │
        ▼
Cloud / DevOps Engineering
```

---

## 🎯 My DevOps Philosophy

DevOps is not simply about learning tools.

It is about changing **how infrastructure and applications are built, deployed, secured, monitored and improved**.

```text
PLAN → CODE → BUILD → TEST → SECURE → RELEASE → DEPLOY → MONITOR → IMPROVE ↺
```

My goal is to make infrastructure:

- **Repeatable**
- **Predictable**
- **Secure**
- **Observable**
- **Automated**
- **Recoverable**
- **Cost-aware**

---

# 🗺️ DevOps Learning Map

```text
                         ┌──────────────────┐
                         │      DEVOPS      │
                         └────────┬─────────┘
                                  │
          ┌───────────────────────┼────────────────────────┐
          │                       │                        │
          ▼                       ▼                        ▼
      DEVELOPMENT              OPERATIONS              SECURITY
          │                       │                        │
      Git/GitHub              Linux                     IAM
      Python                  Azure                     RBAC
      Bash                    Networking                Secrets
      APIs                    Monitoring                DevSecOps
          │                       │                        │
          └───────────────┬───────┴───────────────┬────────┘
                          │                       │
                          ▼                       ▼
                    AUTOMATION                 CLOUD
                          │                       │
                      Terraform               Azure
                      Ansible                 Entra ID
                      PowerShell              Governance
                          │                       │
                          └───────────┬───────────┘
                                      ▼
                                CI/CD PIPELINES
                                      │
                         ┌────────────┴────────────┐
                         ▼                         ▼
                     Containers              Kubernetes
                         │                         │
                         └────────────┬────────────┘
                                      ▼
                                OBSERVABILITY
```

---

# ☁️ 01 — Cloud Computing

My primary cloud focus is **Microsoft Azure**.

### Azure Core

- Azure Resource Groups
- Regions & Availability Zones
- Virtual Machines
- Managed Disks
- Storage Accounts
- Blob Storage
- Azure Files
- Storage Tiers
- Virtual Networks & Subnets
- NSGs
- Public & Private IP
- DNS
- Load Balancer
- Application Gateway
- Azure Front Door
- Traffic Manager
- Azure Bastion
- VPN Gateway
- IPsec VPN
- VNet Peering
- Private Endpoints

### Azure Architecture

```text
                    Azure
                      │
       ┌──────────────┼──────────────┐
       │              │              │
   Compute         Network        Storage
       │              │              │
      VM             VNet        Storage Account
       │              │              │
     Scale         Subnet           Blob
       │              │              │
       └──────────────┼──────────────┘
                      │
                 Identity
                      │
                  Entra ID
                      │
                RBAC / IAM
```

---

# 🏗️ 02 — Azure Landing Zones & Governance

Enterprise cloud needs more than individual resources. It needs **structure, governance, security and standards**.

### Topics

- Azure Landing Zones
- Management Groups
- Subscriptions
- Resource Groups
- Azure Policy
- RBAC
- Naming Standards
- Tagging
- Governance
- Security Baselines
- Cost Management
- Network Architecture
- Hub & Spoke
- Enterprise-scale concepts

```text
Tenant
  │
  └── Management Groups
          │
          ├── Production
          │      └── Subscriptions
          │
          ├── Non-Production
          │      └── Subscriptions
          │
          └── Sandbox
                 └── Subscription
```

---

# 🔐 03 — Identity & Security

Security should be part of the engineering lifecycle, not an afterthought.

### Identity

- Microsoft Entra ID
- Users & Groups
- Service Principals
- Managed Identities
- RBAC
- Least Privilege
- Conditional Access concepts
- Authentication & Authorization

### Security

- Network Security Groups
- Key Vault
- Secrets Management
- Zero Trust concepts
- Secure authentication
- Identity governance
- Infrastructure security

---

# 🐧 04 — Linux

Linux is a core foundation for modern cloud and DevOps engineering.

### Areas

- File system
- Permissions
- Users & Groups
- Processes
- Services / systemd
- Networking
- SSH
- Package management
- Environment variables
- Logs
- Disk management
- Cron jobs
- Shell scripting
- Troubleshooting

### Commands

```bash
ls  cd  pwd  cp  mv  rm  mkdir  touch
cat less grep find awk sed sort
chmod chown ps top df du free
ip ss curl wget ssh systemctl journalctl
```

---

# 🔀 05 — Git & GitHub

Git is the foundation for collaborative software and infrastructure delivery.

### Concepts

- Repository
- Working tree
- Staging
- Commit
- Branch
- Merge
- Rebase
- Pull Request
- Tag
- Remote
- Clone
- Fork
- Conflict Resolution

### Workflow

```text
Local Changes
     │
     ▼
   git add
     │
     ▼
  git commit
     │
     ▼
   git push
     │
     ▼
   GitHub
     │
     ▼
 Pull Request
     │
     ▼
 Code Review
     │
     ▼
   Merge
```

---

# 🏗️ 06 — Infrastructure as Code

## Terraform

Terraform is one of the major focus areas of my DevOps journey.

### Core Concepts

- Providers
- Resources
- Variables
- Outputs
- Locals
- Data Sources
- `.tfvars`
- Dependencies
- Expressions & Functions
- `count`
- `for_each`
- Conditional expressions
- Dynamic blocks
- Modules
- State
- Remote State
- Backend
- State locking
- Import
- Workspaces

### Workflow

```text
Terraform Code
      │
      ▼
terraform fmt
      │
      ▼
terraform init
      │
      ▼
terraform validate
      │
      ▼
terraform plan
      │
      ▼
terraform apply
      │
      ▼
Azure Infrastructure
```

### Example

```hcl
resource "azurerm_resource_group" "example" {
  name     = "rg-devops-demo"
  location = "Central India"
}
```

### Remote State

```text
Developer
    │
    │ terraform
    ▼
Terraform CLI
    │
    ├──────────────► Azure Provider
    │
    ▼
Azure Storage Account
    │
    └── Terraform State
```

---

# 📦 07 — Terraform Modules

Reusable modules make infrastructure easier to maintain and scale.

```text
Terraform Root Module
        │
        ├── Network Module
        │      ├── VNet
        │      └── Subnets
        │
        ├── Compute Module
        │      └── Virtual Machines
        │
        ├── Storage Module
        │      └── Storage Accounts
        │
        └── Security Module
               └── NSG / RBAC
```

**Write once → Reuse many times.**

---

# 🔁 08 — CI/CD

## Continuous Integration

```text
Developer
   ↓
Git Push
   ↓
Build
   ↓
Test
   ↓
Security Scan
   ↓
Artifact
```

## Continuous Delivery / Deployment

```text
Artifact
   ↓
Dev
   ↓
Test
   ↓
UAT
   ↓
Production
```

### Pipeline principles

- Automated builds
- Automated testing
- Infrastructure validation
- Security scanning
- Approval gates
- Environment separation
- Secrets management
- Artifact management
- Deployment strategies
- Rollback

---

# 🔵 09 — Azure DevOps

### Areas

- Azure Repos
- Azure Pipelines
- Azure Boards
- Azure Test Plans
- Azure Artifacts
- YAML pipelines
- Variables
- Variable Groups
- Service Connections
- Environments
- Approvals
- Deployment Gates
- CI/CD for Terraform

### Terraform CI/CD

```text
Git Repository
      │
      ▼
Pull Request
      │
      ▼
terraform fmt
      │
      ▼
terraform validate
      │
      ▼
terraform plan
      │
      ▼
Code Review
      │
      ▼
Approval
      │
      ▼
terraform apply
      │
      ▼
Azure
```

---

# 🐳 10 — Containers

### Docker topics

- Images
- Containers
- Dockerfile
- Docker CLI
- Volumes
- Networks
- Environment Variables
- Registries
- Docker Compose
- Container Security

```text
Dockerfile
    ↓
docker build
    ↓
Docker Image
    ↓
Container Registry
    ↓
docker pull
    ↓
Container
    ↓
Application
```

---

# ☸️ 11 — Kubernetes

### Topics

- Cluster
- Node
- Pod
- Deployment
- ReplicaSet
- Service
- Namespace
- ConfigMap
- Secret
- Ingress
- Persistent Volume
- Persistent Volume Claim
- StatefulSet
- DaemonSet
- Jobs
- CronJobs
- HPA
- Helm

### Architecture

```text
                 Kubernetes Cluster
                        │
              ┌─────────┴─────────┐
              │                   │
         Control Plane          Nodes
              │                   │
      ┌───────┼───────┐      ┌────┴────┐
      │       │       │      │         │
     API   Scheduler  etcd   Pod       Pod
     Server                    │
                              Container
```

---

# ⚙️ 12 — Configuration Management

Automation should continue beyond infrastructure provisioning.

### Tools

- Ansible
- PowerShell
- Bash
- Azure CLI

```text
Infrastructure
      ↓
Provision
      ↓
Configure
      ↓
Deploy
      ↓
Validate
      ↓
Monitor
```

---

# 🐚 13 — Scripting & Automation

### Technologies

- Bash
- PowerShell
- Python
- Azure CLI
- REST APIs

### Automation mindset

```text
Manual Task
     ↓
Identify Repetition
     ↓
Create Script
     ↓
Test
     ↓
Schedule / Pipeline
     ↓
Monitor
     ↓
Improve
```

---

# 📊 14 — Monitoring & Observability

Infrastructure that cannot be observed cannot be effectively operated.

### Monitoring

- Azure Monitor
- Log Analytics
- Metrics
- Alerts
- Activity Logs
- Application Insights
- Network Monitoring

### Observability

```text
                Observability
                     │
        ┌────────────┼────────────┐
        │            │            │
       Logs        Metrics       Traces
        │            │            │
        └────────────┼────────────┘
                     │
                  Insights
                     │
                  Alerts
                     │
                   Action
```

---

# 🛡️ 15 — DevSecOps

Security should move left and remain active throughout delivery.

```text
Security
   ↓
Plan → Code → Build → Test → Release → Deploy → Monitor
   ↑                                            ↓
   └──────────── Continuous Feedback ──────────┘
```

### Topics

- SAST
- DAST
- Dependency Scanning
- Container Scanning
- IaC Security
- Secrets Detection
- Vulnerability Management
- RBAC
- Key Vault
- Secure Pipelines
- Least Privilege

---

# 💰 16 — FinOps & Cloud Cost Optimization

Cloud engineering also needs financial discipline.

### Areas

- Azure Cost Management
- Resource Tagging
- Right-sizing
- Reserved capacity concepts
- Autoscaling
- Storage optimization
- Idle resource detection
- Environment scheduling
- Budget alerts
- Cost allocation

```text
Cloud Usage
     ↓
Visibility
     ↓
Analyze
     ↓
Optimize
     ↓
Automate
     ↓
Measure
     ↺
```

---

# 🌐 17 — Networking for DevOps

### Core networking

```text
OSI Model
TCP/IP
IPv4
CIDR
Subnetting
DNS
DHCP
Routing
NAT
Ports
Firewalls
VPN
TLS
HTTP / HTTPS
Load Balancing
Reverse Proxy
Private Endpoints
```

### Azure networking

```text
Azure
 │
 └── VNet
      │
      ├── Web Subnet
      │      └── Application
      │
      ├── App Subnet
      │      └── Services
      │
      └── Data Subnet
             └── Database
```

---

# 🔄 18 — Disaster Recovery & Resilience

Infrastructure reliability is a major part of my existing operations background and a natural bridge into DevOps and SRE practices.

### Topics

- Backup
- Disaster Recovery
- RPO
- RTO
- High Availability
- Availability Zones
- Failover
- Business Continuity
- DR Testing
- Recovery automation

```text
Prevent
  ↓
Detect
  ↓
Respond
  ↓
Recover
  ↓
Learn
  ↓
Improve
```

---

# 🧪 19 — Infrastructure Testing

Infrastructure code should be treated like application code.

```text
Terraform Format
       ↓
Terraform Validate
       ↓
Terraform Plan
       ↓
Security Scan
       ↓
Policy Validation
       ↓
Deployment
       ↓
Post Deployment Validation
```

---

# 🔑 20 — Secrets & Configuration Management

Never hard-code credentials or secrets.

```text
Application
     │
     ▼
Secret Store
     │
     ▼
Managed Identity
     │
     ▼
Secret
```

### Areas

- Azure Key Vault
- Managed Identity
- Service Connections
- Pipeline Secrets
- Environment Variables
- Secret Rotation
- Least Privilege

---

# 🌍 21 — Environment Strategy

A mature delivery platform separates change by environment while keeping deployment patterns consistent.

```text
                    Git
                     │
                     ▼
              ┌─────────────┐
              │ Development │
              └──────┬──────┘
                     │
                     ▼
                  Testing
                     │
                     ▼
                    UAT
                     │
                     ▼
                Production
```

---

# 📚 22 — DevOps Technology Landscape

| Area | Technologies |
|---|---|
| Cloud | Microsoft Azure |
| Source Control | Git, GitHub |
| CI/CD | Azure DevOps, GitHub Actions |
| IaC | Terraform |
| Configuration | Ansible |
| OS | Linux, Windows |
| Containers | Docker |
| Orchestration | Kubernetes |
| Scripting | PowerShell, Bash, Python |
| Identity | Microsoft Entra ID |
| Security | RBAC, Key Vault, Azure security services |
| Networking | VNet, NSG, VPN, Load Balancer, Application Gateway |
| Monitoring | Azure Monitor, Log Analytics |
| Governance | Azure Policy, Management Groups |
| Cost | Azure Cost Management |

---

# 🧰 23 — My DevOps Lab

This repository is my hands-on engineering laboratory.

I believe in:

> **Learn → Build → Break → Troubleshoot → Automate → Document**

```text
Learn Concept
     ↓
Build Lab
     ↓
Introduce Failure
     ↓
Troubleshoot
     ↓
Fix
     ↓
Automate
     ↓
Document
     ↓
Repeat
```

---

# 📂 Repository Structure

```text
devops-journey/
│
├── 01-linux/
├── 02-git-github/
├── 03-azure/
├── 04-identity-security/
├── 05-terraform/
├── 06-azure-landing-zone/
├── 07-ci-cd/
├── 08-docker/
├── 09-kubernetes/
├── 10-ansible/
├── 11-monitoring/
├── 12-devsecops/
├── 13-finops/
├── 14-projects/
└── README.md
```

Each folder is intended to contain:

- A focused `README.md`
- Source/configuration files
- Architecture diagrams where useful
- Screenshots for labs
- Troubleshooting notes
- Lessons learned

---

# 🚀 24 — Featured Projects

| Project | Focus |
|---|---|
| Azure Infrastructure with Terraform | IaC, Azure, networking, compute, storage |
| Azure Landing Zone | Governance, subscriptions, policy, RBAC, architecture |
| Secure Azure Infrastructure | Entra ID, RBAC, Managed Identity, Key Vault |
| Terraform CI/CD | Git, validation, plan, approvals, apply |
| Containerized Application | Docker, image build, registry, deployment |
| Kubernetes Deployment | Pods, services, deployments, ingress, Helm |
| Monitoring & Observability Lab | Metrics, logs, alerts, dashboards |
| DevSecOps Pipeline | SAST, secrets, IaC and container security |
| Cloud Cost Optimization | Right-sizing, tagging, budgets, automation |

---

# 📈 25 — DevOps Roadmap

### ✅ Foundation

- [x] IT Infrastructure
- [x] Networking
- [x] Windows Administration
- [x] Virtualization
- [x] Cloud Fundamentals
- [x] Azure Fundamentals
- [x] Git Fundamentals
- [x] Linux Fundamentals

### 🔄 In Progress

- [x] Azure CLI
- [x] Azure Virtual Machines
- [x] Azure Networking
- [x] Azure Storage
- [x] Entra ID
- [x] RBAC
- [x] Azure Governance
- [x] Terraform Fundamentals
- [x] Terraform Variables
- [x] Terraform `for_each`
- [x] Terraform Backend
- [x] Terraform Remote State
- [x] Azure Landing Zone concepts

### 🚀 Next Level

- [ ] Advanced Terraform Modules
- [ ] Terraform Testing
- [ ] Terraform Security
- [ ] Azure DevOps Pipelines
- [ ] GitHub Actions
- [ ] CI/CD Automation
- [ ] Docker
- [ ] Kubernetes
- [ ] Helm
- [ ] Ansible
- [ ] Advanced Bash
- [ ] Python Automation
- [ ] DevSecOps
- [ ] Observability
- [ ] Advanced Azure Architecture

### 🌟 Continuous Learning

- [ ] Platform Engineering
- [ ] GitOps
- [ ] Kubernetes Security
- [ ] Cloud Native Architecture
- [ ] Advanced DevSecOps
- [ ] FinOps
- [ ] SRE Practices
- [ ] AI-assisted DevOps
- [ ] Infrastructure Automation at Scale

---

# 🧠 26 — What I Am Building

My objective is not to collect technologies for the sake of a checklist.

I want to build systems where:

```text
Infrastructure
      +
Automation
      +
Security
      +
Observability
      +
Reliability
      +
Cost Awareness
      +
Continuous Delivery
      │
      ▼
   ENGINEERED
   OPERATIONS
```

---

# 💡 27 — Lessons From the Journey

### 01 — Automation removes repetitive work

Use automation to reduce manual effort and free engineers for higher-value work.

### 02 — Infrastructure should be reproducible

If rebuilding an environment requires dozens of manual steps, there is an opportunity for IaC.

### 03 — Security belongs everywhere

Security should not be added only after deployment.

### 04 — Monitoring is not enough

The goal is **observability + actionable insight**.

### 05 — Cloud is not automatically cheaper

Poor architecture can make cloud more expensive than traditional infrastructure.

### 06 — DevOps is a culture as much as a technology

Tools enable DevOps. People, process and collaboration make it successful.

---

# 🏆 28 — The Bigger Picture

```text
20 Years
Infrastructure & Operations
          │
          ▼
     Cloud Computing
          │
          ▼
         Azure
          │
          ▼
 Infrastructure as Code
          │
          ▼
       Terraform
          │
          ▼
       Automation
          │
          ▼
         CI/CD
          │
          ▼
      Containers
          │
          ▼
      Kubernetes
          │
          ▼
      DevSecOps
          │
          ▼
    Observability
          │
          ▼
Platform / Cloud Engineering
```

---

# 📌 29 — My DevOps Principles

```text
Infrastructure as Code
        ↓
Everything Version Controlled
        ↓
Automate Repetitive Work
        ↓
Security by Design
        ↓
Least Privilege
        ↓
Continuous Integration
        ↓
Continuous Delivery
        ↓
Observable Systems
        ↓
Reliable Infrastructure
        ↓
Continuous Improvement
```

---

# 🤝 Let's Connect

I'm documenting this journey through:

🔹 Hands-on Azure labs  
🔹 Terraform projects  
🔹 Infrastructure automation  
🔹 CI/CD experiments  
🔹 Cloud architecture  
🔹 Linux & scripting  
🔹 DevSecOps concepts  
🔹 Troubleshooting notes  
🔹 Real-world infrastructure scenarios

If you are also learning **Cloud, DevOps, Terraform, Azure or Infrastructure Automation**, feel free to explore the repositories and connect.

---

<p align="center">
  <b>🚀 Build. Automate. Secure. Observe. Improve.</b>
  <br />
  Infrastructure → Cloud → IaC → Automation → DevOps
</p>

<p align="center">
  ⭐ If you find something useful, consider starring the repository.
</p>
