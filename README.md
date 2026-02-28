# zoho-churn-detection

# SaaS User Churn Prediction System

## Overview

This project builds a machine learning system to predict which users are likely to stop using a SaaS (Software as a Service) product such as Zoho CRM.

Customer churn is a major problem for SaaS companies because losing users means losing revenue. This system helps identify users who are at risk of leaving, so companies can take action early to retain them.

The model analyzes user activity data and assigns a churn risk score to each user.

---

## Problem Statement

SaaS companies often have thousands of users, and it is difficult to manually identify which users may stop using the product.

This project solves that problem by:

- Analyzing user behavior data
- Predicting the probability of churn
- Classifying users into risk levels
- Providing insights to improve customer retention

---

## What This Project Does

This system performs the following steps:

1. Loads user activity data such as login frequency, session duration, feature usage, and inactivity period  
2. Trains a machine learning model to learn patterns from user behavior  
3. Predicts the churn probability for each user  
4. Classifies users into:
   - High Risk
   - Medium Risk
   - Low Risk  
5. Identifies the key factors that influence churn  
6. Saves the results for business use  

---

## Business Value

This system helps SaaS companies:

- Identify users at risk of leaving
- Take preventive actions such as engagement campaigns
- Improve customer retention
- Reduce revenue loss
- Make data-driven business decisions

---

## Technologies Used

- Python  
- Pandas (data analysis)  
- NumPy (numerical operations)  
- Scikit-learn (machine learning)  
- Matplotlib and Seaborn (data visualization)  
- Jupyter Notebook  

---

## Machine Learning Model

This project uses the Random Forest Classifier, which is a reliable and widely used machine learning algorithm.

The model learns patterns from user activity and predicts churn probability based on behavior.

---


---

## Output

The system generates:

- Churn probability for each user
- Risk classification (High, Medium, Low)
- Feature importance analysis
- Final CSV file with predictions

---

## Key Insights

The model identifies important factors that influence churn, such as:

- Days since last login
- Feature usage
- Login frequency
- Session duration

These insights help businesses understand user behavior better.

---

## Conclusion

This project demonstrates how machine learning can be used to solve a real business problem.

It provides a practical system that helps SaaS companies identify churn risk, improve customer retention, and make better decisions using data.

---

## Author

Umang Dadhich  
Data Science and Machine Learning Enthusiast
