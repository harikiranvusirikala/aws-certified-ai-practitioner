---
title: "7. Responsible Artificial Intelligence Practices"
parent: "Courses"
nav_order: 7
---

# Course: Responsible Artificial Intelligence Practices (Domain 4)

---

Responsible AI refers to "practices" and "principles" that ensure that AI systems are "transparent" and "trustworthy" while "mitigating potential risks and negative outcomes".  
These responsible standards should be considered throughout the entire lifecycle of an AI application. This includes the initial design, development, deployment, monitoring, and evaluation phases.  

To operate AI responsibly, companies should proactively ensure the following about their system:  
  - It is fully transparent and accountable, with monitoring and oversight mechanisms in place.
  - It is managed by a leadership team accountable for responsible AI strategies.
  - It is developed by teams with expertise in responsible AI principles and practices.
  - It is built following responsible AI guidelines.

Responsible AI is not exclusive to any one form of AI. It should be considered when you are building "traditional" or "generative" AI systems.

**Traditional AI**  
  Traditional machine learning models perform tasks based on the data you provide. They can make predictions such as ranking, sentiment analysis, image classification, and more.  
  However, each model can perform only one task. And to successfully do it, the model needs to be carefully trained on the data. As they train, they analyze the data and look for patterns. Then these models make a prediction based on these patterns.  

  Some examples of traditional AI include recommendation engines, gaming, and voice assistance.  

**Generative AI**  
  Generative artificial intelligence (generative AI) runs on "foundation models (FMs)". These models are pre-trained on massive amounts of general domain data that is beyond your own data.  
  They can perform multiple tasks. Based on user input, usually in the form of text called a prompt, the model actually generates content. This content comes from learning patterns and relationships that empower the model to predict the desired outcome.  

  Some examples of generative AI include chatbots, code generation, and text and image generation.  

Generative AI offers business value
  - Creativity: Create new content and ideas, including conversations, stories, images, videos, and music.
  - Productivity: Radically improve productivity across all lines of business, use cases, and industries.
  - Connectivity: Connect and engage with customers and across organizations in new ways.


Responsible AI Challenges in Traditional AI and Generative AI  
Biases in AI systems  
- Accuracy of models  
    models can make predictions or generate content based only on the data they are trained on. If they are not trained properly, you will get inaccurate results.  
    Therefore, it is important to address bias and variance in your model.  
    - Bias  
      Bias in a model means that the model is missing important features of the datasets. This means that the data is too basic. Bias is measured by the difference between the "expected predictions" of the model and the "true values we are trying to predict".  
      If the difference is narrow, then the model has low bias. If the difference is wide, then the model has a high bias.  
      When a model has a high bias, it is "underfitted". Underfitted means that the model is not capturing enough difference in the features of the data, and therefore, the model performs poorly on the training data.  
    - Variance  
      Variance refers to the "model's sensitivity to fluctuations or noise in the training data". The problem is that the model might consider noise in the data to be important in the output. When variance is high, the model becomes so familiar with the training data that it can make predictions with high accuracy. This is because it is capturing all the features of the data.  
      However, when you introduce new data to the model, the model's accuracy drops. This is because the new data can have different features that the model is not trained on. This introduces the problem of "overfitting". Overfitting is when model performs well on the training data but does not perform well on the evaluation data. This is because the model is memorizing the data it has seen and is unable to generalize to unseen examples.  
- Bias-variance trade-off  
    Bias-variance tradeoff is when you optimize your model with the right balance between bias and variance. This means that you need to optimize your model so that it is not underfitted or overfitted. The goal is to achieve a trained model with the lowest bias and lowest variance tradeoff for a given data set.  
    - Can be overcome by:  
      - Cross validation
      - Increase data
      - Regularization
      - Simpler models
      - Dimension reduction (Principal component analysis)
      - Stop training early
      (in detail in course)  

**Challenges of generative AI**
- Toxicity  
 Toxicity is the possibility of generating content (whether it be text, images, or other modalities) that is offensive, disturbing, or otherwise inappropriate.  
- Hallucinations  
 Hallucinations are assertions or claims that sound plausible but are verifiably incorrect.  
 Example: "Tell me about some papers by" a particular author. The model is not actually searching for legitimate citations but generating ones from the distribution of words associated with that author.  
- Intellectual property  
 tendency to occasionally produce text or code passages that were verbatim of parts of their "training data", resulting in privacy and other concerns  
- Plagiarism and cheating  
 Being used to write college essays(where content is being graded or evaluated), writing samples for job applications, and other forms of cheating or illicit copying.  
- Disruption of the nature of work  
 concern that some professions might be replaced or seriously disrupted by the technology.  

**Core Dimensions of Responsible AI**

![Responsible AI core dimensions.png]({{site.baseurl}}/assets/images/getting-started/Responsible%20AI%20core%20dimensions.png)

- Fairness  
 AI systems promote inclusion, prevent discrimination, uphold responsible values and legal norms, and build trust with society.  
 to create systems suitable and beneficial for all.  
- Explainability  
 clearly explain or provide justification for its internal mechanisms and decisions so that it is understandable to humans.  
 Humans must understand how models are making decisions and address any issues of bias, trust, or fairness.
- Privacy and security  
 data that is protected from theft and exposure.  
 at a privacy level, individuals control when and if their data can be used.  
 At the security level, it verifies that no unauthorized systems or unauthorized users will have access to the individual’s data.  

