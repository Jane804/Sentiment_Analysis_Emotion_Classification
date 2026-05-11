# Sentiment Analysis – Emotion Classification

## Project Overview

This project focuses on Emotion Classification using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to classify emotions from text comments using machine learning algorithms.

The project includes:

* Text preprocessing
* Feature extraction using TF-IDF
* Machine learning model training
* Model evaluation and comparison

---

# Dataset

The dataset contains:

* **Comment** → Input text data
* **Emotion** → Target emotion labels

---

# Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Jupyter Notebook

---

# Project Workflow

## 1. Data Loading

The dataset is loaded using Pandas.

## 2. Text Preprocessing

The following preprocessing steps are applied:

* Convert text to lowercase
* Remove punctuation and special characters
* Tokenization
* Remove stopwords

### Importance of Preprocessing

Preprocessing helps:

* Remove unwanted noise
* Improve model accuracy
* Reduce unnecessary words

---

# Feature Extraction

TF-IDF Vectorizer is used to convert text into numerical form.

## TF-IDF Explanation

TF-IDF stands for:

* **TF (Term Frequency)** → Frequency of a word in a document
* **IDF (Inverse Document Frequency)** → Reduces importance of common words

This improves text classification performance.

---

# Machine Learning Models

## 1. Naive Bayes

Naive Bayes is a probabilistic machine learning algorithm widely used in NLP tasks.

### Advantages

* Fast and efficient
* Works well with text data
* Good for large datasets

---

## 2. Support Vector Machine (SVM)

SVM is a supervised learning algorithm used for classification problems.

### Advantages

* High accuracy
* Effective for high-dimensional data
* Performs well in text classification

---

# Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* F1-Score
* Classification Report

---

# Results

The performance of:

* Naive Bayes
* Support Vector Machine (SVM)

is compared using evaluation metrics.

SVM generally performs better for emotion classification tasks.

---

# Conclusion

In this project:

* Text preprocessing was performed
* TF-IDF feature extraction was applied
* Naive Bayes and SVM models were trained
* Model performance was evaluated

This project demonstrates how machine learning techniques can be used for emotion classification in NLP applications.

---

# How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## Install Required Libraries

```bash
pip install pandas numpy nltk scikit-learn
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

# Project Structure

```text
Sentiment-Analysis/
│
├── sentiment_analysis.ipynb
├── nlp_dataset.csv
├── README.md
```

---

# Author

Jane J Reji
