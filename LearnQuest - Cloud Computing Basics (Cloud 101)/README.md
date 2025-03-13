# LearnQuest - Cloud Computing Basics (Cloud 101)

## Module 1: Cloud Computing Fundamentals

### Cloud Computing: A Simple Explanation

**Cloud computing** provides on-demand IT resources (servers, storage, apps) over the internet. Key adoption drivers:

- Cost savings, flexibility, remote access, managed services, scalability, reliability.

### Types of Cloud Computing (Deployment Models)

| Model       | Description                                                                                       | Example                          |
| ----------- | ------------------------------------------------------------------------------------------------- | -------------------------------- |
| **Public**  | Third-party providers deliver services over the public internet.                                  | Microsoft Azure, AWS             |
| **Private** | Dedicated infrastructure for a single organization (on-premises or third-party hosted).           | VMware, OpenStack                |
| **Hybrid**  | Combines public and private clouds for data/application portability and optimized infrastructure. | Azure Hybrid Cloud, AWS Outposts |

### Types of Cloud Services (Service Models)

| Model          | Description                                                                | Examples                    |
| -------------- | -------------------------------------------------------------------------- | --------------------------- |
| **IaaS**       | Rent IT infrastructure (servers, VMs, storage). Customer manages OS/apps.  | AWS EC2, Azure VMs          |
| **PaaS**       | Pre-configured development environments. Provider manages infrastructure.  | Heroku, Google App Engine   |
| **SaaS**       | Subscription-based software hosted by providers (e.g., email, CRM).        | Salesforce, Office 365      |
| **Serverless** | Event-driven code execution. No server management; pay per execution time. | AWS Lambda, Azure Functions |

### Distributed Computing for Performance and Reliability

- **Virtualization**: Virtual hardware mimics physical hardware (managed by hypervisors).
- **Hypervisors**:
  - **Type 1**: Runs directly on hardware (e.g., VMware ESXi).
  - **Type 2**: Runs on an OS (e.g., VirtualBox).
- **Azure Services**: AI, analytics, virtual servers, databases.
- **Distributed Systems**: Components communicate over a network (e.g., blockchain). Key traits:
  - Concurrency, no global clock, independent failures.

---

## Module 2: IaaS, PaaS, SaaS, FaaS

### IaaS (Infrastructure as a Service)

| Aspect         | Details                                                                 |
| -------------- | ----------------------------------------------------------------------- |
| **Use Cases**  | Development/testing environments, application hosting, backup/recovery. |
| **Examples**   | AWS, Azure, Google Cloud.                                               |
| **Advantages** | Scalability, reduced upfront costs, outsourced hardware management.     |

### PaaS (Platform as a Service)

| Aspect           | Details                                                        |
| ---------------- | -------------------------------------------------------------- |
| **Key Features** | Pre-packaged dev environments, DevOps tools, multi-OS support. |
| **Examples**     | AWS Elastic Beanstalk, Azure App Services.                     |
| **Cost Model**   | Pay-as-you-go or subscription.                                 |

### SaaS (Software as a Service)

| Aspect       | Details                                                                      |
| ------------ | ---------------------------------------------------------------------------- |
| **Benefits** | No installation/maintenance, subscription pricing, access to advanced tools. |
| **Examples** | Gmail, Office 365, Salesforce.                                               |

### FaaS (Function as a Service)

| Aspect       | Details                                   |
| ------------ | ----------------------------------------- |
| **Pros**     | No idle costs, dynamic scaling.           |
| **Cons**     | Cold starts (~1-2s lag), no data storage. |
| **Examples** | AWS Lambda, Google Cloud Functions.       |

---

## Module 3: Deployment Models

### Private Deployment Model

| Type              | Description                                                      |
| ----------------- | ---------------------------------------------------------------- |
| **Physical**      | Firm owns/controls the data center.                              |
| **Virtual (VPC)** | Dedicated resources from a third-party provider (e.g., AWS VPC). |

### Public vs Hybrid Cloud

| Model      | Pros                                                  | Cons                                       |
| ---------- | ----------------------------------------------------- | ------------------------------------------ |
| **Public** | Cost-effective, scalable, no hardware management.     | Limited control over data security.        |
| **Hybrid** | Balances security (private) and scalability (public). | Complex setup, higher management overhead. |

### High-Performance Computing (HPC)

- **Components**: Computing, data storage, networking.
- **Cloud Advantage**: Dynamic cluster scaling (e.g., Azure HPC).

### Big Data Cloud

- **Key Tools**: Data warehouses, cloud-based analytics (e.g., Google BigQuery).

---

## Module 4: Hosting Scenarios

### Hosting Models

| Model          | Description                                          | Example Use Case                 |
| -------------- | ---------------------------------------------------- | -------------------------------- |
| **Bare Metal** | Direct hardware access (no virtualization).          | High-performance databases.      |
| **VMs**        | Virtualized environments managed by hypervisors.     | Scalable web apps.               |
| **Containers** | Lightweight, OS-level virtualization (e.g., Docker). | Microservices, DevOps pipelines. |

### On-Premises vs Cloud

| Factor      | On-Premises                 | Cloud                          |
| ----------- | --------------------------- | ------------------------------ |
| **Control** | Full hardware/data control. | Limited to provider offerings. |
| **Cost**    | High upfront CAPEX.         | Pay-as-you-go OPEX.            |

---

## Module 5: Cloud Providers (AWS, Azure, GCP, IBM, Salesforce)

### Top Cloud Providers (2025)

| Provider  | Regions | Key Services                             | Specialization                        |
| --------- | ------- | ---------------------------------------- | ------------------------------------- |
| **AWS**   | 40      | EC2, Lambda, S3, SageMaker.              | Enterprise scalability, global reach. |
| **Azure** | 60+     | Azure VMs, DevOps, Power BI.             | Hybrid cloud, Microsoft integration.  |
| **GCP**   | 40+     | BigQuery, Kubernetes Engine, TensorFlow. | AI/ML, data analytics.                |

### IBM Cloud & Salesforce

| Provider       | Key Offerings                                         |
| -------------- | ----------------------------------------------------- |
| **IBM Cloud**  | Hybrid cloud, legacy system integration, AI (Watson). |
| **Salesforce** | SaaS CRM, Marketing Cloud, Community Cloud.           |

---

## Module 6: Advanced Topics

### Serverless Computing

| Aspect       | Details                                    |
| ------------ | ------------------------------------------ |
| **Pros**     | No server management, pay-per-use.         |
| **Cons**     | Cold starts, limited runtime environments. |
| **Examples** | AWS Lambda, Azure Functions.               |

### Distributed vs Decentralized Apps

| Type              | Description                                                     | Example            |
| ----------------- | --------------------------------------------------------------- | ------------------ |
| **Distributed**   | Runs on multiple nodes but controlled by a central authority.   | CDN networks.      |
| **Decentralized** | No central authority; runs on blockchain/peer-to-peer networks. | Bitcoin, Ethereum. |

### Key Links

- [Centralized vs. Decentralized vs. Distributed Systems](https://modex.tech/centralized-vs-decentralized-vs-distributed-systems/)
- [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/)

## Videos

- [Distributed Applications](https://www.youtube.com/watch?v=OUBzMByzoGQ)
