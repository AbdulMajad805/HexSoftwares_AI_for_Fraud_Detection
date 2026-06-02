# 🛡️ AI Fraud Detection Command Center

An intelligent AI-powered fraud detection system designed to identify suspicious financial transactions in real time using Machine Learning and interactive analytics.

This project combines fraud prediction, financial threat analysis, explainable AI, and a modern fintech-inspired dashboard to simulate a real-world banking security platform.

---

# 🚀 Project Overview

Financial fraud is one of the biggest challenges faced by banks and online payment systems. Traditional rule-based systems often fail to detect complex fraud patterns.

This project uses Machine Learning to analyze transaction behavior and detect potentially fraudulent activities with high accuracy.

The system provides:

- Real-time fraud prediction
- AI-powered risk analysis
- Threat-level classification
- Interactive fraud monitoring dashboard
- Explainable AI insights
- Financial analytics visualization

---

# 🎯 Objectives

- Detect fraudulent transactions using Machine Learning
- Reduce false fraud alerts
- Provide real-time transaction analysis
- Build an enterprise-style AI dashboard
- Simulate a fintech fraud monitoring platform

---

# 🧠 Machine Learning Workflow

## 1. Data Collection
Used the Credit Card Fraud Detection dataset containing anonymized transaction data.

## 2. Data Preprocessing
- Handled imbalanced dataset
- Applied feature scaling
- Used SMOTE for oversampling fraud cases

## 3. Exploratory Data Analysis
Performed:
- Fraud distribution analysis
- Correlation analysis
- Transaction behavior visualization
- Statistical analysis

## 4. Model Training
Implemented multiple models:
- Logistic Regression
- Random Forest
- XGBoost

## 5. Model Evaluation
Compared models using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

---

# 🏆 Best Performing Model

## Random Forest Classifier

### Performance Metrics

| Metric | Score |
|---|---|
| Accuracy | 99.94% |
| Precision | 84.5% |
| Recall | 83.7% |
| F1 Score | 84.1% |

The Random Forest model provided the best balance between fraud detection capability and minimizing false alarms.

---

# 🖥️ Dashboard Features

## 🔍 AI Fraud Analysis
- Real-time transaction prediction
- Fraud probability calculation
- Threat-level classification

## 📡 Live Transaction Feed
- Simulated banking transaction monitoring
- AI-generated fraud alerts
- Real-time risk analysis

## 📈 Fraud Analytics
- Fraud trend visualization
- Threat monitoring charts
- AI feature importance analysis

## 🧠 AI Insights Engine
Provides intelligent explanations such as:
- Abnormal transaction behavior
- High anomaly confidence
- Suspicious spending patterns

## 🛡️ Threat Categories
| Risk Score | Threat Level |
|---|---|
| 0–30 | Safe |
| 31–60 | Moderate |
| 61–80 | High Risk |
| 81–100 | Critical |

---

# 🛠️ Technologies Used

## Programming Language
- Python

## Machine Learning
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Data Analysis
- Pandas
- NumPy

## Visualization
- Plotly
- Matplotlib
- Seaborn

## Web Framework
- Streamlit

## Model Storage
- Joblib

---

# 📂 Project Structure

```bash
AI-Fraud-Detection-System/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── models/
│   └── fraud_model.pkl
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── screenshots/