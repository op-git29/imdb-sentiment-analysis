# IMDb Movie Review Sentiment Analysis 🎬

## Overview

This project builds a machine learning based sentiment classification system for IMDb movie reviews.

The objective is to classify a movie review as **Positive** or **Negative** using Natural Language Processing (NLP) and supervised machine learning techniques.

The project compares three different classification models:

- Logistic Regression
- Random Forest
- Linear Support Vector Machine (SVM)

TF-IDF is used to convert textual reviews into numerical features, and multiple evaluation metrics are used to compare model performance.

---

## Dataset

The project uses the IMDb Movie Reviews dataset containing **50,000 movie reviews**.

### Features

| Column | Description |
|--------|-------------|
| `review` | Movie review text |
| `sentiment` | Positive or Negative sentiment |

The dataset contains a balanced distribution of positive and negative reviews.

---

## Project Workflow

```text
IMDb Reviews
      ↓
Data Exploration
      ↓
Data Cleaning
      ↓
Label Encoding
      ↓
Train-Test Split
      ↓
TF-IDF Vectorization
      ↓
 ┌───────────────────────┐
 │ Logistic Regression   │
 │ Random Forest         │
 │ Linear SVM            │
 └───────────────────────┘
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Confusion Matrix
      ↓
Error Analysis
      ↓
Custom Review Prediction
