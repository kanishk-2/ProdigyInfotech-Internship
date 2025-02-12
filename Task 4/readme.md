# Task 5:
Traffic Accident Analysis & Prediction

## problem statement -
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.

## Overview
This project analyzes traffic accident data to identify patterns related to road conditions, weather, and time of the day. Additionally, it builds a K-Nearest Neighbors (KNN) classifier to predict accident severity based on contributing factors.

## Dataset
The dataset (RTA Dataset.csv) contains accident-related attributes such as number of vehicles involved, casualties, weather conditions, road surface type, accident location, and driver details.

## Technologies Used
* Python
* Pandas & NumPy (for data processing)
* Seaborn & Matplotlib (for data visualization)
* Scikit-learn (for machine learning)
* Imbalanced-learn (SMOTE) (for handling class imbalance)

##  The model will:
    * Perform data cleaning (handle missing values, drop irrelevant columns).
    * Visualize accident severity distribution and correlations using heatmaps.
    * Analyze contributing factors such as weather, road conditions, and time of day.
    * Apply label encoding and one-hot encoding for categorical variables.
    * Balance the dataset using SMOTE (Synthetic Minority Over-sampling Technique).
    * Train a K-Nearest Neighbors (KNN) model to classify accident severity.
    * Evaluate the model using classification reports, confusion matrices, and accuracy scores.
    
## Key Findings & Insights
* Most accidents occur under normal weather conditions, but rainy conditions increase severity.
* Road surface conditions (e.g., wet roads) contribute to higher accident severity.
* Accidents peak during specific times of the day (rush hours).
* The KNN model achieved an accuracy of ~70-80% in predicting accident severity.

## Conclusion
This project provides valuable insights into traffic accident patterns and helps in predicting accident severity based on road and environmental factors. The findings can assist in improving road safety policies and accident prevention strategies.
