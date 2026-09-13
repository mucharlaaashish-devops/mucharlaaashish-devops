# Hi, I'm Aashish Mucharla 👋

### DevOps Engineer | AWS & Azure | Cloud Infrastructure | CI/CD | Docker | Kubernetes

I’m a DevOps Engineer with 3+ years of experience working with cloud infrastructure, application deployments, server management, CI/CD, monitoring, and production application support.

My focus is on building secure, reliable and scalable cloud environments and automating the journey from:

**Code → Build → Container → Deployment → Monitoring**

---

## 🏗️ Featured DevOps Project

### 🔐 Secure AWS Architecture — College Web Application

> **Zero Public Access • Private VPC • Automated CI/CD • Secure AWS Infrastructure**

Designed and implemented a secure AWS architecture for a web application with private application and database infrastructure.

### Architecture

**Users**
→ **Route 53**
→ **ACM / HTTPS**
→ **CloudFront**
→ **Private VPC**
→ **EC2**
→ **RDS MySQL**

Supporting AWS services:

- GitHub Actions
- AWS Systems Manager
- S3
- IAM
- VPC Endpoints
- Security Groups
- Private Subnets
- SSM-based server access

### 🔒 Security & Infrastructure

- EC2 without public IP access
- RDS without public access
- Private VPC architecture
- HTTPS with ACM
- CloudFront with private VPC origin
- AWS Systems Manager for server access
- No SSH port exposed publicly
- Restricted Security Groups
- VPC Endpoints for private AWS service communication
- IAM roles following least-privilege principles
- S3 for deployment/file transfer workflows

### 🔄 CI/CD

**Developer → GitHub → GitHub Actions → EC2 Auto Deployment**

Automated deployment workflow with GitHub Actions and secure server access through AWS Systems Manager.

### 🛡️ Zero Trust Approach

The architecture follows a **Zero Trust / private-access model** where application infrastructure and database resources are not directly exposed to the public internet.

---

## 🎓 VBB — Virtual Business Bridge

### [🌐 Live Application](https://vbb.mic.gov.in/)

A large-scale education and innovation platform supporting schools, teachers and students.

### 📊 Platform Scale

| Metric | Count |
|---|---:|
| 🏫 Total Schools in Database | **68,775** |
| 🏫 Registered Schools | **1,516** |
| 🏫 ATL Schools Registered | **67,259** |
| 👨‍🏫 Registered Teachers | **184,646** |
| 👨 Male Teachers | **106,781** |
| 👩 Female Teachers | **77,825** |
| 🎓 Students Enrolled | **390,486** |
| 👦 Male Students | **176,084** |
| 👧 Female Students | **214,349** |
| 👥 Teams Created | **94,325** |
| 💡 Teams Submitted Ideas | **45,022** |
| 📚 Teachers Completed Course | **8,257** |
| 🎓 Students Completed Course | **132,046** |
| 📖 Students Course In Progress | **24,964** |
| 💡 Students/Users in Other Course Activity | **233,476** |

### My DevOps / Cloud Focus

- AWS infrastructure and application deployment
- EC2 server management
- Application deployment and troubleshooting
- Load balancing and scalable infrastructure
- Monitoring with AWS CloudWatch
- Application availability and performance monitoring
- Server and application log analysis
- CI/CD and deployment workflows
- Supporting high-user-load government/education applications

---

## ☁️ Cloud & DevOps Skills

### AWS

`EC2` `VPC` `S3` `RDS` `ALB` `CloudFront` `Route 53` `IAM` `CloudWatch` `SNS` `SES` `Systems Manager`

### Azure

`Azure DevOps` `Azure Repos` `Azure Pipelines` `Azure Boards` `Azure Artifacts`

### Containers & Kubernetes

`Docker` `Kubernetes` `Minikube` `OpenShift` `Helm`

- Deployments
- Services
- Ingress
- ConfigMaps
- Secrets
- Health Probes
- Resource Requests & Limits
- Scaling
- Service Discovery

### CI/CD

`Jenkins` `GitHub Actions` `Git` `GitHub`

### Infrastructure as Code

`Terraform` `Ansible`

### Monitoring

`AWS CloudWatch` `Prometheus` `Grafana`

### Operating Systems & Scripting

`Linux` `Windows Server` `Bash` `PowerShell`

### Development

`Node.js` `TypeScript` `JavaScript` `Python` `REST APIs`

---

# 🚀 Kubernetes Hands-On Project

## Task Platform — Docker + Kubernetes

A full-stack application created to understand container orchestration and Kubernetes application deployment.

### Architecture

```text
                    Internet
                       │
                       ▼
                ┌──────────────┐
                │    Ingress   │
                └──────┬───────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
        Frontend Service    Backend Service
             │                   │
        ┌────┴────┐        ┌─────┴─────┐
        │         │        │           │
       FE        FE       BE          BE
       Pod       Pod      Pod         Pod
                            │
                     ┌──────┴──────┐
                     ▼             ▼
                 PostgreSQL      Redis
