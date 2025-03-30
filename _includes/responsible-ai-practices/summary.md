<br>

- Bias-variance trade-off

## Challenges of Generative AI
- Toxicity (generate inappropriate content)
- Hallucinations (inaccurate responses)
- Intellectual property
- Plagiarism and cheating
- Disruption of the nature of work

## Core Dimensions of Responsible AI (features of responsible AI)
- Fairness
- Explainability
- Privacy and security
- Transparency  
- Veracity and robustness  
- Governance  
- Safety  
- Controllability  

# Developing Responsible AI Systems
## Reviewing Amazon service tools for responsible AI
- Foundation model evaluation
  - **Model evaluation on Amazon Bedrock** - evaluate, compare, and select between FMs  
  - **SageMaker Clarify** - evaluate FMs for metrics like accuracy, robustness, and toxicity  
- Safeguards for generative AI
  - **Amazon Bedrock Guardrails** - implement safeguards  
- Bias detection
  - **Amazon SageMaker Clarify** - identify potential bias in ML models and dataset without extensive coding  
  - **Amazon SageMaker Data Wrangler** - import, prepare, transform, balance data if imbalance  
- Model prediction explanation
  - **SageMaker Clarify** in integrated with **Amazon SageMaker Experiments**  
- Monitoring and human reviews
  - **Amazon SageMaker Model Monitor** - monitors models in production  
  - **Amazon Augmented AI (Amazon A2I)** - workflow for human review on **ML predictions**
- Governance improvement
  - **Amazon SageMaker Role Manager** - define minimum permissions  
  - **Amazon SageMaker Model Cards** - model behavior in production, all in one place
    - Catalog details include information such as the intended use and risk rating of a model, training details and metrics, evaluation results and observations, and additional callouts such as considerations, recommendations, and custom information. 
- Providing transparency
  - **AWS AI Service Cards** - responsible AI documentation for AWS AI services
    - Basic concepts to help customers better understand the service or service features
    - Intended use cases and limitations
    - Responsible AI design considerations
    - Guidance on deployment and performance optimization

## Responsible Practices to Select a Model
- use **Model evaluation on Amazon Bedrock** or **SageMaker Clarify** to evaluate models for accuracy, robustness, toxicity, or nuanced content that requires human judgement.
<br>

- Define application use case narrowly
- Choosing a model based on performance
  - Level of customization – The ability to change a model’s output with new data ranging from prompt-based approaches to full model retraining
  - Model size – The amount of information the model has learned as defined by parameter count
  - Inference options – From self-managed deployment to API calls
  - Licensing agreements – Some agreements can restrict or prohibit commercial use
  - Context windows – The amount of information that can fit in a single prompt
  - Latency – The amount of time it takes for a model to generate an output
- Choosing a model based on sustainability concerns (socially, environmentally, and economically sustainable over the long term.)
  - Responsible agency considerations for selecting a model
    - Value alignment
    - Responsible reasoning skills
    - Appropriate level of autonomy
    - Transparency and accountability
  - Environmental considerations for selecting a model
    - Energy consumption
    - Resources utilization
    - Environmental impact assessment
  - Economic considerations for selecting a model (impact on jobs)

## Responsible Preparation for Datasets
- use **SageMaker Clarify** and **SageMaker Data Wrangler** to help balance your datasets.

<br>

- Balancing datasets
  - Inclusive and diverse data collection
  - Data curation
    - Data preprocessing
    - Data augmentation
    - Regular auditing

---

# Transparent and Explainable Models
## Advantages over black box models
- Increased trust
- Easier to debug and optimize for improvements
- Better understanding of the data and the model's decision-making process

<!-- ## Solutions for transparent and explainable models
- Explainability frameworks
- Transparent documentation
- Monitoring and auditing
- Human oversight and involvement
- Counterfactual explanations
- User interface explanations -->

## AWS tools for transparency
- **AWS AI Service Cards** - Amazon provides transparent documentation on Amazon services that help you build your AI services.
- **Amazon SageMaker Model Cards** - you can catalog and provide documentation on models that you create or develop yourself.
## AWS tools for explainability
- **SageMaker Clarify**
- **SageMaker Autopilot** (how ML models make predictions)

## Model Trade-Offs
- Interpretability trade-offs
- Safety and transparency trade-offs
- Model controllability

<br>

- A model that provides transparency into a system so a human can explain the model’s output based on the weights and features is an example of **interpretability** in a model.
- A model that uses model agnostic methods to explain the behavior of the model in human terms is an example of **explainability** in a model.
- A model that avoids causing harm in its interactions with the world is an example of **safety** in a model.
- A model that you can influence the predictions and behavior by changing aspects of the training data is an example of **controllability** in a model.

## Principles of Human-Centered Design for Explainable AI
- Design for amplified decision-making.
  - Clarity
  - Simplicity
  - Usability
  - Reflexivity
  - Accountability
- Design for unbiased decision-making.
  - Transparency
  - Fairness
  - Training
- Design for human and AI learning.
  - Cognitive apprenticeship
  - Personalization
  - User-centered design

- Reinforcement learning from human feedback (RLHF)
  - **Amazon SageMaker Ground Truth** - humans involved for making high value data sets, incorporating human feedback across the ML lifecycle
