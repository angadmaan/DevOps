# ☁️ Module 3: Exploring Compute Services

> **Course:** AWS Certified Cloud Practitioner (CLF-C02)  
> **Module:** 3 - Exploring Compute Services

---

# 📖 Overview

This module expands on AWS compute services by introducing modern application deployment options beyond Amazon EC2. It covers **containers, container orchestration, serverless computing, application deployment platforms, batch processing, simplified cloud hosting, and hybrid cloud solutions**. These services help developers build scalable, efficient, and highly available applications while reducing infrastructure management.

---

# 🐳 Containers

A **container** is a lightweight software package that includes an application along with all its dependencies, libraries, and configuration files.

Containers solve the common problem of applications behaving differently across development, testing, and production environments.

### Benefits

- Consistent application deployment
- Faster startup time
- Lightweight compared to virtual machines
- Easy portability across environments

---

# 📦 Amazon Elastic Container Registry (Amazon ECR)

Amazon ECR is a **fully managed container image registry** that securely stores, manages, and deploys Docker container images.

### Key Features

- Secure image storage
- Integration with Amazon ECS and Amazon EKS
- Private repositories
- Scalable image management

---

# 🚀 Amazon Elastic Container Service (Amazon ECS)

Amazon ECS is a **fully managed container orchestration service** that simplifies running, managing, and scaling containerized applications on AWS.

### Best For

- Docker-based applications
- Simplified container management
- AWS-native container deployments

---

# ☸️ Amazon Elastic Kubernetes Service (Amazon EKS)

Amazon EKS is a **fully managed Kubernetes service** that allows organizations to run Kubernetes clusters without managing the control plane.

### Benefits

- Native Kubernetes support
- High availability
- Automatic cluster management
- Integration with AWS networking, storage, and security services

---

# ⚡ AWS Fargate

AWS Fargate is a **serverless compute engine for containers**.

Instead of managing EC2 instances, developers simply define their containers, and Fargate automatically provisions the required infrastructure.

### Benefits

- No server management
- Automatic scaling
- Pay only for resources used
- Works with Amazon ECS and Amazon EKS

---

# 🌱 AWS Elastic Beanstalk

Elastic Beanstalk is a **Platform as a Service (PaaS)** that allows developers to deploy web applications without managing the underlying infrastructure.

AWS automatically handles:

- Capacity provisioning
- Load balancing
- Auto Scaling
- Application health monitoring

---

# 🔄 AWS Batch

AWS Batch is a fully managed service designed for running **large-scale batch computing jobs**.

It automatically provisions compute resources and optimizes job scheduling based on workload requirements.

### Common Use Cases

- Data analysis
- Scientific computing
- Image rendering
- Financial modeling

---

# 💡 Amazon Lightsail

Amazon Lightsail is a simplified cloud platform that provides:

- Virtual Private Servers (VPS)
- Containers
- Databases
- Networking

with **predictable monthly pricing**, making it ideal for beginners, personal projects, and small business applications.

---

# 🏢 AWS Outposts

AWS Outposts extends AWS infrastructure and services to **on-premises environments**.

It allows organizations to run AWS services locally while maintaining a consistent hybrid cloud experience.

### Best For

- Low-latency applications
- Data residency requirements
- Hybrid cloud deployments

---

# 📊 Choosing the Right Compute Service

| Service | Primary Use Case |
|----------|------------------|
| Amazon EC2 | Full control over virtual servers |
| Amazon ECS | Manage Docker containers |
| Amazon EKS | Run Kubernetes workloads |
| AWS Fargate | Serverless containers |
| Elastic Beanstalk | Easy web application deployment |
| AWS Batch | Batch processing jobs |
| Amazon Lightsail | Simple websites and applications |
| AWS Outposts | Hybrid cloud infrastructure |

---

# 💡 Key Takeaways

- Containers provide portable and consistent application deployment.
- Amazon ECR securely stores container images.
- Amazon ECS simplifies Docker container management.
- Amazon EKS enables managed Kubernetes clusters.
- AWS Fargate removes the need to manage servers for containers.
- Elastic Beanstalk automates application deployment and infrastructure management.
- AWS Batch efficiently runs large-scale batch workloads.
- Amazon Lightsail offers simplified cloud hosting with predictable pricing.
- AWS Outposts extends AWS services to on-premises data centers for hybrid cloud environments.

---

## 🏷️ Tags

`AWS` `Cloud Practitioner` `Containers` `Amazon ECS` `Amazon EKS` `AWS Fargate` `Elastic Beanstalk` `AWS Batch` `Lightsail` `AWS Outposts`