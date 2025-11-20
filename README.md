## Customer Churn Prediction (Classification)

## Overview
This project predicts customer churn using the Telco Customer Churn dataset.  
The model analyzes customer behavior patterns to identify who is likely to leave the service.

## Objectives
- Analyze churn behavior patterns  
- Perform data cleaning & preprocessing  
- Train ML models for churn prediction  
- Evaluate using classification metrics  
- Identify important features that drive churn  

## Dataset
**Telco Customer Churn**  
Important variables:
- `gender`, `SeniorCitizen`, `tenure`
- `Contract`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (Target)

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- RandomForestClassifier  

## Workflow
1. Load dataset  
2. Convert numeric columns & fill missing values  
3. Label encode categorical variables  
4. EDA — churn distribution, correlations  
5. Train-test split  
6. Model training (Random Forest)  
7. Evaluate: Accuracy, F1-score, classification report  
8. Feature importance  

## Model Performance
- **Accuracy:** ~80–85%  
- **F1-score:** depends on training  
- **Top churn factors:**  
  - Contract type  
  - Monthly charges  
  - Tenure  

## Key Insights
- Month-to-month contract customers churn more  
- Higher monthly charges → higher churn  
- New customers (short tenure) churn more  

## Future Work
- Hyperparameter tuning  
- Try XGBoost, LightGBM  
- Apply SMOTE for imbalance  
- Model deployment with Streamlit  

## Files
- `notebook.ipynb` — full code  
- `README.md` — documentation  
