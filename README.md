# Google-Advanced-Data-Analytics-Specialization-Capstone-Project
Project done as part of my Google Advanced Data Analytics Specialization Course .This project focuses on building a machine learning model to predict employee attrition and identify the key factors influencing employee turnover. The goal is to help organizations make data-driven decisions to improve employee retention.


# HR Attrition Prediction using Machine Learning

## Overview
This project builds a machine learning model to predict employee attrition and identify the key factors influencing employee turnover. The objective is to enable data-driven decision-making for improving employee retention.

---

## Problem Statement
Employee attrition leads to increased hiring costs, productivity loss, and operational inefficiencies. This project aims to:
- Predict whether an employee will leave the company
- Identify key drivers of attrition
- Provide actionable insights for HR teams

---

## Dataset
- ~15,000 employee records
- Features include:
  - Satisfaction level
  - Last evaluation score
  - Number of projects
  - Average monthly working hours
  - Tenure
  - Work accident history
  - Promotion history
  - Department
  - Salary level

---

## Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn, XGBoost  

---

## Workflow
1. Data Cleaning  
   - Removed duplicates (~3000 records)  
   - Renamed columns for consistency  

2. Exploratory Data Analysis (EDA)  
   - Identified relationships between features and attrition  
   - Visualized distributions and correlations  

3. Feature Engineering  
   - One-hot encoding for categorical variables  
   - Prepared training and testing datasets  

4. Model Building  
   - Logistic Regression (baseline)  
   - Random Forest  
   - XGBoost  

5. Model Evaluation  
   - Accuracy, Precision, Recall, F1-score  
   - ROC-AUC curve  
   - Confusion matrix  

---

## Results
| Model                | Accuracy | Recall (Attrition) | Precision (Attrition) |
|---------------------|---------|--------------------|----------------------|
| Logistic Regression | ~77%    | 0.84               | 0.39                 |
| Random Forest       | ~99%    | 0.93               | 0.98                 |
| XGBoost             | ~99%    | 0.93               | 0.98                 |

- Ensemble models significantly outperformed the baseline
- High recall ensures most attrition cases are correctly identified

---

## Key Insights
- Low satisfaction is the strongest predictor of attrition  
- High workload (long hours, many projects) increases turnover risk  
- Employees with low salary are more likely to leave  
- Lack of promotion significantly impacts retention  

---

## Business Recommendations
- Improve employee satisfaction through regular feedback  
- Monitor and balance workload  
- Provide clear promotion paths  
- Review compensation for low-salary employees  
- Use predictive models for proactive retention strategies  

---

## Future Improvements

- Deploy model using Streamlit or Flask  
- Add real-time prediction capability  
- Perform advanced feature engineering  

---
