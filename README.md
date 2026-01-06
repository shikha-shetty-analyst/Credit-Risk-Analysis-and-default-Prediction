💳 Credit Card Fraud Detection

End-to-End Machine Learning Project | Imbalanced Classification

📌 Project Overview

This project focuses on building a robust fraud detection system using machine learning techniques to identify fraudulent credit card transactions.
Given the extreme class imbalance inherent in real-world fraud datasets, the project emphasizes model selection, evaluation metrics, and risk-aware decision making rather than raw accuracy.

The solution is implemented end-to-end, from data understanding and preprocessing to model training and performance evaluation.

🧠 Business Problem

Credit card fraud leads to:

Significant financial losses

Erosion of customer trust

Increased operational costs for banks and payment processors

The objective is to accurately detect fraudulent transactions while minimizing false positives that may block legitimate customers.

📊 Dataset Description

Source: Kaggle – European Cardholders Dataset

Total Transactions: 284,807

Fraudulent Transactions: ~0.17% (Highly imbalanced)

Features

V1 to V28: PCA-transformed, anonymized features

Time: Seconds elapsed between transactions

Amount: Transaction amount

Class: Target variable

0 → Legitimate

1 → Fraud

🛠️ Tech Stack

Language: Python

Libraries:

NumPy, Pandas – Data manipulation

Matplotlib / Seaborn – Visualization

Scikit-learn – Modeling & evaluation

🔄 Project Workflow

Data Loading & Exploration

Dataset inspection

Class imbalance analysis

Data Preprocessing

Feature scaling

Train-test split with stratification

Model Development

Logistic Regression (baseline, interpretable model)

Random Forest Classifier (non-linear, ensemble-based)

Model Evaluation

Precision, Recall, F1-score

Confusion Matrix

ROC-AUC Score
(Accuracy intentionally not emphasized due to imbalance)

🤖 Models Implemented
1️⃣ Logistic Regression

Serves as a baseline model

High interpretability

Useful for understanding feature influence

Performs reasonably well with proper thresholding

2️⃣ Random Forest Classifier

Captures non-linear relationships

More robust to noise

Better recall for fraud detection

Suitable for real-world deployment scenarios

📈 Evaluation Metrics Used

Given the business risk of fraud detection, the following metrics are prioritized:

Recall (Fraud Class): Minimize missed frauds

Precision: Reduce false alarms

F1-Score: Balance between precision & recall

ROC-AUC: Overall discriminatory power

📌 Key Insights

Fraud detection is not an accuracy-driven problem

Even simple models can perform well with:

Proper evaluation metrics

Correct handling of class imbalance

Ensemble methods improve fraud recall at the cost of interpretability

📁 Repository Structure
├── Credit Card Fraud Detection.ipynb   # Complete analysis & modeling
├── creditcard.csv                      # Dataset
├── README.md                           # Project documentation

🚀 Future Improvements

Apply SMOTE / undersampling techniques

Experiment with XGBoost / LightGBM

Implement cost-sensitive learning

Deploy as a real-time inference API

Add model explainability (SHAP / LIME)

👩‍💻 Author

Shikha Shetty
Aspiring Data Analyst | Machine Learning Enthusiast
