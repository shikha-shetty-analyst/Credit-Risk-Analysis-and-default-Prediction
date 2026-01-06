Credit Card Fraud Detection (Operations & Analytics Project)
Business Problem

In large-scale e-commerce platforms, fraudulent credit card transactions lead to revenue loss, chargebacks, increased operational cost, and poor customer experience.
The objective of this project is to identify fraudulent transactions using data analysis and machine learning, while maintaining a balance between fraud prevention and genuine customer flow.

This problem closely mirrors real-world Flipkart-scale transaction analytics, where fraud cases are extremely rare but highly impactful.

Project Objective

Detect fraudulent credit card transactions effectively

Handle highly imbalanced transaction data

Support operational decision-making using data

Minimize missed fraud cases while controlling false positives

Dataset Overview

Transaction-level dataset with anonymized numerical features

Target column:

0 → Legitimate transaction

1 → Fraudulent transaction

Fraud transactions form less than 1% of the total dataset

Tools & Technologies

Python

Pandas, NumPy – data cleaning and manipulation

Matplotlib, Seaborn – exploratory data analysis

Scikit-learn – model building and evaluation

Approach
1. Data Preprocessing

Checked for missing values and data quality issues

Analyzed class imbalance

Standardized features where required

2. Exploratory Data Analysis

Compared fraud vs non-fraud transaction patterns

Identified behavioral differences useful for risk analysis

Insights applicable for operational dashboards

3. Model Development

Built and evaluated classification models such as:

Logistic Regression

Decision Tree

Random Forest

Models were selected with a focus on business usability, not just accuracy.

4. Evaluation Metrics

Since accuracy is misleading for imbalanced data, the following were used:

Precision

Recall

F1-Score

Confusion Matrix

Recall was prioritized to reduce undetected fraud and revenue leakage.

Key Insights

Fraud detection requires trade-offs between recall and precision

High accuracy alone does not indicate a good fraud model

Missing fraud cases has a higher business cost than flagging some genuine transactions

These trade-offs reflect real operational decisions in e-commerce risk teams

Business & Operational Impact

Helps identify high-risk transactions for review

Can be integrated into payment approval or fraud monitoring workflows

Provides analytical foundation for risk and operations teams

Project Structure
├── Credit Card Fraud Detection.ipynb
├── README.md

Author

Shikha Shetty
Data Analytics | Operations Analytics

Skills: Python, SQL, Excel, Power BI

Experience: Data Labs Intern at Convin.ai

Portfolio: https://shikhashetty.com

Why This Project Matters
