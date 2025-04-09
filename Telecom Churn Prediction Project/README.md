#  Telecom Churn Prediction Project

## Overview
This project aims to predict customer churn in the telecom industry using machine learning. By identifying the key drivers of churn, telecom companies can take proactive steps to retain valuable customers, reduce revenue loss, and optimize service offerings.

---

##  Tools & Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Problem Statement
Customer churn is a major concern for telecom companies. Losing customers not only affects revenue but also increases acquisition costs.  
**Goal**: Use historical customer data to predict whether a customer is likely to churn and identify the main features influencing their decision.

---

##  Dataset Information
- **Source**: [Kaggle – Telecom Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7,043  
- **Columns**: 21 features including:
  - `gender`, `SeniorCitizen`, `tenure`, `Contract`, `InternetService`, `MonthlyCharges`, `Churn` (target)

---

## Project Workflow
1. **Data Cleaning**
   - Handled missing values and incorrect data types
2. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution across demographics and services
3. **Feature Engineering**
   - Encoded categorical variables, removed redundant features
4. **Model Building**
   - Used Logistic Regression and Decision Tree Classifier
5. **Model Evaluation**
   - Confusion Matrix, Accuracy, Precision, Recall, F1-Score

---

## Key Insights
- Customers with **month-to-month contracts** are more likely to churn.
- Higher **monthly charges** correlate with increased churn probability.
- **Fiber optic** internet users churn more than DSL users.
- Customers without tech support or online backup tend to leave more often.
- Longer tenure reduces the chances of churn.

---

## Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression | 80.8%    | 72.3%     | 68.5%  | 70.3%    |
| Decision Tree       | 78.6%    | 70.1%     | 66.2%  | 68.1%    |

> Logistic Regression performed slightly better and is easier to interpret for business teams.

---
