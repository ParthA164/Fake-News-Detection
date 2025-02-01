# Fake News Detection

---

### 1. Methodology
This project implements machine learning techniques for fake news detection using two approaches:
1. **Bag of Words (BoW) Model:**
   - Uses CountVectorizer to transform text data into feature vectors.
   - Applies machine learning classifiers to distinguish fake news from real news.
2. **TF-IDF Model:**
   - Utilizes TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction.
   - Employs various classifiers to improve accuracy and robustness.

---

### 2. Description
The Fake News Detection project is designed to analyze news articles and classify them as "Fake" or "Real" based on textual content. The dataset consists of labeled news articles, where text preprocessing, feature extraction, and classification techniques are applied to achieve accurate predictions.

**Key Features:**
- Data preprocessing (stopwords removal, stemming, tokenization)
- Feature extraction (BoW and TF-IDF)
- Classification using ML models (Logistic Regression, Naïve Bayes, Random Forest, etc.)
- Model evaluation using accuracy, precision, recall, and F1-score

---

### 3. Input / Output
#### **Input:**
- Dataset containing news articles with labels (`fake` or `real`).
- Text-based input for prediction.

#### **Output:**
- Classification result: "Fake" or "Real".
- Model evaluation metrics (confusion matrix, accuracy, precision, recall, F1-score).

---
