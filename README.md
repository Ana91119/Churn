# Customer Churn Prediction  
A machine learning project to predict customer churn for a subscription-based service using Logistic Regression and Decision Tree Classifier.

## Overview  
The goal of this project is to identify customers likely to discontinue their subscription. Predicting churn helps businesses implement targeted retention strategies, reduce customer loss, and optimize resources.

## Dataset  
The dataset contains customer-level data with features such as:  
- Subscription type and contract length  
- Customer demographics (age, gender)  
- Service usage frequency  
- Payment history (e.g., delayed payments)

## Methodology  
1. **Data Preprocessing**: Handling missing values, feature scaling, and encoding categorical variables.  
2. **Model Development and Evaluation**:  
   - Logistic Regression (Accuracy: 84.9%, AUC: 0.91)  
   - Decision Tree Classifier (Accuracy: 93.5%, AUC: 0.953)  

## Key Technologies  
- Python (Pandas, NumPy, Scikit-learn)  
- Visualization: Matplotlib, Seaborn  

## Business Insights  
- Decision Tree Classifier is suitable for identifying all possible churners due to its high recall.  
- Logistic Regression provides a more balanced approach for targeted interventions.

