# 📘 Natural Language Processing (NLP) Practicals



---

## 📌 Overview

This repository contains a collection of **Natural Language Processing (NLP) practical implementations** using Python. The experiments cover fundamental NLP concepts including text preprocessing, regular expressions, statistical language models, feature extraction, and machine learning-based text classification.

The practicals are implemented using popular libraries such as:

* **NLTK**
* **Scikit-learn**
* **SpaCy**
* **Pandas**

---

## 🛠️ Technologies Used

* Python 3.x
* NLTK
* Scikit-learn
* SpaCy
* Pandas

---

## 📂 List of Practicals

### 🔹 Q1. Text Preprocessing

* Tokenization
* Lowercasing
* Removal of punctuation
* Stopword removal
* Stemming (Porter Stemmer)
* Lemmatization (WordNet Lemmatizer)

👉 Converts raw text into a clean and usable format for NLP tasks.

---

### 🔹 Q2. Regular Expressions (Regex)

* Extract:

  * Email usernames
  * Dates
  * Phone numbers
  * Hashtags
* Abbreviation expansion

👉 Demonstrates pattern matching and text extraction using regex.

---

### 🔹 Q3. Word Frequency Analysis

* Tokenization
* Stopword removal
* Frequency counting using `Counter`

👉 Identifies the most common words in a given text.

---

### 🔹 Q4. TF-IDF Vectorization

* Converts text documents into numerical vectors
* Uses `TfidfVectorizer`

👉 Important for feature extraction in NLP models.

---

### 🔹 Q5. Statistical Language Model

* Unigram probabilities
* Bigram probabilities
* Add-one (Laplace) smoothing
* Sentence probability calculation

👉 Demonstrates probabilistic modeling of language.

---

### 🔹 Q6. Part-of-Speech (POS) Tagging

* Tokenization
* POS tagging using NLTK
* Extraction of nouns
* Frequency distribution of POS tags

👉 Helps understand grammatical structure of text.

---

### 🔹 Q7. Named Entity Recognition (NER)

* Implemented using SpaCy
* Extract entities such as:

  * Person
  * Organization
  * Location

👉 Useful for information extraction tasks.

---

### 🔹 Q8. Sentiment Analysis (IMDB Dataset)

* Dataset: IMDB Movie Reviews (50K samples)
* Preprocessing using TF-IDF
* Model: Logistic Regression
* Evaluation:

  * Accuracy
  * Classification Report

👉 Classifies reviews as **Positive** or **Negative**.

---

## ▶️ How to Run

1. Install required libraries:

   ```bash
   pip install nltk spacy scikit-learn pandas
   ```

2. Download necessary datasets:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

3. For SpaCy:

   ```bash
   python -m spacy download en_core_web_sm
   ```

4. Run each Python script individually.

---

## 📊 Learning Outcomes

By completing these practicals, you will:

* Understand basic NLP preprocessing techniques
* Learn text representation methods (TF-IDF)
* Apply regex for pattern extraction
* Build simple language models
* Perform POS tagging and NER
* Implement sentiment analysis using ML

---

## 📌 Conclusion

These practicals provide a strong foundation in **Natural Language Processing**, covering both theoretical concepts and hands-on implementation. They serve as a stepping stone for advanced NLP tasks such as deep learning-based models and transformers.

---


