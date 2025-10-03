# Youtube_Comments_Spam_Detection
This project detects spam vs non-spam comments from YouTube datasets using Machine Learning (ML) and Natural Language Processing (NLP) techniques.
It compares models trained on TF-IDF features and Word2Vec embeddings.

## 🚀 Project Overview

Dataset: [UCI YouTube Spam Collection Dataset](https://archive.ics.uci.edu/dataset/380/youtube+spam+collection)  

Goal: Build and compare ML models to detect spam comments.

Techniques Used:

Data Cleaning & Preprocessing (NLTK, regex, stopwords, lemmatization)

Feature Engineering: TF-IDF & Word2Vec

Machine Learning Models: Logistic Regression, Naive Bayes, Random Forest, SVM, XGBoost

Model Comparison with Accuracy & Classification Reports

Visualizations: WordCloud, Countplots, Accuracy Comparison

## 📂 Dataset

The dataset contains comments from 5 popular YouTube videos (Psy, Katy Perry, LMFAO, Eminem, Shakira).

Each comment is labeled as:

1 = Spam

0 = Non-Spam (Ham)

## 🧹 Preprocessing Steps

Convert text to lowercase

Remove stopwords & special characters

Lemmatize words (reduce to base form)

Create two types of features:

TF-IDF features (keyword-based)

Word2Vec embeddings (meaning-based)

## 📊 Exploratory Data Analysis

Class Distribution

Word Count Distribution

WordCloud for Spam vs Non-Spam

### Spam vs Non-Spam Distribution
![Class Distribution](https://github.com/janhavisakoji/Youtube_Comments_Spam_Detection/blob/57ceba81a4317d743fa7a470eb2d6ec4ef59828f/spam_non-spam.png)

## 🤖 Machine Learning Models

We trained and compared the following models:

1. Logistic Regression

2. Naive Bayes

3. Random Forest

4. Support Vector Machine (SVM)

5. XGBoost

## 📈 Results

TF-IDF Models performed better than Word2Vec (spam depends on keywords).

Logistic Regression, SVM, and XGBoost gave the highest accuracy.

### Model Accuracy Comparison
![Accuracy Comparison](https://github.com/janhavisakoji/Youtube_Comments_Spam_Detection/blob/57ceba81a4317d743fa7a470eb2d6ec4ef59828f/Model_Accuracy_Comparison.png)

## 🛠️ Tech Stack

Language: Python

Libraries: scikit-learn, XGBoost, NLTK, Gensim, Matplotlib, Seaborn, WordCloud

Environment: Jupyter Notebook

## 📌 Future Improvements

Try deep learning models (LSTM, BERT).

Deploy as a web app using Flask/Streamlit.

Experiment with cross-lingual datasets (comments in other languages).

## 👩‍💻 Author

Janhavi Sakoji – Data Analyst 

📧 Email: [janhavisakoji@gmail.com](janhavisakoji@gmail.com)

🌐 LinkedIn: [My LinkedIn](https://linkedin.com/in/janhavisakoji)
