# 📘 DeepLearning — Applied Deep Learning Projects (TensorFlow)

This repository contains **applied deep learning projects implemented in TensorFlow/Keras**, focusing on **Natural Language Processing (NLP)** and **sequence modeling**. Each project is delivered as a fully executable Jupyter Notebook with clear preprocessing, model design, training, and evaluation workflows.

## 🚀 Projects Overview
### [RNN-based Text Classification for Review Recommendation](https://github.com/Berniac/DeepLearning/blob/main/Projects/rnn_text_classification_review_recommendation_tensorflow.ipynb)
#### 🔍 Problem Statement
Predict whether a product review is recommended or not based on customer-written text and associated metadata.

#### 🧠 Approach
- Combined multiple text features (review title, review body, department, and class)
- Applied text cleaning using **regular expressions**
- Tokenized and vectorized text inputs
- Built and trained a **Recurrent Neural Network (RNN)** using TensorFlow/Keras
- Evaluated model data on unseen data

#### 🛠️ Key Techniques
- NLP preprocessiong (text normalization & feature engineering)
- RNN-based sequence modeling
- Binary Classification
- Model Evaluation and learning curves

### [Sequence-to-Sequence Encoder–Decoder Model](https://github.com/Berniac/DeepLearning/blob/main/Projects/sequence_to_sequence_encoder_decoder_tensorflow.ipynb)
#### 🔍 Problem Statement
Model sequential data using an **Encoder–Decoder architecture**, a foundational approach for tasks such as machine translation, sequence prediction, and time-series forecasting.
#### 🧠 Approach
- Cleaned and prepared sequential input data
- Designed an **Encoder-Decoder (Seq2Seq)** neural network architecture
- Trained the model using TensorFlow/Keras
- Applied early stopping to prevent overfitting
- Evaluated training and validation performance

#### 🛠️ Key Techniques
- Sequence-to-Sequence modeling
- Encoder-Decoder neural architectures
- Time-dependent data processing
- Training optimization with callbacks

