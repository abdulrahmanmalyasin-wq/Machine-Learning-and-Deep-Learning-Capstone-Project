# Sentiment Analysis using Machine Learning and Deep Learning

## Overview

This project focuses on building a Sentiment Analysis system using Natural Language Processing (NLP), Machine Learning, and Deep Learning techniques.

The goal of this project is to classify movie reviews into two categories:
- Positive
- Negative

The project uses text preprocessing, TF-IDF feature extraction, machine learning models, and a neural network model to perform sentiment classification.

---

## Dataset

The project uses the IMDB Movie Reviews dataset.

Each review contains:
- Review text
- Sentiment label (positive / negative)

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## Project Workflow

The project follows these steps:

1. Load the dataset
2. Clean and preprocess text data
3. Remove unnecessary characters and stop words
4. Convert text into numerical features using TF-IDF
5. Split data into training and testing sets
6. Train machine learning models
7. Evaluate model performance
8. Build and train a neural network model
9. Compare results between models

---

## Machine Learning Models

The following models were implemented:

### Logistic Regression
Used as a baseline classification model for sentiment prediction.

### Random Forest
An ensemble learning algorithm that combines multiple decision trees.

### K-Nearest Neighbors (KNN)
Classifies reviews based on similarity between text samples.

---

## Deep Learning Model

A Neural Network model was created using TensorFlow and Keras.

The model contains:
- Dense layers
- ReLU activation functions
- Dropout layers
- Sigmoid output layer

The model was trained to classify reviews into positive and negative sentiments.

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Results

The models were compared based on their performance.

Best performing model:

Logistic Regression

Accuracy:

88.93%

---

## Repository Structure
ml capstone project/
│
├── notebook.ipynb
├── IMDB Dataset.csv
└── README.md
