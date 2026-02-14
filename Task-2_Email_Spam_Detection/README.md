# 📧 Email Spam Detection

## 📌 Project Overview

The Email Spam Detection project is a machine learning project that classifies emails into **Spam** or **Not Spam (Ham)**.  

It helps filter unwanted messages and improve email security. This project uses Natural Language Processing (NLP) techniques to process text data and machine learning models to predict the category of emails.

---

## 🎯 Objective

- Detect spam emails automatically
- Apply text preprocessing techniques
- Convert text into numerical features for ML models
- Train and evaluate classification models
- Gain practical understanding of NLP in Python

---

## 📊 Dataset Information

- Dataset contains labeled emails:
  - `0` → Not Spam (Ham)
  - `1` → Spam
- Includes hundreds or thousands of text messages
- CSV format (`dataset.csv`)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- NLP techniques (Vectorization, Stopword removal)

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Imported dataset using Pandas
- Checked for missing values and data types

### 2️⃣ Data Cleaning
- Converted text to lowercase
- Removed punctuation and special characters
- Removed stopwords (common words)

### 3️⃣ Feature Extraction
- Converted text into numerical data using:
  - CountVectorizer or TF-IDF Vectorizer

### 4️⃣ Train-Test Split
- Split dataset into 80% training, 20% testing

### 5️⃣ Model Training
- Trained models like:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)

### 6️⃣ Model Evaluation
- Measured performance using:
  - Accuracy Score
  - Confusion Matrix
  - Precision, Recall, F1-Score

---

## 📈 Model Performance

- Model achieved high accuracy
- Correctly classified spam and ham emails
- Naive Bayes performed particularly well

---

## 📁 Project Structure


