# ☁️ Module 2: Compute in the Cloud

> **Course:** AWS Certified Cloud Practitioner (CLF-C02)  
> **Module:** 2 - Compute in the Cloud

---

# 📖 Overview

This module introduces **AWS Compute Services**, with a primary focus on **Amazon Elastic Compute Cloud (Amazon EC2)**. It explains how businesses can launch scalable virtual servers in the cloud, choose appropriate instance types, optimize costs using different pricing models, and improve application availability through load balancing, auto scaling, and messaging services.

---

# 🚀 Amazon EC2 (Elastic Compute Cloud)

Amazon EC2 is a web service that provides secure, resizable virtual servers in the AWS Cloud. It allows users to deploy applications quickly without investing in physical hardware.

Key benefits include:

- On-demand virtual servers
- Flexible computing capacity
- High scalability
- Easy management

---

# 🖥️ EC2 Instance Types

AWS provides multiple EC2 instance families designed for different workloads.

- **General Purpose** – Balanced compute, memory, and networking.
- **Compute Optimized** – High-performance processors for compute-intensive tasks.
- **Memory Optimized** – Designed for memory-intensive applications.
- **Storage Optimized** – Ideal for workloads requiring high-speed local storage.
- **Accelerated Computing** – Uses GPUs or specialized hardware for AI, ML, and graphics workloads.

Selecting the correct instance type helps improve both performance and cost efficiency.

---

# 💰 EC2 Pricing Options

AWS provides multiple pricing models so customers can optimize costs based on their workload requirements.

### 1. On-Demand Instances

Pay only for the compute capacity you use without any long-term commitment.

**Best for:**

- Short-term workloads
- Testing and development
- Applications with unpredictable traffic

---

### 2. Reserved Instances (RI)

Commit to using an EC2 instance for a **1-year or 3-year term** in exchange for significant discounts compared to On-Demand pricing.

**Best for:**

- Steady and predictable workloads
- Long-running applications

---

### 3. Savings Plans

Savings Plans provide flexible pricing by committing to a consistent amount of compute usage (measured in **$/hour**) over a 1-year or 3-year period.

Unlike Reserved Instances, Savings Plans offer greater flexibility across eligible AWS compute services.

**Best for:**

- Consistent compute usage
- Organizations seeking maximum cost savings with flexibility

---

### 4. Spot Instances

Spot Instances allow customers to use unused AWS compute capacity at discounts of up to **90%** compared to On-Demand pricing.

These instances can be interrupted by AWS when capacity is needed.

**Best for:**

- Batch processing
- Big data analysis
- CI/CD pipelines
- Fault-tolerant workloads

---

### 5. Dedicated Hosts

A Dedicated Host is a **physical server dedicated entirely to your organization**.

It provides greater control, supports software licensing requirements, and helps meet compliance regulations.

**Best for:**

- Licensing requirements
- Regulatory compliance
- Workloads requiring dedicated physical servers

---

### 6. Dedicated Instances

Dedicated Instances run on hardware dedicated to a single customer but without giving visibility or control over the underlying physical host.

**Best for:**

- Applications requiring hardware isolation
- Security and compliance needs
---

# ⚖️ Scaling and Availability

To improve reliability and performance, AWS provides several supporting services:

- **Elastic Load Balancing (ELB)** distributes incoming traffic across multiple EC2 instances, improving availability and fault tolerance.
- **Amazon EC2 Auto Scaling** automatically launches or terminates EC2 instances based on application demand, ensuring optimal performance while reducing costs.

---

# 📨 Messaging Services

AWS also offers messaging services that improve communication between applications.

- **Amazon Simple Queue Service (Amazon SQS)** enables reliable message queuing, allowing application components to communicate independently.
- **Amazon Simple Notification Service (Amazon SNS)** delivers notifications through email, SMS, or mobile push notifications to users and applications.

---

# 💡 Key Takeaways

- Amazon EC2 provides scalable virtual servers in the cloud.
- Different EC2 instance types are designed for specific workloads.
- AWS offers On-Demand, Reserved, and Spot pricing options.
- Elastic Load Balancing improves application availability.
- Auto Scaling automatically adjusts compute resources based on demand.
- Amazon SQS and Amazon SNS simplify communication between distributed applications.

---

## 🏷️ Tags

`AWS` `Cloud Practitioner` `Amazon EC2` `Auto Scaling` `Elastic Load Balancer` `Amazon SNS` `Amazon SQS` `Cloud Compute`