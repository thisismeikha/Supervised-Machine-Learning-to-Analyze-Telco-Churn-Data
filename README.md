# Supervised-Machine-Learning-to-Analyze-Telco-Churn-Data

This repository is a continuation of my previous repository that explore telco churn data analysis with EDA (https://github.com/thisismeikha/EDA-for-Telco-Churn-Data). To estimate factors behind churn decision, I developed four models, namely K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, and Random Forest. To find the best model, I employed metrics specified for unbalanced data.

Based on the evaluation metrics, Logistic Regression has the highest metrics among all other models. Thus we can use the model to analyze the data.

Here is the detail variables in the churn data
This is telco churn data

Target

Churn — Whether the customer churned or not (Yes or No)

Feature

PhoneService

MultipleLines

InternetService

OnlineSecurity

OnlineBackup

DeviceProtection

TechSupport

StreamingTV

StreamingMovies

Customer account information

Tenure

Contract

PaperlessBilling

PaymentMethod

MonthlyCharges

TotalCharges

customerID

Gender

SeniorCitizen

Partner

Dependents

New Variable

I will create a new variable, namely total_service, to catch the idea, whether adding more services could trigger churn
