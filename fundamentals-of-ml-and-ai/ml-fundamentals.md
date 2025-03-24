---
title: ML Fundamentals
parent: 1. Fundamentals of ML and AI
nav_order: 1
---

# ML Fundamentals

Building a machine learning model involves:
- data collection and preparation, 
- selecting an appropriate algorithm, 
- training the model on the prepared data, and 
- evaluating its performance through testing and iteration.

## Training data:  
Bad data is often called garbage in, garbage out, and therefore an ML model is only as good as the data used to train it.

- Labeled data - each input instance has a label that represent output for classification  
- Unlabled data

<br>

- Structured data    - data with particular format, mostly like form of tables or databases with rows and columns  
  - Tabular data    - data stored in spreadsheets, databases, or CSV files  
  - Time-series data - data consists of sequences of values measured at successive points in time, such as stock prices, sensor readings, or weather data.  
- Unstructured data  - data that lacks a predefined structure or format, such as text, images, audio, and video  
  - Text data        - documents, articles, social media posts, and other textual data.  
  - Image data       - digital images, photographs, and video frames.  

## Machine learning process:
  - In supervised learning, the algorithms are trained on labeled data. The goal is to learn a mapping function that can predict the output for new, unseen input data.
  - Unsupervised learning refers to algorithms that learn from unlabeled data. The goal is to discover inherent patterns, structures, or relationships within the input data.
  - In reinforcement learning, the machine is given only a performance score as guidance and semi-supervised learning, where only a portion of training data is labeled. Feedback is provided in the form of rewards or penalties for its actions, and the machine learns from this feedback to improve its decision-making over time.

## Inferencing: (process of using the information that a model has learned to make predictions or decisions)
  Syncronous inferencing  
    Client-req -> AI -> immediate response  
  Asyncronous inferencing - longer processing time  
    Client-req -> AI(ack) -> later  
  - Batch inferencing     - analyzes large amount of data all at once, where the speed of the decision-making process is not as crucial as the accuracy of the results.  
    Eg: data analysis  
  - Real-time inferencing - process the incoming data and make a decision almost instantaneously, without taking the time to analyze a large dataset  
    Eg: chatbots or self-driving cars  
