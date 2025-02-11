# Phase-4-Project-NLP

# Sentiment Analysis of Tweets on Apple Products

## Problem Statement

The goal of this project is to build a Natural Language Processing (NLP) model to analyze the sentiment of tweets about Apple products. The task is to classify the sentiment of tweets into two categories:

- **Positive Sentiment**: Tweets that express a favorable opinion about Apple products.
- **Negative Sentiment**: Tweets that express a negative or critical opinion about Apple products.

## Objectives

1. **Sentiment Classification**: 
   - Build a binary sentiment classifier to distinguish between positive and negative sentiments expressed in tweets.
  
2. **Model Evaluation**:
   - Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
   - Visualize the model's performance with a confusion matrix.

By analyzing sentiment on Twitter about Apple products, this model can help businesses track public perception, manage brand reputation, and better understand consumer feedback.

## Project Structure

This project follows a structured workflow consisting of the following key steps:

1. **Exploratory Data Analysis (EDA), Data Cleaning & Preprocessing**
2. **Text Vectorization**
3. **Model Training & Evaluation (Binary Classification)**
4. **Ensemble Methods for Continuous Improvement**
5. **Model Deployment**
6. **Continuous Model Improvement**

## Steps Overview

### Step 1: EDA, Data Cleaning & Preprocessing
- Import required libraries.
- Load and inspect the dataset.
- Clean the text data by removing URLs, mentions, hashtags, digits, punctuation, and extra spaces.
- Handle missing values and duplicates.
- Filter and map sentiment labels to binary values: Positive = 1, Negative = 0.

### Step 2: Text Vectorization
- Use **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert the cleaned text data into numerical vectors.

### Step 3: Model Training & Evaluation
- Train a Logistic Regression model for binary sentiment classification.
- Evaluate model performance using accuracy, precision, recall, and F1-score.
- Visualize the confusion matrix to assess classification performance.

### Step 4: Ensemble Methods for Continuous Improvement
- Use **Random Forest** and **Gradient Boosting** classifiers to improve performance.
- Compare and evaluate the performance of the ensemble models.

### Step 5: Model Deployment
- Save the trained model and the TF-IDF vectorizer using **joblib**.
- Deploy the model using a **Flask** web application with an API endpoint `/predict` for making real-time predictions.

### Step 6: Continuous Model Improvement
- Monitor model performance over time and retrain with new data to keep the model up-to-date.

## Prerequisites

To run this project, ensure you have the necessary libraries installed as used in the notebook:

