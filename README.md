# Churn-Prediction-Model
Churn Prediction Model with EDA, Feature Engineering and testing out different models. Based on a kaggle notebook.
Test it out: 

## What is churn prediction?

Churn prediction is the process by which businesses attempt to predict which customers are at high risk of leaving the company or cancelling a subscription to a service, based on their behaviour with your product.

## Why is it important?

- The cost of acquiring a new customer is almost always greater than the cost to retain an existing customer.
- This implies that businesses should prioritise retaining its existing customers.
- Customer churn informs a business if a customer is likely to leave the company.
- The business can then take further action to retain the customer such as targeted re-engagement campaigns or even re-evaluating company-wide retention initiatives like pricing.
- Predicting churn allows for the identification of factors that lead to churn.
- Predicting churn helps in preventing churn

## What is this project about?

This project takes a dataset from kaggle:

https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics

This dataset contains 2 tables, in CSV format:

- The Customer Churn table contains information on all 7,043 customers from a Telecommunications company in California in Q2 2022
- Each record represents one customer, and contains details about their demographics, location, tenure, subscription services, status for the quarter (joined, stayed, or churned), and more!
- The Zip Code Population table contains complimentary information on the estimated populations for the California zip codes in the Customer Churn table

The aim of the project is to create a churn prediction model to predict which customers are likely to leave the company. This is done through classification (0 = Customer will stay, 1 = Customer will churn).

## Processes used:

- EDA: In depth analysis of the dataset features
- Feature Engineering: Creating new features which aim to accurately model the relationship between the original features and the target variable
- Testing out different models: Several unique models were utilised throughout the project - RandomForestClassifier, Neural Networks and XGBoost

## What is included in the project?

The project includes the files used for data analysis and model testing. I conducted two trial runs of the entire process (EDA -> Model Testing).

## How can you test it out?

I have summarised the best results and data analysis in a kaggle notebook which you can find by clicking this link:
