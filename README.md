Week 2 Lab – Customer Churn Prediction

This repository contains my Week 2 Artificial intelligence Lab work, focused on building, evaluating, and comparing different classification models for customer churn prediction.

📌 Project Overview

In this lab, the Telco Customer Churn dataset is used to predict whether a customer is likely to stay with or churn from a telecom service. The notebook covers the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and business-oriented threshold analysis.

🎯 Objectives

- Understand and preprocess a real-world customer churn dataset.
- Convert categorical variables into numerical features using one-hot encoding.
- Handle missing values and prepare the dataset for machine learning.
- Split the data into training and testing sets.
- Establish a baseline model for comparison.
- Train and evaluate multiple classification algorithms.
- Analyze model performance using different evaluation metrics.
- Understand the effect of classification thresholds.
- Analyze the business cost of false positives and false negatives.
- Investigate feature importance and customer churn risk factors.
- Compare different models and draw conclusions from their performance.

🤖 Models Implemented

The following models were trained and evaluated:

- Dummy Classifier – Used as a baseline.
- Logistic Regression – Used for interpretable churn prediction.
- Balanced Logistic Regression – Used to address class imbalance.
- Decision Tree Classifier – Used to study nonlinear decision rules.
- Random Forest Classifier – Used as an ensemble learning approach.

📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

The notebook also compares training and testing performance to understand model generalization and possible overfitting.

🔍 Additional Analysis

The lab goes beyond basic model training by exploring:

Feature Analysis

Logistic Regression coefficients and Random Forest feature importance are examined to identify features associated with customer churn.

Threshold Analysis

Different probability thresholds are tested to observe their effect on precision, recall, and F1-score.

Business Cost Analysis

A cost-based analysis is performed by assigning different costs to:

- Missing a customer who is likely to churn.
- Offering an unnecessary retention incentive to a customer who would stay.

This demonstrates how machine learning predictions can be connected to real-world business decisions.

Feature Engineering

Additional features are created, including:

- Number of subscribed services
- New customer indicator
- Charge per month
- Price difference between monthly and calculated charges

These engineered features are then used to investigate whether they improve prediction performance.

🛠️ Technologies & Libraries

- Python
- Jupyter Notebook / Kaggle Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

📁 Repository Structure

Week-2-Lab/
│
├── ateeq-ur-rehman-week-2-lab.ipynb
└── README.md

📚 Dataset

The project uses the Telco Customer Churn dataset, which contains customer information, subscribed services, account details, charges, and churn status.

💡 Key Learning Outcomes

Through this lab, I practiced the complete machine learning classification workflow, from data preprocessing and feature engineering to model evaluation and business-cost analysis. The lab also helped me understand why accuracy alone is not always sufficient for evaluating a classification model, particularly when the cost of different types of prediction errors is different.

👨‍💻 Author

Ateeq Ur Rehman

 Artificial Intelligence Student


⭐ This repository is part of my Artificial intelligence Lab – Week 2 coursework and documents my practical learning and experimentation with classification models.
