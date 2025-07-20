
# 📧 Email Spam Classifier

## 🔍 Overview

The **Email Spam Classifier** is a machine learning project that detects whether a given email message is **Spam** or **Not Spam (Ham)**. The model is trained on labeled email datasets using Natural Language Processing (NLP) and classification algorithms.

---

## 🚀 Features

- Text preprocessing and vectorization using TF-IDF
- Training using Logistic Regression (or other ML models)
- Real-time spam prediction using user input
- Streamlit web interface for easy interaction
- Accuracy and performance evaluation

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - scikit-learn  
  - TfidfVectorizer  
  - Streamlit  
  - matplotlib / seaborn (optional for visualization)

---

## 📂 Project Structure

📁 email-spam-classifier/
├── mail_data.csv # Dataset (labeled spam/ham)
├── spam_classifier.py # Main Python logic
├── app.py # Streamlit web app
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── model.pkl # Saved ML model (optional)
