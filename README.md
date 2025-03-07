Bank Customer Churn Prediction

Overview

This project focuses on predicting customer churn in a bank using machine learning techniques. The goal is to identify customers who are likely to leave the bank based on historical data and key customer attributes.

Features

Data Preprocessing:

Handling missing values and encoding categorical variables.

Feature scaling for numerical attributes.

Exploratory Data Analysis (EDA):

Understanding key factors affecting customer churn.

Visualizing distributions and correlations.

Model Training & Evaluation:

Machine Learning Models: Logistic Regression, Decision Trees, Random Forest, XGBoost.

Performance Metrics: Accuracy, Precision, Recall, F1-score, and AUC-ROC.

Dataset

Contains customer details such as age, account balance, credit score, tenure, number of products, and churn status.

Labeled with churn (yes/no) as the target variable.

Installation

Install dependencies before running the project:

pip install pandas numpy scikit-learn matplotlib seaborn xgboost

Usage

Run the script to preprocess data, train models, and evaluate results:

python churn_prediction.py

Results

Identified key factors influencing customer churn.

Compared model performances to find the best predictor.

Future Improvements

Implement deep learning (Neural Networks, LSTMs) for better accuracy.

Enhance feature engineering to improve prediction performance.

License

This project is open-source and available under the MIT License.
