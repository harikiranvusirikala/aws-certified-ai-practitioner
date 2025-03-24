---
title: Amazon Services and Tools for Responsible AI
parent: 7. Responsible AI Practices
nav_order: 4
---

# Amazon Services and Tools for Responsible AI
{: .no_toc }
- Amazon SageMaker is a fully managed ML service.  
- Amazon Bedrock is a fully managed service that makes available high-performing FMs from leading AI startups and Amazon for our use through a unified API.  

Amazon Bedrock also offers a broad set of capabilities to build generative AI applications with security, privacy, and responsible AI.

With the serverless experience of Amazon Bedrock, you can privately customize FMs with your own data and securely integrate and deploy them into your applications by using AWS tools without having to manage any infrastructure.

## Reviewing Amazon service tools for responsible AI
{: .no_toc }

<details open markdown="block">
  <summary>
    Contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

#### Foundation model evaluation  
  - **Model evaluation on Amazon Bedrock** - can evaluate, compare, and select the best foundation model for your use case in just a few clicks.  
  - Amazon Bedrock offers a choice of automatic evaluation and human evaluation.  
    - Automatic evaluation offers predefined metrics such as accuracy, robustness, and toxicity.   
    - Human evaluation offers subjective or custom metrics such as friendliness, style, and alignment to brand voice. For human evaluation, you can use your in-house employees or an AWS-managed team as reviewers.  
  - **SageMaker Clarify** - can automatically evaluate FMs for metrics such as accuracy, robustness, and toxicity to support your responsible AI initiative.  
#### Safeguards for generative AI  
  - **Amazon Bedrock Guardrails** - implement safeguards  
  Guardrails helps control the interaction between users and FMs by filtering undesirable and harmful content, redacting personally identifiable information (PII), and enhancing content safety and privacy in generative AI applications.  
Additionally, you can continuously monitor and analyze user inputs and FM responses that can violate customer-defined policies in the guardrails.  
    - Consistent level of AI safety  
    - Block undesirable topics  
    - Filter harmful content  
    - Redact PII to protect user privacy  
#### Bias detection  
  - **Amazon SageMaker Clarify** - helps identify potential bias in machine learning models and datasets without the need for extensive coding.  
  - **Amazon SageMaker Data Wrangler** - to balance your data in cases of any imbalances.  
 Offers three balancing operators: random undersampling, random oversampling, and Synthetic Minority Oversampling Technique (SMOTE) to rebalance data in your unbalanced datasets.  
#### Model prediction explanation  
  - **SageMaker Clarify** is integrated with **Amazon SageMaker Experiments** to provide scores detailing which features contributed the most to your model prediction on a particular input for tabular, natural language processing (NLP), and computer vision models.  
For tabular datasets, SageMaker Clarify can also output an aggregated feature importance chart that provides insights into the overall prediction process of the model.  
These details can help determine if a particular model input has more influence than expected on overall model behavior.  
#### Monitoring and human reviews  
  - **Amazon SageMaker Model Monitor** - monitors the quality of SageMaker machine learning models in production.  
You can set up continuous monitoring with a real-time endpoint (or a batch transform job that runs regularly), or on-schedule monitoring for asynchronous batch transform jobs.  
You can set alerts that notify you when there are deviations in the model quality.  
  - **Amazon Augmented AI (Amazon A2I)** - helps build the workflows required for human review of ML predictions.  
Brings human review to all developers and removes the undifferentiated heavy lifting associated with building human review systems or managing large numbers of human reviewers.  
#### Governance improvement  
  - **Amazon SageMaker Role Manager** - administrators can define minimum permissions in minutes.   
  - **Amazon SageMaker Model Cards** - to capture, retrieve, and share essential model information, such as intended uses, risk ratings, and training details, from conception to deployment.   
  - **Amazon SageMaker Model Dashboard** - to keep your team informed on model behavior in production, all in one place.  
#### Providing transparency  
  - **AWS AI Service Cards** - help you better understand AWS AI services.  
Form of responsible AI documentation that provides a single place to find information on the intended use cases and limitations, responsible AI design choices, and deployment and performance optimization best practices for AWS AI services.  
They are part of a comprehensive development process to build AWS services in a responsible way that addresses the core dimensions of responsible AI.  
Each AI Service Card contains four sections that cover the following:  
    - Basic concepts to help customers better understand the service or service features  
    - Intended use cases and limitations  
    - Responsible AI design considerations  
    - Guidance on deployment and performance optimization  
