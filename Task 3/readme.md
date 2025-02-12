# Task 3: Decision Tree Classifier for Customer Purchase Prediction

## problem statement :
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning

## Overview
This project builds a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The Bank Marketing dataset from the UCI Machine Learning Repository is used to train and evaluate the model.

## Dataset
The dataset (bank-additional.csv) contains customer attributes such as age, job, marital status, education, loan status, contact type, and past campaign outcomes. The target variable (y) indicates whether a customer subscribed to a term deposit (yes or no).

## Technologies Used
* Python
* Pandas & NumPy (for data manipulation)
* Scikit-learn (for machine learning model & evaluation)
* Matplotlib (for visualization)

## The model will:
    * Preprocess categorical data using Label Encoding.
    * Split the dataset into training (70%) and testing (30%).
    * Train a Decision Tree Classifier with max_depth=4.
    * Evaluate the model using accuracy, classification report, and feature importance.
    * Visualize the decision tree to understand decision-making.

## Key Findings & Insights
    * Previous marketing campaign success (poutcome)
    * Duration of last contact (duration)
    * Number of previous contacts (campaign)
    * Client’s employment type (job)
    * Customers with successful past campaign interactions were more likely to purchase.
    
## Conclusion
This project demonstrates how decision trees can be used for customer purchase prediction. The insights gained can help businesses optimize marketing strategies and target the right customers effectively.
