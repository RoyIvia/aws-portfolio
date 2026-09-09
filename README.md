# AWS Cloud Architecture Portfolio

> **Designing secure, scalable, resilient, and intelligent cloud solutions on AWS.**

This repository is a portfolio of AWS solutions designed from a **Cloud Solutions Architect perspective**, demonstrating how business and technical requirements translate into production-ready cloud architectures.

## About Me

I am **Roy Ivia**, a Cloud Solutions Architect with experience designing AWS environments, supporting cloud migrations, conducting architecture reviews, and translating business requirements into cloud solutions.

My current work and technical development are centered around 
three complementary areas:

```text


                   Cloud Architecture
                          │
            ┌─────────────┴─────────────┐
            │                           │
            ▼                           ▼
     Cloud Security            GenAI & Agentic AI
            │                           │
            └─────────────┬─────────────┘
                          │
                          ▼
             Secure Intelligent Systems
```

I approach cloud projects from an architecture-first perspective: understanding the business problem, identifying technical and non-functional requirements, evaluating design alternatives, and selecting AWS services based on security, reliability, performance, scalability, operational complexity, and cost.

This portfolio documents that approach through practical AWS implementations and architecture case studies.

# Certifications

My AWS certification path supports a broader objective of developing depth across architecture, operations, security, data, machine learning, and artificial intelligence.

Current AWS certifications include:

* **AWS Certified Solutions Architect – Associate**
* **AWS Certified CloudOps Engineer – Associate**
* **AWS Certified AI Practitioner**
* **AWS Certified Cloud Practitioner**

Certification knowledge is applied through the projects in this repository, with emphasis on architecture and implementation.



# Architecture Focus

**Cloud Architecture**

My core focus is designing AWS environments capable of supporting production workloads and organizational requirements.

Areas covered across this portfolio include:

* **System Design**
* Multi-tier and serverless architectures
* Amazon VPC and hybrid connectivity
* Multi-account architecture
* Identity and access management
* High availability and disaster recovery
* Auto Scaling and load balancing
* Container architectures
* Storage and data architectures
* Cloud migration and backup
* Observability
* Infrastructure automation
* Cost optimization

Designs are evaluated against the **AWS Well-Architected Framework**, using its six pillars :

| Pillar                     | Architectural Focus                                           |
| -------------------------- | ------------------------------------------------------------- |
| **Operational Excellence** | Operating, monitoring, and continuously improving workloads   |
| **Security**               | Protecting systems, data, identities, and access              |
| **Reliability**            | Recovering from failures and meeting workload requirements    |
| **Performance Efficiency** | Using resources efficiently as demand and technology change   |
| **Cost Optimization**      | Delivering business value while controlling unnecessary spend |
| **Sustainability**         | Minimising the environmental impact of cloud workloads        |

---

## Cloud Security

Security is treated as an architectural requirement rather than a layer added after deployment.

```text
Identity
   ↓
Network
   ↓
Compute
   ↓
Application
   ↓
Data
   ↓
Monitoring
   ↓
Governance
```

Key areas include:

* AWS IAM and least privilege
* Workload identities and IAM policy design
* Network segmentation and private subnets
* Security groups and VPC endpoints
* AWS PrivateLink
* Encryption at rest and in transit
* AWS KMS and secrets management
* Amazon S3 security
* AWS CloudTrail and AWS Config
* Amazon GuardDuty and Inspector
* AWS Security Hub
* AWS WAF and Shield
* Security monitoring and incident visibility

---

## Generative AI & Agentic AI

Generative AI architecture extends beyond invoking a foundation model.

My work focuses on:

* Amazon Bedrock
* Foundation models
* Retrieval-Augmented Generation (RAG)
* Embeddings and vector search
* Knowledge retrieval
* Prompt Engineering
* AI agents and tool use
* AWS Lambda integrations
* Amazon OpenSearch
* Amazon S3 vector architectures
* Model access controls and guardrails
* AI application security
* Observability
* Responsible AI
* Cost and performance optimization

# Architecture Methodology

Projects follow a structured architecture lifecycle:

```text
Business Problem
      │
      ▼
Business Requirements
      │
      ▼
Technical & Non-Functional Requirements
      │
      ▼
Architecture Design
      │
      ▼
Architecture Decisions
      │
      ▼
Security Design
      │
      ▼
Implementation
      │
      ▼
Validation & Testing
      │
      ▼
Observability
      │
      ▼
Cost Optimization
      │
      ▼
Documentation
```

---

# Security by Design

Projects apply defence in depth across identity, networking, workloads, data, encryption, monitoring, and governance.

```text
                 AWS Account
                     │
              Identity Boundary
                     │
                    IAM
                     │
               Network Boundary
                     │
                    VPC
                     │
              Workload Security
                     │
         ┌───────────┼───────────┐
         │           │           │
      Compute       Data      Application
         │           │           │
         └───────────┼───────────┘
                     │
             Encryption & KMS
                     │
             Logging & Auditing
                     │
          Detection & Monitoring
```

---

# Repository Structure

This repository acts as the top-level portfolio. Individual projects remain independent Git repositories and are referenced through Git submodules.

```text
aws-portfolio/
│
├── README.md
│
├── aws-customer-churn-mlops/
│   └── Independent project repository
│
└── <additional-aws-projects>/
    └── Independent project repositories
```

This preserves independent commit histories, documentation, architecture decisions, implementation, and project lifecycles while providing a single portfolio entry point.

Clone with submodules:

```bash
git clone --recurse-submodules <repository-url>
```

For an existing clone:

```bash
git submodule update --init --recursive
```

---

## Contact

**Roy Ngondi Ivia**
Cloud Solutions Architect

[royivia104@gmail.com](mailto:royivia104@gmail.com)
Nairobi, Kenya

**Focus:** Cloud Architecture · Cloud Security · Generative AI · Agentic AI

For professional opportunities, architecture discussions, partnerships, and collaboration, please connect with me through the contact channels on my GitHub profile.

---

> **Note:** Projects in this repository are portfolio implementations and architecture case studies. Production architectures should always be adapted to the organization's workload requirements, security policies, compliance obligations, scale, risk profile, and cost constraints.

