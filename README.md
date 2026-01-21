## Project Overview

This project focuses on predicting whether a credit card customer is likely to default on their payment using a Logistic Regression model. The goal is to build a reliable binary classification system based on customer demographic details, credit usage, and payment history.

## Dataset

The project uses the **UCI Credit Card Dataset**, which contains information about credit card clients, including:

- Demographic details (age, gender, education, marital status)
- Credit limit information
- Bill amounts and payment amounts
- Historical repayment status

## Methodology

- Data preprocessing and cleaning
- Feature engineering (payment behavior transformation and aggregated bill/payment features)
- Feature scaling using StandardScaler
- Model training using Logistic Regression
- Model evaluation using accuracy, confusion matrix, classification report, and ROC-AUC score

## Model Evaluation

The trained model is evaluated using:

- Accuracy score
- Precision, recall, and F1-score
- Confusion matrix visualization
- ROC curve and AUC score

## Interactive Interface

A simple **Gradio web interface** is included to allow users to input customer details and receive a real-time prediction indicating:

- High risk of default
- Low risk of default

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Gradio

## Use Case

This project can be useful for:

- Financial risk assessment
- Credit scoring systems
- Educational purposes in machine learning and data science
