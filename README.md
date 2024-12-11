![meme1](https://github.com/user-attachments/assets/ad7c814f-feb1-4714-ac4c-0ca75bf8d77c)  

# Comment Toxicity Classifier⛓️
Online discussions are often disrupted by toxic behaviors such as threats, insults, obscenity, and identity-based hate, which can discourage meaningful conversations. To tackle this issue, this project develops a multi-headed model designed to classify various types of toxic comments. Using a Bidirectional LSTM (Long Short-Term Memory) neural network, the model processes and evaluates the toxicity level of each comment. In addition, a simple web interface is created using Gradio, allowing users to input a comment into a textbox, click a button, and receive a textbox saying if the comment is toxic.

# Kaggle Dataset
🔗 [Toxic Comment Classification ](https://www.kaggle.com/datasets/julian3833/jigsaw-toxic-comment-classification-challenge)

The dataset used for this project is sourced from Kaggle. It consists of over 50,000 images, organized into 43 categories. Each category represents a specific traffic sign and contains between 210 to 2,500 images, providing a diverse and comprehensive dataset for training and evaluating the model.
# Requirements
To run the packages locally, make use of these Python packages:
- `gradio`: For the user interface
- `scikit-learn`: For text vectorization
- `keras`: For the machine learning model
- `numpy`: For numerical operations
  
# Approach
- The dataset consists of labeled toxic comments. Preprocessing steps include cleaning the text (removing punctuation, stopwords, and special characters), tokenizing the comments, and performing other text normalization techniques to prepare the data for model training.
- Vectorization: The text data is transformed into numerical vectors. This step converts the raw text into a format that can be input into machine learning models for classification.
- The core of the model is a Bidirectional LSTM (Long Short-Term Memory) network. This architecture allows the model to capture contextual relationships in the text from both directions.
- Once trained, a Gradio interface is developed to allow users to interact with the model, inputting a comment and receiving a toxicity score or classification through a user-friendly web interface.
 
# Performance
- Accuracy : 90.%
- Precision : 92.0%
- Recall : 87.0%
 
# Test Image Results

https://github.com/user-attachments/assets/80795b67-b299-43ef-be5c-654345ce7d7c

# Links 
🔗 [Toxic Comment Classification ](https://www.kaggle.com/datasets/julian3833/jigsaw-toxic-comment-classification-challenge)
