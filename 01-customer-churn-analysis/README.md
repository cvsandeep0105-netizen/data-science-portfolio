# Customer Churn Analysis & Prediction

## Project Overview
This project analyzes customer churn behavior using exploratory data analysis (EDA) 
and machine learning models to identify key factors influencing customer retention.

### Key Results
- Best Model: Random Forest
- ROC-AUC: 0.88
- Accuracy: 78%

## Project Flow
1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature encoding and scaling  
5. Model training and evaluation  
6. Model comparison and selection  
7. Business insights and recommendations

## Dataset
- **Name:** IBM Telco Customer Churn Dataset  
- **Source:** Kaggle  
- **Records:** 7,043 customers  
- **Description:** Customer demographics, subscription details, services, and billing information used to analyze and predict customer churn.

  
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

## Results Summary
- Best Model: Logistic Regression / Random Forest
- Accuracy: 82%
- ROC-AUC: 0.85
- Key Findings:
  - Month-to-month contract customers show the highest churn
  - Higher monthly charges correlate with increased churn risk
  - Long-tenure customers are less likely to churn

## Business Impact
- Target high-risk customers with retention offers
- Reduce churn and increase customer lifetime value

- ## How This Can Be Used in Production
- Identify high-risk customers monthly using churn probability scores
- Trigger retention offers for high-risk segments
- Integrate model with CRM systems for automated alerts
- Reduce churn-driven revenue loss through proactive intervention

## Future Improvements
- Hyperparameter tuning using GridSearchCV
- Handling class imbalance using SMOTE
- Adding explainability using SHAP values
- Deploying the model as a REST API

- https://github.com/cvsandeep0105-netizen/data-science-portfolio/blob/main/01_customer_churn_eda_and_modeling%20(1).ipynb

## Author
Sandeep Reddy
