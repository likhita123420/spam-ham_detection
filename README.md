# Spam–Ham Detection using Machine Learning

## 📌 Project Overview
This project focuses on building a **Spam–Ham (SMS) text classification model** using **Machine Learning techniques**.  
The goal is to automatically classify messages as **Spam** or **Ham (Not Spam)** based on their textual content.

This is a classic **Natural Language Processing (NLP)** problem and is widely used in email filtering, SMS filtering, and messaging applications.

---

## 🛠️ Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📂 Dataset
- Dataset contains labeled SMS messages:
  - `spam` → Unwanted promotional or fraudulent messages
  - `ham` → Legitimate messages
- Dataset is preprocessed for NLP tasks such as:
  - Text cleaning
  - Tokenization
  - Stopword removal
  - Vectorization

---

## ⚙️ Project Workflow
1. **Data Loading & Exploration**
2. **Text Preprocessing**
   - Lowercasing
   - Removing punctuation and special characters
   - Stopword removal
   - Tokenization
3. **Feature Extraction**
   - Count Vectorizer / TF-IDF Vectorizer
4. **Model Building**
   - Machine Learning classifier (e.g., Naive Bayes / Logistic Regression)
5. **Model Evaluation**
   - Accuracy
   - Confusion Matrix
   - Classification Report
6. **Prediction on New Messages**

---

## 📊 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help evaluate model performance, especially for **imbalanced datasets**.

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/likhita123420/spam-ham_detection.git
