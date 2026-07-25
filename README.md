# 🎬 IMDB Movie Review Sentiment Analysis using NLP

A Natural Language Processing (NLP) project that classifies IMDB movie reviews as **Positive** or **Negative** using different text vectorization techniques and Machine Learning models.

---

## 📌 Project Overview

Sentiment Analysis is one of the most common applications of Natural Language Processing (NLP). In this project, movie reviews from the IMDB dataset are cleaned, preprocessed, converted into numerical vectors, and classified using Machine Learning algorithms.

The project demonstrates the complete NLP pipeline—from raw text to prediction.

---

## 🚀 Features

- Text preprocessing
- HTML tag removal
- Lowercase conversion
- Stopword removal
- Bag of Words (BoW)
- N-Gram feature extraction
- TF-IDF Vectorization
- Word2Vec implementation
- Machine Learning model training
- Model evaluation using Accuracy

---

## 📂 Dataset

**Dataset:** IMDB Movie Reviews

- 10,000 reviews used for training (sampled from the original dataset)
- Binary Classification
  - Positive
  - Negative

Dataset columns:

| Column | Description |
|---------|-------------|
| review | Movie review text |
| sentiment | Positive / Negative |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Gensim
- Jupyter Notebook

---

## 📚 NLP Pipeline

### 1. Data Loading

- Load IMDB dataset
- Remove duplicate reviews
- Handle missing values

---

### 2. Text Preprocessing

The following preprocessing steps are performed:

- Remove HTML tags
- Convert text to lowercase
- Remove stopwords
- Tokenization

---

### 3. Feature Extraction

Different text representation techniques are explored:

### ✅ Bag of Words (BoW)

Converts text into word frequency vectors.

---

### ✅ Bag of Words with N-Grams

Captures word combinations such as:

```
not good
very nice
highly recommended
```

---

### ✅ TF-IDF

Assigns higher importance to informative words while reducing the influence of commonly occurring words.

---

### ✅ Word2Vec

Uses dense word embeddings to capture semantic relationships between words.

---

## 🤖 Machine Learning Models

The project experiments with:

- Random Forest Classifier
- Gaussian Naive Bayes (for Word2Vec features)

---

## 📊 Evaluation

Performance is measured using:

- Accuracy Score

Future improvements can include:

- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

---

## 📁 Project Structure

```
├── IMDB Dataset.csv
├── text-classification.ipynb
├── word2vec.ipynb
├── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/op-git29/imdb-sentiment-analysis.git
```

---

### 2. Install dependencies

```bash
pip install numpy pandas scikit-learn nltk gensim
```

---

### 3. Download NLTK stopwords

```python
import nltk
nltk.download("stopwords")
```

---

### 4. Run the notebooks

Open:

```
text-classification.ipynb
```

and

```
word2vec.ipynb
```

using Jupyter Notebook.

---

## 📈 Future Improvements

- Lemmatization
- Stemming comparison
- Hyperparameter tuning
- Logistic Regression
- Support Vector Machine (SVM)
- XGBoost
- Deep Learning (LSTM/GRU)
- Transformer-based models (BERT)

---

## 📖 Learning Outcomes

This project helped in understanding:

- Text preprocessing
- Feature engineering for NLP
- Bag of Words
- TF-IDF
- Word Embeddings (Word2Vec)
- Machine Learning for text classification
- Building an end-to-end NLP pipeline

---

## 👨‍💻 Author

**Om Prakash**

B.Tech, Metallurgical & Materials Engineering  
National Institute of Technology Tiruchirappalli (NIT Trichy)

---

## ⭐ If you found this project useful, consider giving it a star!
