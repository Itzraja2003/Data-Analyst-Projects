Customer Churn Prediction & Retention Engine
Project Overview

Customer churn directly affects business revenue and growth.
This project builds an end-to-end churn prediction system using machine learning to identify customers likely to churn and recommends actionable retention strategies.

Business Objective

Predict customer churn probability
Identify key factors contributing to churn
Segment customers based on churn risk
Recommend retention actions
Estimate potential business impact

Approach

Data Loading
     ↓
Data Cleaning & EDA
     ↓
Feature Engineering
     ↓
Machine Learning Models
     ↓
Churn Risk Scoring
     ↓
Retention Recommendation Engine
     ↓
Business Impact Estimation

Dataset

Type: Customer subscription data
Target Variable: Churn (Yes / No)
Features: tenure, contract type, monthly charges, services, payment method

Tech Stack

Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
SMOTE
SHAP
Google Colab

Models Used

Model	Purpose
Logistic Regression	Baseline model
Random Forest	Final churn prediction model

Model Performance

ROC-AUC used for evaluation
Recall prioritized to identify maximum churn-prone customers

Churn Risk Segmentation

High Risk: >70% probability
Medium Risk: 40–70%
Low Risk: <40%

Retention Recommendation Engine

Based on churn risk and customer value:
High risk & high value → Personalized discount
High risk → Engagement campaigns
Medium risk → Loyalty programs
Low risk → No action required

Business Impact

Simulated retention of 20% high-risk customers

Demonstrated potential revenue savings

Provided actionable insights for decision-makers
