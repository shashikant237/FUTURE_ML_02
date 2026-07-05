# 🎫 Support Ticket Classification & Prioritization using NLP

> **Future Interns - Machine Learning Internship (Task 2)**

A Natural Language Processing (NLP) project that automatically classifies customer support tickets into categories and predicts their priority level using Machine Learning. This system helps support teams reduce manual effort, prioritize urgent issues, and improve response times.

---

## 📌 Project Overview

Customer support teams receive thousands of tickets every day. Manually categorizing and prioritizing these tickets is time-consuming and can delay responses.

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to:

- 📂 Classify support tickets into categories
- 🚨 Predict ticket priority (High, Medium, Low)
- 🤖 Automate the ticket triaging process
- 📊 Improve operational efficiency

---

## 🎯 Objectives

- Clean and preprocess customer support ticket text
- Convert text into numerical features using **TF-IDF**
- Train Machine Learning models for classification
- Predict:
  - Ticket Category
  - Ticket Priority
- Evaluate model performance using multiple metrics

---

## 📂 Dataset

**Dataset:** Customer Support Tickets Dataset

The dataset contains:

- Ticket Description
- Ticket Type
- Ticket Priority
- Ticket Subject
- Ticket Status
- Customer Information
- Resolution Details

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Joblib
- Google Colab

---

## 🧠 NLP Techniques

- Text Cleaning
- Lowercase Conversion
- Stopword Removal
- Punctuation Removal
- Number Removal
- Lemmatization
- TF-IDF Vectorization

---

## 🤖 Machine Learning Models

### Ticket Category Classification
- Multinomial Naive Bayes
- Logistic Regression

### Ticket Priority Prediction
- Multinomial Naive Bayes
- Logistic Regression

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 🚀 Features

- Automatic Support Ticket Classification
- Priority Prediction
- Interactive Ticket Prediction
- TF-IDF Feature Extraction
- Confusion Matrix Visualization
- Classification Reports
- Business Insights

---

## 💻 Example Prediction

### Input

```text
My payment failed and the amount was deducted from my bank account.
```

### Output

```text
Predicted Category : Billing

Predicted Priority : High
```

---

## 📈 Project Workflow

```
Support Ticket
        │
        ▼
Text Cleaning
        │
        ▼
Stopword Removal
        │
        ▼
Lemmatization
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Machine Learning Models
        │
        ▼
Category Prediction
        │
        ▼
Priority Prediction
```

---

## 📁 Repository Structure

```
FUTURE_ML_02
│
├── FUTURE_ML_02_Support_Ticket_Classification.ipynb
├── customer_support_tickets.csv
├── README.md
├── requirements.txt
```

---

## 💼 Business Impact

This solution can help organizations:

- Reduce manual ticket sorting
- Prioritize urgent customer issues
- Improve response times
- Increase support team productivity
- Enhance customer satisfaction

---

## 🔮 Future Improvements

- Deploy using Streamlit or Flask
- Integrate with helpdesk platforms
- Support multiple languages
- Use transformer models (BERT/RoBERTa)
- Real-time ticket prediction API

---

## 👨‍💻 Author

**Shashikant Jha**

B.Tech CSE (AI & ML)

Machine Learning Intern – Future Interns

GitHub: https://github.com/shashikant237

---

