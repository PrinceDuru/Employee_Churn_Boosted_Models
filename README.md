# EMPLOYEE CHURN PROJECT

## Problem Statement
* Identify key factors causing high performing employee churn
* Build a model to predict employees at risk for early tracking and possible prevention
* Make recommendations based on findings

## Outcomes Predictions
* Time spent in the company has heavy impact on high performing employees leaving.
* They often leave with time frame of 4 to 5 years

## Data Acquisition
Company's employees records

## Data Preparation
* Basic checks were done to filter null values, duplicated records
* Feature selection methods (Correlation and Tree Based Feature Importances) were used to remove irrelevant columns/features that wouldn't contribute to model performance 
* Employee Performance standard was assumed and adopted to filter out high performing employees based on which model was built

## Universe Description
Employees records containing features like:
* Time spent at the company
* Number of promotion in the last 5 years
* Employees Salary levels
* Number of projects completed, etc

## Modeling
Base models used:
* Logistic Regression
* Decision Tree Classifier
* Random Forest
Boosting models were also used to boost model peformance such as:
* Ada Boost
* Gradient Boosting, and
* XGBoost

## Model Evalution
Based on problem statement, the model was evaluated with Accuracy and Recall scores to minimize false negatives (FN)
Based models had good scores, and scores were optimized with boosted models

## Deliverable
* Keys factors causing high performing employee churn were discovered from data analysis and from models feature importances
* Model was built to predict high performing employees at risk of churning
* Recommendations were made based on findings
