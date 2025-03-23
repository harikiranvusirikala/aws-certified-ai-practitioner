---
title: "Responsible AI Challenges in Traditional AI and Generative AI"
parent: "7. Responsible Artificial Intelligence Practices"
grand_parent: "Courses"
nav_order: 2
---

# Responsible AI Challenges in Traditional AI and Generative AI  

## Biases in AI systems  
-  **Accuracy of models**  
    models can make predictions or generate content based only on the data they are trained on. If they are not trained properly, you will get inaccurate results.  
    Therefore, it is important to address bias and variance in your model.  
    - **Bias**  
      Bias in a model means that the model is missing important features of the datasets. This means that the data is too basic. Bias is measured by the difference between the "expected predictions" of the model and the "true values we are trying to predict".  
      If the difference is narrow, then the model has low bias. If the difference is wide, then the model has a high bias.  
      When a model has a high bias, it is "underfitted". Underfitted means that the model is not capturing enough difference in the features of the data, and therefore, the model performs poorly on the training data.  
    - **Variance**  
      Variance refers to the "model's sensitivity to fluctuations or noise in the training data". The problem is that the model might consider noise in the data to be important in the output. When variance is high, the model becomes so familiar with the training data that it can make predictions with high accuracy. This is because it is capturing all the features of the data.  
      However, when you introduce new data to the model, the model's accuracy drops. This is because the new data can have different features that the model is not trained on. This introduces the problem of "overfitting". Overfitting is when model performs well on the training data but does not perform well on the evaluation data. This is because the model is memorizing the data it has seen and is unable to generalize to unseen examples.  
- **Bias-variance trade-off**  
    Bias-variance tradeoff is when you optimize your model with the right balance between bias and variance. This means that you need to optimize your model so that it is not underfitted or overfitted. The goal is to achieve a trained model with the lowest bias and lowest variance tradeoff for a given data set.  
    - Can be overcome by:  
      - Cross validation
      - Increase data
      - Regularization
      - Simpler models
      - Dimension reduction (Principal component analysis)
      - Stop training early  
      (in detail in aws course)  

## Challenges of generative AI
- **Toxicity**  
    Toxicity is the possibility of generating content (whether it be text, images, or other modalities) that is offensive, disturbing, or otherwise inappropriate.  
- **Hallucinations**  
    Hallucinations are assertions or claims that sound plausible but are verifiably incorrect.  
    Example: "Tell me about some papers by" a particular author. The model is not actually searching for legitimate citations but generating ones from the distribution of words associated with that author.  
- **Intellectual property**  
    tendency to occasionally produce text or code passages that were verbatim of parts of their "training data", resulting in privacy and other concerns  
- **Plagiarism and cheating**  
    Being used to write college essays(where content is being graded or evaluated), writing samples for job applications, and other forms of cheating or illicit copying.  
- **Disruption of the nature of work**  
    concern that some professions might be replaced or seriously disrupted by the technology.  