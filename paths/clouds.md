# ☁️ Cloud & Infrastructure

Cloud & Infrastructure is the area of Computer Science concerned with running, deploying, scaling, securing, and maintaining software systems and the infrastructure they depend on.

It brings together:

- Linux
- Networking
- Cloud computing
- Automation
- Containers
- Infrastructure as Code
- CI/CD
- Monitoring
- Reliability
- Security

It is closely connected to Software Engineering, Systems, Networking, Cybersecurity, and Distributed Systems.

---

## 🧭 The Landscape

```text
Cloud & Infrastructure
│
├── Cloud Engineering
│
├── DevOps
│
├── Site Reliability Engineering (SRE)
│
├── Platform Engineering
│
└── Infrastructure / Systems Engineering
```

These roles overlap considerably, and job responsibilities vary between organizations.

---

# ☁️ Cloud Engineering

Cloud Engineers work with cloud infrastructure and services to deploy and operate applications.

### Typical Work

- Provisioning infrastructure
- Managing compute resources
- Configuring storage
- Designing networks
- Managing identities and permissions
- Deploying applications
- Monitoring infrastructure
- Managing availability and scalability
- Automating infrastructure
- Controlling infrastructure costs

### Core Concepts

- Virtual machines
- Containers
- Object storage
- Databases
- Virtual networks
- Load balancers
- DNS
- IAM
- Monitoring
- Autoscaling
- Availability zones
- Regions
- Backup and disaster recovery

---

# 🔄 DevOps

DevOps combines development and operations practices to improve how software is built, tested, released, and operated.

It is not simply a list of tools.

The important ideas include:

- Automation
- Collaboration
- Continuous Integration
- Continuous Delivery / Deployment
- Infrastructure as Code
- Monitoring
- Fast and reliable feedback
- Reproducible environments

### Common Tools

- Git
- GitHub
- GitHub Actions
- Jenkins
- Docker
- Kubernetes
- Terraform
- Ansible
- Prometheus
- Grafana

---

# 🛡️ Site Reliability Engineering

SRE applies software engineering approaches to operating reliable systems.

Important concepts include:

- Reliability
- Availability
- Scalability
- Monitoring
- Alerting
- Incident response
- Service Level Indicators
- Service Level Objectives
- Error budgets
- Automation

SRE connects strongly with:

```text
Software Engineering
        ↓
Distributed Systems
        ↓
Cloud Infrastructure
        ↓
Reliability Engineering
```

---

# 🧩 Platform Engineering

Platform Engineering focuses on building internal platforms and tools that help development teams deploy and operate software more easily.

Examples include:

- Internal developer platforms
- Deployment platforms
- Infrastructure templates
- Self-service environments
- Developer portals
- Automated CI/CD systems

The goal is often to provide reusable infrastructure and workflows rather than requiring every development team to build them independently.

---

# 🧱 Foundations

Before going deep into cloud and DevOps, understand these foundations.

## 1. Linux

Learn:

- Filesystem
- Permissions
- Processes
- Users and groups
- Package management
- Services
- Logs
- SSH
- Shell commands
- Bash scripting

---

## 2. Networking

Understand:

- IP addresses
- IPv4 / IPv6
- Subnets
- CIDR
- Ports
- TCP / UDP
- HTTP / HTTPS
- DNS
- DHCP
- Routing
- Firewalls
- SSH
- TLS

You don't need to become a network engineer, but cloud infrastructure becomes much easier when networking makes sense.

---

## 3. Git

Learn:

- Repository
- Commit
- Branch
- Merge
- Pull request
- Remote
- GitHub workflows

---

## 4. Programming / Scripting

You don't need to become a software developer before entering DevOps.

But you should be comfortable with at least one language and scripting.

Useful choices:

- Python
- Bash
- PowerShell

Python and Bash are particularly useful for automation.

---

# 🐳 Containers

Containers package an application together with the components it needs to run consistently.

### Learn

- Images
- Containers
- Dockerfile
- Volumes
- Networks
- Registries
- Docker Compose

### Practice

Start with:

```text
Application
    ↓
Dockerfile
    ↓
Docker Image
    ↓
Container
    ↓
Docker Registry
```

Don't jump directly to Kubernetes without understanding containers first.

---

# ☸️ Kubernetes

Kubernetes is a platform for managing containerized workloads.

Important concepts include:

- Pods
- Deployments
- Services
- Namespaces
- ConfigMaps
- Secrets
- Ingress
- Volumes
- Stateful workloads
- Health checks
- Scaling

Understand Docker and container fundamentals before going deep into Kubernetes.

---

# ☁️ Cloud Platforms

The major cloud platforms include:

### AWS

Amazon Web Services

Important services to explore:

- EC2
- S3
- IAM
- VPC
- RDS
- Lambda
- CloudWatch
- Elastic Load Balancing

### Microsoft Azure

Explore:

- Virtual Machines
- Storage
- Virtual Networks
- Entra ID
- Azure Functions
- Azure Monitor

### Google Cloud

Explore:

- Compute Engine
- Cloud Storage
- VPC
- Cloud Run
- GKE
- Cloud SQL
- Cloud Monitoring

### Important

You do **not** need to learn AWS, Azure, and Google Cloud simultaneously.

Learn cloud concepts first, then choose one provider and practise with it.

---

# 🏗️ Infrastructure as Code

Infrastructure as Code (IaC) means defining infrastructure using configuration/code so that it can be created and managed consistently.

### Tools

- Terraform
- OpenTofu
- AWS CloudFormation
- Ansible

Learn concepts such as:

- Resources
- Variables
- State
- Modules
- Configuration
- Provisioning
- Idempotency

---

# 🔁 CI/CD

A basic CI/CD workflow looks like:

```text
Developer
    ↓
Git Push
    ↓
CI Pipeline
    ↓
Build
    ↓
Tests
    ↓
Security Checks
    ↓
Package / Container
    ↓
Deploy
    ↓
Monitor
```

Tools include:

- GitHub Actions
- Jenkins
- GitLab CI/CD
- Azure DevOps

Start with **GitHub Actions** if you already use GitHub.

---

# 📊 Monitoring & Observability

Running an application is not enough.

You need to understand what is happening inside it.

### Important Concepts

- Metrics
- Logs
- Traces
- Alerts
- Dashboards
- Health checks
- Incident response

### Common Tools

- Prometheus
- Grafana
- OpenTelemetry
- CloudWatch
- Azure Monitor
- Google Cloud Monitoring

---

# 🔐 Cloud Security

Security should be part of infrastructure from the beginning.

Learn:

- IAM
- Least privilege
- Authentication
- Authorization
- Secrets management
- Encryption
- Network security
- Firewalls
- Security groups
- Vulnerability management
- Logging and auditing

Never put cloud credentials, API keys, passwords, or secrets directly into Git repositories.

---

# 💰 Cost Awareness

Cloud resources can cost money.

Learn:

- Resource usage
- Pricing models
- Budgets
- Cost monitoring
- Autoscaling
- Storage costs
- Data transfer costs
- Resource cleanup

For students, always understand the pricing before creating cloud resources.

---

# 🛣️ Practical Learning Path

```text
Linux
   ↓
Networking
   ↓
Git & GitHub
   ↓
Bash / Python
   ↓
Cloud Fundamentals
   ↓
Choose ONE cloud provider
   ↓
Docker
   ↓
CI/CD
   ↓
Infrastructure as Code
   ↓
Kubernetes
   ↓
Monitoring & Observability
   ↓
Security & Reliability
```

This is a learning sequence, not a requirement that every person must follow every step.

---

# 🧪 Projects

## Beginner

### 1. Linux Server Project

Set up a Linux environment and practise:

- Users
- Permissions
- SSH
- Processes
- Services
- Logs

### 2. Deploy a Website

Build a simple website and deploy it to a cloud platform.

Learn:

```text
Domain
 ↓
DNS
 ↓
Server
 ↓
Web Server
 ↓
Application
```

### 3. Dockerize an Application

Take an existing application and:

- Write a Dockerfile
- Build an image
- Run a container
- Use volumes
- Configure networking

---

## Intermediate

### 4. CI/CD Pipeline

Build:

```text
GitHub
   ↓
GitHub Actions
   ↓
Build
   ↓
Test
   ↓
Docker Image
   ↓
Deployment
```

### 5. Infrastructure as Code

Use Terraform to provision infrastructure.

### 6. Monitoring Dashboard

Deploy an application and monitor it using:

- Prometheus
- Grafana

---

## Advanced

### 7. Kubernetes Application

Deploy a multi-service application to Kubernetes.

### 8. Cloud Architecture

Design a system containing:

- Load balancer
- Application servers
- Database
- Object storage
- Monitoring
- IAM
- Backup

### 9. Production-style Pipeline

Combine:

```text
GitHub
 ↓
CI/CD
 ↓
Docker
 ↓
Registry
 ↓
Kubernetes
 ↓
Cloud
 ↓
Monitoring
```

---

# 📚 Resources

These are intentionally selected resources rather than a huge list.

## 🐧 Linux

### GeeksforGeeks — Linux

Useful for learning Linux commands, concepts, and administration topics.

https://www.geeksforgeeks.org/linux-unix/

### Linux Documentation

Use the official Linux documentation and manual pages as references.

https://www.kernel.org/doc/

### Linux Journey

Interactive learning material for Linux fundamentals.

https://linuxjourney.com/

---

# 🌐 Networking

### GeeksforGeeks — Computer Networks

Useful for learning networking fundamentals such as TCP/IP, DNS, HTTP, routing, and network security.

https://www.geeksforgeeks.org/computer-networks/

### Cloudflare Learning Center

Excellent explanations of concepts such as DNS, HTTP, TLS, CDNs, and networking.

https://www.cloudflare.com/learning/

---

# 🐙 Git & GitHub

### Git Documentation

https://git-scm.com/doc

### GitHub Skills

Hands-on interactive exercises for learning GitHub workflows.

https://skills.github.com/

---

# 🐳 Docker

### Docker Documentation

The official place to learn Docker concepts, commands, containers, images, and Compose.

https://docs.docker.com/

### GeeksforGeeks — Docker

Useful supplementary tutorials and examples.

https://www.geeksforgeeks.org/devops/docker-tutorial/

---

# ☸️ Kubernetes

### Kubernetes Documentation

The official Kubernetes documentation and tutorials.

https://kubernetes.io/docs/

### Kubernetes Basics

Interactive introduction to core Kubernetes concepts.

https://kubernetes.io/docs/tutorials/kubernetes-basics/

### GeeksforGeeks — Kubernetes

Additional tutorials and explanations.

https://www.geeksforgeeks.org/devops/kubernetes-tutorial/

---

# ☁️ AWS

### AWS Skill Builder

Official AWS learning platform containing courses and learning paths.

https://skillbuilder.aws/

### AWS Documentation

Official documentation for AWS services.

https://docs.aws.amazon.com/

### GeeksforGeeks — AWS

Useful supplementary tutorials covering AWS services and concepts.

https://www.geeksforgeeks.org/devops/aws-tutorial/

---

# 🔷 Microsoft Azure

### Microsoft Learn — Azure

Official, structured learning paths and hands-on modules.

https://learn.microsoft.com/training/azure/

### Azure Documentation

Official documentation for Azure services.

https://learn.microsoft.com/azure/

---

# 🌐 Google Cloud

### Google Cloud Skills Boost

Hands-on labs and learning paths for Google Cloud.

https://www.cloudskillsboost.google/

### Google Cloud Documentation

Official documentation for Google Cloud.

https://cloud.google.com/docs

### GeeksforGeeks — Google Cloud

Supplementary tutorials for GCP concepts and services.

https://www.geeksforgeeks.org/devops/google-cloud-platform-tutorial/

---

# 🏗️ Terraform

### Terraform Documentation

Official documentation and tutorials.

https://developer.hashicorp.com/terraform/docs

### Terraform Tutorials

Hands-on tutorials from HashiCorp.

https://developer.hashicorp.com/terraform/tutorials

---

# 🔄 CI/CD

### GitHub Actions Documentation

Official documentation for building automation and CI/CD workflows.

https://docs.github.com/actions

### Jenkins Documentation

Official documentation for Jenkins.

https://www.jenkins.io/doc/

---

# 📊 Observability

### Prometheus Documentation

https://prometheus.io/docs/

### Grafana Documentation

https://grafana.com/docs/

### OpenTelemetry Documentation

https://opentelemetry.io/docs/

---

# 🗺️ Complete Roadmaps

### GeeksforGeeks — DevOps Roadmap

A broad roadmap covering networking, Linux, cloud, Docker, Kubernetes, and other DevOps topics.

https://www.geeksforgeeks.org/devops/devops-roadmap/

### roadmap.sh — DevOps

A visual roadmap for exploring DevOps concepts and technologies.

https://roadmap.sh/devops

---

# 🧪 Hands-on Learning Strategy

Don't learn Cloud & DevOps by memorizing commands.

Use this cycle:

```text
Learn a concept
      ↓
Understand why it exists
      ↓
Use it manually
      ↓
Automate it
      ↓
Break it
      ↓
Debug it
      ↓
Document what you learned
```

For example:

```text
Learn Docker
     ↓
Run a container
     ↓
Build your own image
     ↓
Connect two containers
     ↓
Docker Compose
     ↓
Deploy it
```

That progression gives much more understanding than simply watching tutorials.

---

# 🔗 Connections With Other Fields

```text
Software Engineering
        │
        ↓
      DevOps
        │
   ┌────┼────┐
   ↓    ↓    ↓
Cloud Docker CI/CD
   │    │    │
   └────┼────┘
        ↓
   Kubernetes
        ↓
Infrastructure
        ↓
   Observability
        ↓
       SRE
```

Cloud & Infrastructure also connects strongly with:

- Cybersecurity
- Networking
- Distributed Systems
- Backend Engineering
- Data Engineering
- AI / ML Infrastructure

---

# 🎯 How to Explore This Field

If you're completely new, don't start with Kubernetes.

Start with:

```text
Linux
 ↓
Networking
 ↓
Git
 ↓
Cloud basics
 ↓
Docker
 ↓
CI/CD
```

Then explore:

```text
Cloud Engineering
DevOps
SRE
Platform Engineering
```

Try building and operating real systems before deciding which specialization interests you.

---

## ⚠️ Important

Cloud and DevOps involve real infrastructure and, in some cases, real costs.

Before creating resources:

- Check pricing
- Understand free-tier limits
- Set billing alerts where available
- Delete unused resources
- Never expose credentials
- Never commit secrets to Git

---

**`cd CSE` → understand the infrastructure behind the software, automate it, and learn by running real systems.**