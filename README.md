# Credit-card-customer-churn-Prediction
Project Overview
Welcome to my hackathon project on predicting credit card customer churn! Our goal (Team Pinnacle) is to develop a robust classification model that can help banks identify customers likely to discontinue their credit card services. Understanding the reasons behind these decisions will enable banks to take proactive measures to retain valuable customers.

## Dataset
The dataset contains various features related to customers' credit card usage and demographic information. Key attributes include:
Customer_Age                   
Dependent_count                 
Months_on_book                 
Total_Relationship_Count        
Months_Inactive_12_mon          
Contacts_Count_12_mon           
Credit_Limit                
Total_Revolving_Bal         
Avg_Open_To_Buy             
Total_Amt_Chng_Q4_Q1         
Total_Trans_Amt             
Total_Trans_Ct              
Total_Ct_Chng_Q4_Q1          
Avg_Utilization_Ratio

## Features
We engineered several features to enhance our model's performance:

Customer Demographics: Age, Gender, Marital Status
Account Information: Credit Limit, Balance
Transaction History: Purchase Frequency, Payment History

## Models
We explored multiple machine learning models to identify the best classifier:
Logistic Regression
Random Forest
Decision Tree
Gradient Boosting
XGBoost
Each model was evaluated using cross-validation and test accuracy metrics.

## Evaluation
Our models were evaluated based on accuracy, precision, recall, and F1-score. Below are some highlights from our findings:
Best Model: Random Forest
Key Influencing Features: Total_Trans_Ct, Total_Trans_Amt  , Total_Ct_Chng_Q4_Q1, Total_Revolving_Bal, Avg_Utilization_Ratio   
