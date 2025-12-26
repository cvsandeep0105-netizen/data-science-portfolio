# Customer Churn Analysis & Prediction

## 🔍 Business Problem
Customer churn directly impacts company revenue. Retaining an existing customer is significantly cheaper than acquiring a new one.  
This project builds a machine learning model to **predict customer churn in advance**, enabling businesses to take **proactive retention actions**.



## 🎯 Business Objective
- Identify customers likely to churn
- Understand key drivers of churn
- Enable data-driven retention strategies
- Reduce revenue loss



## 📊 Dataset
**IBM Telco Customer Churn Dataset**

- Records: 7,043 customers
- Features include:
  - Demographics
  - Contract type
  - Services subscribed
  - Billing and payment behavior
- Target variable: `Churn` (Yes / No)



## ⚙️ Project Workflow
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



## 🧪 Models Evaluated
- Logistic Regression (Baseline)
- Random Forest (Final Model)
 6e39cbc (Add author info and finalize Project 1)

Baseline models ensure that advanced models add **real business value**

## 📈 Key Results
| Metric | Score |
|------|------|
| Accuracy | ~78% |
| ROC-AUC | ~0.88 |
| Best Model | Random Forest |

Random Forest outperformed the baseline by capturing **non-linear relationships** in customer behavior.


## 🔑 Key Insights
- Contract type strongly influences churn
- Month-to-month customers churn more
- Higher monthly charges increase churn risk
- Long-tenure customers are less likely to churn



## 🏭 Production Readiness
This solution can be integrated into production systems:
- Periodic model retraining
- CRM system integration
- Real-time churn risk scoring
- Monitoring for data drift


## 🚀 Conclusion
The model effectively identifies high-risk customers and provides actionable insights.  
This solution supports **data-driven decision-making** and can significantly reduce churn when deployed at scale.

## 📏 Baseline Comparison Strategy
A baseline Logistic Regression model was trained to establish a reference performance.

 
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

This ensures:
- Model improvement is measurable
- Advanced models justify their complexity
- Business stakeholders trust the results
 6e39cbc (Add author info and finalize Project 1)

Random Forest was selected only after outperforming the baseline on ROC-AUC and stability.

## 👤 Author

**Venkata Sandeep Kumar Reddy**  
 Aspiring Data Scientist / ML Engineer