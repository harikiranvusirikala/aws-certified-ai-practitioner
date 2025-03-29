# Course 7: Responsible AI Practices (Domain 4)

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
**Amazon SageMaker Role Manager** - define minimum permissions  
	- **Amazon SageMaker Model Cards** - model behavior in production, all in one place
		- Catalog details include information such as the intended use and risk rating of a model, training details and metrics, evaluation results and observations, and additional callouts such as considerations, recommendations, and custom information. 
- Providing transparency
	- **AWS AI Service Cards** - responsible AI documentation for AWS AI services
	  - Basic concepts to help customers better understand the service or service features
	  - Intended use cases and limitations
	  - Responsible AI design considerations
	  - Guidance on deployment and performance optimization

# Model Trade-Offs
- Interpretability trade-offs
- Safety and transparency trade-offs
- Model controllability
<br>

- A model that provides transparency into a system so a human can explain the model’s output based on the weights and features is an example of **interpretability** in a model.
- A model that uses model agnostic methods to explain the behavior of the model in human terms is an example of **explainability** in a model.
- A model that avoids causing harm in its interactions with the world is an example of **safety** in a model.
- A model that you can influence the predictions and behavior by changing aspects of the training data is an example of **controllability** in a model.

# Principles of Human-Centered Design for Explainable AI
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
