# AppleTweetSentiment

### 🧠 NLP-Powered Sentiment Analysis on Tweets about Apple Products

This project uses Natural Language Processing (NLP) and machine learning techniques to classify the sentiment of tweets directed at Apple products as **positive** or **negative**. The goal is to help track public opinion, enhance brand monitoring, and understand consumer feedback.

---

## 📌 Problem Statement

The objective is to build a sentiment analysis model that:

* Classifies tweets about Apple products into **positive** or **negative** sentiments.
* Uses real-world Twitter data to analyze brand perception.
* Supports future deployment for real-time sentiment monitoring.

---

## 🎯 Objectives

1. **Binary Sentiment Classification:**  
   Identify whether a tweet shows positive or negative sentiment.

2. **Model Evaluation:**  
   Use performance metrics (accuracy, precision, recall, F1-score) and visualize the confusion matrix.

3. **Ensemble Modeling:**  
   Enhance performance using Random Forest and Gradient Boosting methods.

4. **Deployment Ready:**  
   Save the model and deploy using a Flask API endpoint.

---

## 🧪 Tech Stack

* **Python** (`pandas`, `NumPy`, `scikit-learn`)
* **NLP:** TF-IDF vectorization
* **Models:** Logistic Regression, Random Forest, Gradient Boosting
* **Deployment:** Flask API
* **Model Persistence:** `joblib`

---

## 🔍 Steps Overview

1. **Exploratory Data Analysis (EDA)**  
2. **Text Cleaning & Preprocessing**  
3. **Text Vectorization using TF-IDF**  
4. **Model Training & Evaluation (Logistic Regression)**  
5. **Model Optimization (Ensemble Methods)**  
6. **Model Deployment using Flask API**  
7. **Continuous Improvement through Retraining**

---

## 📊 Results

* **Logistic Regression Accuracy:** ~80%  
* **Random Forest Accuracy:** ~80.1%  
* **Gradient Boosting Accuracy:** ~79.9%

The models successfully distinguish sentiment polarity with strong performance, suitable for basic brand sentiment tracking.

---

## 🚀 Deployment

* Trained model and vectorizer are saved using `joblib`.  
* Flask API exposes a `/predict` endpoint for external use.

**Example input:**
```json
{ "text": "I love my new iPhone!" }
````

**Example output:**

```json
{ "sentiment": "Positive" }
```

---

## 🔄 Future Improvements

* Incorporate neutral or mixed sentiments
* Apply deep learning models like BERT or LSTM
* Integrate real-time Twitter API for live monitoring
* Improve multilingual support

---

## 📁 Dataset

The dataset used includes tweets mentioning various Apple products and their corresponding emotional tone.

**Note:** Dataset preprocessing includes:

* Removal of URLs, mentions, hashtags, punctuation
* Unicode normalization
* Filtering out neutral/no-emotion tweets

---
## 📬 Contact

Have questions or suggestions? Feel free to:

- Open an [issue](https://github.com/Cyrus-DS/Apple_Twitter_Sentiment_NLP_Phase-4/issues)
- Connect with me on [LinkedIn](https://www.linkedin.com/in/cyrus-wambugu-b9476195/)
- Visit my [GitHub profile](https://github.com/Cyrus-DS) for more projects

