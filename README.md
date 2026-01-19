Customer Churn Prediction & Retention Engine
1.Project Overview

Customer churn directly affects business revenue and growth.
This project builds an end-to-end churn prediction system using machine learning to identify customers likely to churn and recommends actionable retention strategies.

2.Business Objective

Predict customer churn probability
Identify key factors contributing to churn
Segment customers based on churn risk
Recommend retention actions
Estimate potential business impact

3.Approach

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

4.Dataset

Type: Customer subscription data
Target Variable: Churn (Yes / No)
Features: tenure, contract type, monthly charges, services, payment method

5.Tech Stack

Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
SMOTE
SHAP
Google Colab

6.Models Used

Model Purpose
Logistic Regression	Baseline model
Random Forest	Final churn prediction model

7.Model Performance

ROC-AUC used for evaluation
Recall prioritized to identify maximum churn-prone customers

8.Churn Risk Segmentation

High Risk: >70% probability
Medium Risk: 40–70%
Low Risk: <40%

9.Retention Recommendation Engine

Based on churn risk and customer value:
High risk & high value → Personalized discount
High risk → Engagement campaigns
Medium risk → Loyalty programs
Low risk → No action required

10.Business Impact

Simulated retention of 20% high-risk customers
Demonstrated potential revenue savings
Provided actionable insights for decision-makers
