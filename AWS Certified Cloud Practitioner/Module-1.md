# ☁️ Module 1: Introduction to Cloud Computing

> **Course:** AWS Cloud Practitioner Essentials (AWS Skill Builder)  
> **Module:** 1 - Introduction to Cloud Computing

---

# 📖 What is Cloud Computing?

According to AWS,

> **Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.**

This definition consists of four important concepts.

---

# 1️⃣ On-Demand Delivery

On-demand delivery means that computing resources can be accessed **whenever they are needed**, without waiting for physical hardware to be installed or configured.

Instead of purchasing servers or storage, users can provision resources within seconds and scale them based on current requirements.

### Benefits

- Instant resource provisioning
- Scale resources up or down as needed
- No hardware procurement
- Faster deployment

### Example

A company launches an Amazon EC2 instance during high website traffic and terminates it once the traffic decreases.

---

# 2️⃣ IT Resources

Cloud providers offer a wide range of IT resources that organizations can use to build, deploy, and manage applications.

These include:

- Compute
- Storage
- Databases
- Networking
- Artificial Intelligence & Machine Learning
- Security Services
- Analytics
- Monitoring Services

Instead of buying and maintaining physical infrastructure, users consume these resources as cloud services.

---

# 3️⃣ Over the Internet

Cloud computing delivers IT resources through the internet.

Users access services remotely using:

- AWS Management Console
- AWS Command Line Interface (CLI)
- Software Development Kits (SDKs)
- APIs

This allows users to manage cloud resources from anywhere with an internet connection.

### Example

A developer can launch an EC2 instance from home, college, or office without physically accessing a data center.

---

# 4️⃣ Pay-As-You-Go Pricing

Cloud computing follows a **usage-based pricing model**.

Instead of paying for infrastructure upfront, customers only pay for the resources they actually consume.

### Benefits

- Lower initial investment
- Cost efficiency
- Financial flexibility
- No long-term hardware commitments

### Example

Rather than purchasing a physical server for a short-term project, an organization can rent computing resources for only the duration of the project.

---

# 🌩️ Cloud Deployment Types

AWS provides different deployment models based on business requirements.

The three primary deployment models are:

- Cloud
- On-Premises
- Hybrid

---

# ☁️ 1. Cloud Deployment

In a cloud deployment model, applications and infrastructure are hosted entirely within the cloud.

Organizations can:

- Migrate existing applications to the cloud
- Build new cloud-native applications
- Combine both approaches

### Example

A company hosts its application using:

- Amazon EC2
- Amazon RDS
- Amazon S3
- Amazon VPC

All resources are managed within AWS.

### Advantages

- High scalability
- Lower infrastructure costs
- Faster deployment
- Reduced maintenance

---

# 🖥️ 2. On-Premises Deployment

In an on-premises deployment model, infrastructure remains inside the organization's own data center.

Although virtualization technologies can improve resource utilization, this model does not provide many of the benefits of cloud computing.

Organizations maintain complete responsibility for:

- Servers
- Storage
- Networking
- Maintenance
- Security

### Advantages

- Dedicated resources
- Greater control
- Low latency for local applications

### Limitations

- High upfront cost
- Limited scalability
- Hardware maintenance
- Longer deployment times

---

# 🔄 3. Hybrid Deployment

Hybrid deployment combines **cloud resources** with **on-premises infrastructure**.

This model is useful when organizations need to keep certain applications on-premises due to regulatory requirements or business preferences while taking advantage of cloud services.

### Example

A company stores sensitive customer information on-premises while using AWS for analytics and application hosting.

### Advantages

- Flexibility
- Easier migration to the cloud
- Supports legacy systems
- Meets compliance requirements

---

# 🌍 Multi-Cloud

AWS notes that **multi-cloud deployments can also be considered hybrid deployments**.

In this approach, organizations use services from multiple cloud providers based on their business requirements.

---

# 📊 Deployment Model Comparison

| Feature | Cloud | On-Premises | Hybrid |
|----------|--------|-------------|---------|
| Infrastructure Location | Cloud Provider | Organization | Both |
| Scalability | High | Limited | Flexible |
| Initial Cost | Low | High | Medium |
| Maintenance | Cloud Provider | Organization | Shared |
| Deployment Speed | Fast | Slow | Moderate |

---

# 💡 Key Takeaways

- Cloud computing is the **on-demand delivery of IT resources over the internet with pay-as-you-go pricing.**
- The four key components of cloud computing are:
  - On-demand delivery
  - IT resources
  - Over the internet
  - Pay-as-you-go pricing
- AWS supports three primary deployment models:
  - Cloud
  - On-Premises
  - Hybrid
- Hybrid deployments help organizations balance cloud innovation with existing infrastructure and compliance requirements.
- According to AWS Skill Builder, **multi-cloud deployments can also be considered hybrid deployments.**

---

# 📚 Summary

Cloud computing enables organizations to access computing resources quickly, securely, and cost-effectively through the internet. Instead of purchasing and maintaining physical infrastructure, users can provision resources on demand and pay only for what they use. Depending on business requirements, organizations can choose between cloud, on-premises, or hybrid deployment models to build and manage their applications efficiently.
