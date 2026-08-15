# 🚀 DevOps Journey | Infrastructure → Cloud → Automation

<p align="center">

[<img src="https://img.shields.io/badge/Azure-Cloud%20Engineering-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />](03-azure/)
[<img src="https://img.shields.io/badge/Terraform-Infrastructure%20as%20Code-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />](05-terraform/)
[<img src="https://img.shields.io/badge/Linux-System%20Administration-FCC624?style=for-the-badge&logo=linux&logoColor=black" />](01-linux/)
[<img src="https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white" />](02-git-github/)
[<img src="https://img.shields.io/badge/DevOps-Automation-326CE5?style=for-the-badge&logo=azuredevops&logoColor=white" />](07-ci-cd/)

</p>

<p align="center">
  <b>20 Years of IT Infrastructure & Operations → Cloud → IaC → Automation → DevOps</b>
</p>

---

## 👋 About This Journey

Welcome to my **DevOps & Cloud Engineering journey**.

I come from an enterprise **IT Infrastructure & Operations** background with 20 years of experience across infrastructure management, cloud operations, virtualization, networking, identity, cybersecurity, backup, disaster recovery, IT service delivery and vendor management.

My DevOps journey is about bringing that infrastructure experience into the world of:

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

# 🎯 My DevOps Philosophy

DevOps is not simply about learning tools.

It's about changing **how infrastructure and applications are built, deployed, secured, monitored and operated**.

My approach:

```text
PLAN
  ↓
CODE
  ↓
BUILD
  ↓
TEST
  ↓
SECURE
  ↓
RELEASE
  ↓
DEPLOY
  ↓
MONITOR
  ↓
IMPROVE
  ↺
```

The goal is simple:

**Make infrastructure repeatable.  
Make deployments predictable.  
Make operations measurable.  
Make changes safer.  
Automate wherever automation creates value.**

---

# 🗺️ DevOps Learning Map

```text
                         ┌──────────────────┐
                         │     DEVOPS       │
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
                                      │
                                      ▼
                              CONTINUOUS IMPROVEMENT
```

---

# ☁️ 01 — Cloud Computing

My primary cloud focus is **Microsoft Azure**.

### Azure Core

- Azure Resource Groups
- Azure Regions
- Availability Zones
- Virtual Machines
- Managed Disks
- Storage Accounts
- Blob Storage
- Azure Files
- Storage Tiers
- Azure Tables
- Azure Queues
- Virtual Networks
- Subnets
- Network Security Groups
- Public & Private IP
- DNS
- Load Balancer
- Application Gateway
- Azure Front Door
- Azure Traffic Manager
- Azure Bastion
- VPN Gateway
- IPsec VPN
- VNet Peering
- Hub & Spoke Architecture

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

One of the important areas of my cloud journey is understanding how enterprise Azure environments should be designed rather than simply creating individual resources.

### Topics

- Azure Landing Zones
- Management Groups
- Subscriptions
- Resource Groups
- Azure Policy
- RBAC
- Resource Organization
- Naming Standards
- Tagging
- Governance
- Security Baselines
- Cost Management
- Identity & Access Management
- Network Architecture
- Hub & Spoke
- Enterprise-scale concepts

### Enterprise Structure

```text
Tenant
  │
  └── Management Groups
          │
          ├── Production
          │      ├── Subscription
          │      └── Resources
          │
          ├── Non-Production
          │      ├── Subscription
          │      └── Resources
          │
          └── Sandbox
                 └── Subscription
```

---

# 🔐 03 — Identity & Security

Security is not a separate phase of DevOps.

It should be integrated throughout the lifecycle.

### Identity

- Microsoft Entra ID
- Users
- Groups
- Service Principals
- Managed Identities
- RBAC
- Least Privilege
- Conditional Access
- Authentication
- Authorization

### Security

- Network Security Groups
- Azure Firewall concepts
- Zero Trust
- Secrets Management
- Key Vault
- Secure authentication
- Identity governance
- Infrastructure security

### Security Mindset

```text
Developer
    ↓
Source Code
    ↓
Build
    ↓
Security Scan
    ↓
Infrastructure
    ↓
Deployment
    ↓
Runtime
    ↓
Monitoring
```

---

# 🐧 04 — Linux

Linux is a fundamental part of my DevOps journey.

### Areas

- Ubuntu
- RHEL concepts
- File system
- Permissions
- Users & Groups
- Processes
- Services
- Systemd
- Networking
- SSH
- Package management
- Environment variables
- Logs
- Disk management
- Cron jobs
- Shell scripting
- Troubleshooting

### Essential Commands

```bash
ls
cd
pwd
cp
mv
rm
mkdir
touch
cat
less
grep
find
awk
sed
sort
chmod
chown
ps
top
df
du
free
ip
ss
curl
wget
ssh
systemctl
journalctl
```

---

# 🔀 05 — Git & GitHub

Git is the foundation of infrastructure and application collaboration.

### Git Concepts

- Repository
- Working Tree
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
- Git workflows

### Typical Workflow

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

- Terraform Providers
- Resources
- Variables
- Outputs
- Locals
- Data Sources
- `.tfvars`
- Resource Dependencies
- Expressions
- Functions
- `count`
- `for_each`
- Conditional Expressions
- Dynamic Blocks
- Modules
- State
- Remote State
- Backend
- State Locking
- Import
- Workspaces
- Terraform Plan
- Terraform Apply
- Terraform Destroy

### Terraform Workflow

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

# 🔁 07 — CI/CD

The next step is connecting infrastructure and application code to automated pipelines.

### CI — Continuous Integration

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

### CD — Continuous Delivery / Deployment

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

### Pipeline Principles

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

# 🔵 08 — Azure DevOps

Areas to explore and implement:

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

# 🐳 09 — Containers

Containerization is a key step toward modern application delivery.

### Docker

Topics:

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

### Container Lifecycle

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

# ☸️ 10 — Kubernetes

The next layer of the container journey.

### Kubernetes Concepts

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
- Horizontal Pod Autoscaler
- Helm

### Kubernetes Architecture

```text
                 Kubernetes Cluster
                        │
              ┌─────────┴─────────┐
              │                   │
         Control Plane          Nodes
              │                   │
      ┌───────┼───────┐      ┌────┴────┐
      │       │       │      │         │
     API   Scheduler  etcd   Pod      Pod
     Server                    │
                              Container
```

---

# ⚙️ 11 — Configuration Management

Automation should not stop at infrastructure creation.

### Tools

- Ansible
- PowerShell
- Bash
- Azure CLI

### Automation Flow

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

# 📊 12 — Monitoring & Observability

Infrastructure that cannot be observed cannot be effectively operated.

### Monitoring

- Azure Monitor
- Log Analytics
- Metrics
- Alerts
- Activity Logs
- Application Insights
- Infrastructure Monitoring
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

# 🛡️ 13 — DevSecOps

Security should move left.

```text
Traditional

Code → Build → Deploy → Security


DevSecOps

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

# 💰 14 — FinOps & Cloud Cost Optimization

Cloud engineering is not only about making infrastructure work.

It also needs to be financially sustainable.

### Areas

- Azure Cost Management
- Resource Tagging
- Right-sizing
- Reserved Capacity
- Autoscaling
- Storage Optimization
- Idle Resource Identification
- Environment Scheduling
- Budget Alerts
- Cost Allocation

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

# 🌐 15 — Networking for DevOps

A strong networking foundation is essential for cloud and DevOps.

### Topics

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
HTTP/HTTPS
Load Balancing
Reverse Proxy
Private Endpoints
```

### Azure Networking

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

# 🔄 16 — Disaster Recovery & Resilience

My infrastructure background also connects strongly with DevOps reliability practices.

### Topics

- Backup
- Disaster Recovery
- RPO
- RTO
- High Availability
- Availability Zones
- Azure Site Recovery concepts
- Azure Backup
- Failover
- Business Continuity
- DR Testing
- Infrastructure Recovery Automation

### Resilience Mindset

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

# 🧪 17 — Testing Infrastructure

Infrastructure code should be treated like application code.

### Validation

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

# 🌍 18 — Environment Strategy

A mature DevOps environment should separate workloads and changes.

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

Infrastructure should be **consistent across environments while allowing environment-specific configuration**.

---

# 🔑 19 — Secrets & Configuration Management

Never hard-code secrets.

❌ Bad:

```text
username = "admin"
password = "MyPassword123"
```

✅ Better:

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

Areas:

- Azure Key Vault
- Managed Identity
- Service Connections
- Pipeline Secrets
- Environment Variables
- Secret Rotation
- Least Privilege

---

# 📚 20 — DevOps Tools Landscape

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
| Security | Azure Security, RBAC, Key Vault |
| Networking | Azure VNet, NSG, VPN, Firewall |
| Monitoring | Azure Monitor, Log Analytics |
| Artifacts | Azure Artifacts, Container Registries |
| Collaboration | Azure Boards, GitHub |
| Automation | Azure CLI, PowerShell, Terraform |
| Governance | Azure Policy, Management Groups |
| Cost | Azure Cost Management |

---

# 🧰 21 — My DevOps Lab Environment

This repository is my hands-on laboratory.

Instead of only reading documentation, I believe in:

> **Learn → Build → Break → Troubleshoot → Automate → Document**

Example lab lifecycle:

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

# 📂 22 — Repository Structure

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

---

# 🚀 23 — Featured Projects

The repository will progressively contain hands-on projects rather than only theoretical notes.

### 🏗️ Azure Infrastructure with Terraform

Provision Azure infrastructure using Infrastructure as Code.

**Focus:** `Terraform → Azure → Networking → Compute → Storage → RBAC`

### ☁️ Azure Landing Zone

Design an enterprise-oriented Azure foundation.

**Focus:** `Management Groups → Subscriptions → Governance → Policy → RBAC → Networking`

### 🔐 Secure Azure Infrastructure

Build infrastructure following least-privilege and security principles.

**Focus:** `Entra ID → RBAC → Managed Identity → Key Vault → NSG → Private Access`

### 🔄 Terraform CI/CD Pipeline

Automate infrastructure deployment through CI/CD.

```text
GitHub
   ↓
Pull Request
   ↓
Validation
   ↓
Terraform Plan
   ↓
Review
   ↓
Approval
   ↓
Terraform Apply
   ↓
Azure
```

### 🐳 Containerized Application

Package an application into a Docker container and deploy it through a CI/CD pipeline.

### ☸️ Kubernetes Deployment

Deploy and manage containerized workloads using Kubernetes.

---

# 📈 24 — DevOps Roadmap

### ✅ Foundation

- [x] IT Infrastructure
- [x] Networking
- [x] Windows Administration
- [x] Virtualization
- [x] Cloud Fundamentals
- [x] Azure Fundamentals
- [x] Git Fundamentals
- [x] Linux Fundamentals

### 🔄 Current Focus

- [x] Azure CLI
- [x] Azure VMs
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

# 🧠 25 — What I Am Building

My objective is not to collect certifications or memorize commands.

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

# 💡 26 — Lessons From the Journey

### 01 — Automation is not about replacing people

It's about removing repetitive work so engineers can focus on higher-value problems.

### 02 — Infrastructure should be reproducible

If rebuilding an environment requires dozens of manual steps, there is an opportunity for automation.

### 03 — Security belongs everywhere

Security should not be added at the end of a deployment.

### 04 — Monitoring is not enough

The goal is **observability + actionable insight**.

### 05 — Cloud is not automatically cheaper

Poor architecture can make cloud more expensive than traditional infrastructure.

### 06 — DevOps is a culture as much as a technology

Tools enable DevOps.

People, processes and collaboration make it successful.

---

# 🏆 27 — The Bigger Picture

My DevOps journey connects my existing infrastructure experience with modern cloud engineering:

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

# 📌 28 — My DevOps Principles

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

I'm documenting this journey publicly through:

🔹 Hands-on Azure labs  
🔹 Terraform projects  
🔹 Infrastructure automation  
🔹 CI/CD experiments  
🔹 Cloud architecture  
🔹 Linux & scripting  
🔹 DevSecOps concepts  
🔹 Troubleshooting notes  
🔹 Real-world infrastructure scenarios  

If you're also learning **Cloud, DevOps, Terraform, Azure or Infrastructure Automation**, feel free to explore the repositories and connect.

---

<p align="center">

### 🚀 Build. Automate. Secure. Observe. Improve.

**Infrastructure → Cloud → IaC → Automation → DevOps**

</p>

<p align="center">

⭐ If you find something useful, consider starring the repository.

</p>
