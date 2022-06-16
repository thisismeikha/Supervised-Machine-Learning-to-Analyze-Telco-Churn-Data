# Supervised-Machine-Learning-to-Analyze-Telco-Churn-Data

This repository is a continuation of my previous repository that explore telco churn data analysis with EDA (https://github.com/thisismeikha/EDA-for-Telco-Churn-Data). 

To estimate factors behind churn decision, I developed four models, namely K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, and Random Forest. My goal is to find the best model.

Based on the evaluation metrics specified for unbalance data, I found that Logistic Regression is the best model among all other models because the model has the highest evaluation metrics. 

_________________________________________________________________________________________________________________________________________________________________________
Here is the detail variables in the churn data. The data itself can be downloaded here https://www.kaggle.com/datasets/blastchar/telco-customer-churn
Target: 
Churn — Whether the customer churned or not (Yes or No)

Feature:
PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Customer account information, Tenure, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, customerID, Gender, SeniorCitizen, Partner, Dependents

New Variable:
I will create a new variable, namely total_service, to catch the idea, whether adding more services could trigger churn

_________________________________________________________________________________________________________________________________________________________________________
Note: I was trained as an economist and in a process to understand data better through data science. You can find me in here (https://www.linkedin.com/in/meikha-azzani-813724138/)
