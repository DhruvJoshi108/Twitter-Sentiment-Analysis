# Twitter Sentiment Analysis

This project performs binary sentiment classification on Twitter data, identifying whether a tweet expresses a positive or negative sentiment.

The model is built using TF-IDF features and Logistic Regression, a strong classical baseline for text classification.

---

## Problem Statement
Given a tweet, classify it as:
- Positive
- Negative

---

## Dataset
- Twitter Sentiment140 Dataset
- Source: Kaggle
- Labels:
  - 0 = Negative
  - 4 = Positive

The dataset contains noisy, real-world social media text including slang, abbreviations, and informal language.

---

## Approach
1. Clean and normalize tweet text
2. Convert text into TF-IDF features
3. Train a Logistic Regression classifier
4. Evaluate using standard classification metrics

---

## Tech Stack
- Python
- pandas
- scikit-learn
- Regular Expressions

---

## Model Pipeline
- Text preprocessing
- TF-IDF vectorization
- Supervised learning
- Model evaluation

---

## Results
- Accuracy typically ranges between 78% and 82%
- Performance reflects the challenges of informal and noisy text
