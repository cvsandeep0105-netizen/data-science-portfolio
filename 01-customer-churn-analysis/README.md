# Customer Churn Analysis & Prediction

## Project Overview
This project analyzes customer churn behavior using exploratory data analysis (EDA) 
and machine learning models to identify key factors influencing customer retention.

## Dataset
- IBM Telco Customer Churn Dataset
- Records: 7,043 customers
- Features: Demographics, contract details, services, billing information

## Exploratory Data Analysis
- Churn distribution analysis
- Churn vs contract type, tenure, monthly charges
- Churn vs internet service and payment methods

## Models Used
- Logistic Regression
- Random Forest Classifier
- 
## Model Comparison

| Model              | Accuracy | ROC-AUC |
|-------------------|----------|---------|
| Logistic Regression | 70%      | 0.83    |
| Random Forest      | 78%      | 0.88    |


## Model Performance
Logistic Regression:
- Accuracy: ~70%
- ROC-AUC: ~0.83

 ## Final Model Selection

Random Forest was selected as the final model due to its higher ROC-AUC score
and better ability to capture non-linear relationships in customer behavior.

## Key Insights
- Month-to-month contracts show highest churn
- Low tenure customers are more likely to churn
- High monthly charges increase churn probability
- Fiber optic users have higher churn risk


## How This Can Be Used in Production
- Identify high-risk customers monthly
- Trigger retention offers for high-risk segments
- Reduce churn-driven revenue loss
- 

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Business Impact
This analysis helps telecom companies proactively identify high-risk customers 
and design targeted retention strategies.

## Author
Sandeep Reddy
