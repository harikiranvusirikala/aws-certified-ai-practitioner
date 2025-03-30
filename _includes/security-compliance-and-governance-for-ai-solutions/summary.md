# Applying Governance and Compliance for AI Systems
## Compliance Standards
- National Institute of Standards and Technology (NIST)
- European Union Agency for Cybersecurity (ENISA)
- International Organization for Standardization (ISO)
- AWS System and Organization Controls (SOC)
- Health Insurance Portability and Accountability Act (HIPAA)
- General Data Protection Regulation (GDPR)
- Payment Card Industry Data Security Standard (PCI DSS)
- Algorithmic Accountability Act - prevent bias, ensure transparency and explainbility

## AWS Services for Governance and Compliance

| Service | Usage |
|:--|:--|
| AWS Config | view of configuration |
| Amazon Inspector | vulnerability management |
| AWS Audit Manager | manage risk and compliance |
| AWS Artifact | AWS security and compliance documents |
| AWS CloudTrail | log of actions |
| AWS Trusted Advisor | cost, performance, security, resillience, operational excellence, and service limits |

## Data Governance Strategies
- Data quality and integrity
- Data protection and privacy
- Data lifecycle management
- Responsible AI
- Governance structures and roles
- Data sharing and collaboration

## Concepts in Data governance
- Data lifecycles
- Data logging
- Data residency - physical location where data is stored and processed.
- Data monitoring
- Data analysis
- Data retention

## Approaches to governance strategies
- Policies
- Review cadence - Implement a regular review process to assess the performance, safety, and responsible AI implications of the generative AI solutions.
- Review strategies
- Transparency standards
- Team training requirements

## Key aspects to consider when monitoring an AI system.
- Performance metrics
  - **Model accuracy**: The proportion of correct predictions made by the model
  - **Precision**: The ratio of true positive predictions to the total number of **positive predictions made by the model**
  - **Recall**: The ratio of true positive predictions to the total number of **actual positive instances in the data**
  - **F1-score**: The harmonic mean of precision and recall, which provides a **balanced measure** of model performance
  - **Latency**: The time taken by the model to make a prediction, which is an important measure of a model's practical performance
- Infrastructure monitoring
- Monitoring for bias and fairness
- Monitoring for compliance and responsible AI

## Generative AI Security Scoping Matrix

| Scope | Info |
|:--|:--|
| Scope 1: Consumer app        | Using public generative AI services |
| Scope 2: Enterprise app        | Using an app or SaaS with generative AI features |
| Scope 3: Pre-trained models | Building your app on a versioned model |
| Scope 4: Fine-tuned models  | Fine-tuning a model on your data |
| Scope 5: Self-trained models | Training a model from scratch on your data |

---

# Securing AI Systems
## Security considerations
- Threat detection
- Vulnerability management
- Infrastructure protection
- Prompt injection
- Data encryption

## AWS Shared Responsibility Model
- Customer - security IN the cloud
- AWS - security OF the cloud

## Foundational AWS security services recommended

| Service | Usage |
|:--|:--|
| AWS Security Hub | incident response |
| AWS KMS | data protection |
| Amazon GuardDuty | threat detection |
| AWS Shield Advanced | network and application protection |

## AWS security services
- Identify sensitive data before training models
  - Amazon Macie
- Manage identities and access to AWS services and resources
  - IAM
- Limit access to your data, models, and outputs
  - AWS IAM Identity Center, IAM Access Analyzer, AWS Verified Access, Amazon Verified Permissions and Amazon SageMaker Role Manager
- Protect data from exfiltration (data theft) and manipulation
  - Network Firewall, Amazon VPC and it's policies, AWS PrivateLink
- Protect AI workloads with intelligent threat detection
  - Amazon GuardDuty, Amazon Inspector and Amazon Detective
- Automate incident response and compliance
  - AWS Security Hub, AWS Config, AWS Audit Manager and AWS Artifact
- Defend your generative AI web applications and data
  - AWS Shield Advanced, AWS Firewall Manager, and AWS WAF and it's AWS WAF Bot Control

## Understanding Data and Model Lineage
- Source citation - source - helps assess the **reliability** and **trustworthiness** of the output
  - Datasets
  - Databases
  - Other sources
- Documenting data origins - place of origin - understanding the **potential biases, limitations, or quality issues** that might be present in the training data
  - Details about the data collection process
  - The methods used to curate and clean the data
  - Any preprocessing or transformations applied to the data

## Tools and techniques
- Data lineage
- Cataloging
- Model cards  

<br>

- **Amazon SageMaker Model Cards**
  - Provide guidance on how a model should be used.
  - Support audit activities with detailed descriptions of model training and performance.
  - Communicate how a model is intended to support business goals.

## Data engineering lifecycle
- Data engineering automation and access control
  - Pipeline automation is an important part of modern data-centric architecture design.
  - You can use **AWS Glue workflows** to create a pipeline.
- Data collection
  - **Amazon Kinesis**, **AWS Database Migration Service (DMS)** and **AWS Glue**
- Data preparation and cleaning
  - one of the most important, yet most time-consuming, stages of the data lifecycle.
  - for large workload that has a variety of data, use **Amazon EMR** or **AWS Glue**
- Data quality checks
  - **AWS Glue DataBrew**, and **AWS Glue Data Quality**
- Data visualization and analysis
  - **Amazon QuickSight** - to create graphs or charts. 
  - **Amazon Neptune** - for graph database operations and visualization.
- Infrastructure as code (IaC) deployment
  - **AWS CloudFormation**
- Monitoring and debugging
  - **Amazon CloudWatch**

## Best Practices for Secure Data Engineering
- Assessing data quality
- Implementing privacy-enhancing technologies
- Data access control
- Data integrity  

<br>

- **AWS Privacy Reference Architecture** - guidelines to assist in deign and implementation of privacy-supporting controls
