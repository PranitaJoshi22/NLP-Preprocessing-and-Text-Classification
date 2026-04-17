# NLP Preprocessing and Text Classification

## 📌 Objective

The main objective of this project is to perform Natural Language Processing (NLP) preprocessing techniques and build a text classification model using machine learning algorithms.

---

## 🎯 Learning Outcomes

* Understand and apply NLP preprocessing techniques
* Perform tokenization, stopword removal, stemming, and lemmatization
* Convert text data into numerical form using vectorization methods
* Build and evaluate machine learning models for text classification

---

## 🧠 Technologies Used

* Python
* NLTK (Natural Language Toolkit)
* Scikit-learn
* Pandas & NumPy

---

## ⚙️ Implementation Steps

### 1. Data Collection

A small sample dataset of text sentences with labels (positive/negative) is used. The dataset can be replaced with any real-world dataset.

---

### 2. Text Preprocessing

The following preprocessing steps are applied:

* **Lowercasing**: Convert all text to lowercase
* **Removing Special Characters**: Clean unwanted symbols
* **Tokenization**: Split text into individual words
* **Stopword Removal**: Remove common words like *the, is, and*
* **Stemming**: Reduce words to root form (e.g., *running → run*)
* **Lemmatization**: Convert words to meaningful base form

---

### 3. Feature Extraction (Vectorization)

Two techniques are used to convert text into numerical form:

* **CountVectorizer**: Counts frequency of words
* **TF-IDF Vectorizer**: Assigns importance to words based on frequency across documents

---

### 4. Model Building

Two machine learning models are implemented:

* **Naive Bayes Classifier**
* **Logistic Regression**

---

### 5. Model Evaluation

The performance of the models is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score

---

## 📊 Results and Analysis

* Naive Bayes performed well due to its efficiency in handling text data
* Logistic Regression showed competitive performance by learning feature importance
* TF-IDF gave better results compared to CountVectorizer as it reduces the effect of common words

---

## ⚖️ Comparison of Models

| Model               | Strengths                          | Limitations                  |
| ------------------- | ---------------------------------- | ---------------------------- |
| Naive Bayes         | Fast, good for text classification | Assumes feature independence |
| Logistic Regression | Better weight learning             | Slightly slower              |

---

## 🚀 Conclusion

This project helped in understanding how raw text data can be processed and converted into a format suitable for machine learning models. By applying preprocessing techniques and vectorization methods, meaningful patterns were extracted from text data. The comparison of models highlighted how different algorithms perform on the same dataset and the importance of choosing the right approach for better accuracy.

---

## 📌 Future Improvements

* Use larger real-world datasets
* Apply advanced models like Deep Learning (LSTM, BERT)
* Perform hyperparameter tuning for better accuracy

---
