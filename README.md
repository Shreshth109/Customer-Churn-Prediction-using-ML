# Customer Churn Prediction using Machine Learning

## Overview
This project predicts whether a telecom customer is likely to **churn** based on their usage patterns and account details.
Churn means when a customer leaves or stops using the services of a Company.
By identifying potential churners early, telecom companies can offer targeted benefits or discounts to **retain customers** and reduce revenue loss.

---

## Dataset
- **Rows:** 7,043  
- **Columns:** 21  
- **Target:** `Churn` (Yes/No)  

**Key Features:**  
`gender`, `tenure`, `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`, `InternetService`

---

## Steps Performed
1. **Data Cleaning & EDA** – Removed irrelevant columns, handled missing values, checked data types.  
2. **Class Imbalance Handling** – Used **SMOTE** to balance churn (Yes/No) classes.  
3. **Model Training** – Trained tree-based models:  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
4. **Model Evaluation** – Used Accuracy, Confusion Matrix, Precision, Recall, and F1-score.  
5. **Train-Test Split:** 80% training, 20% testing.

**Best Model:** Random Forest — achieved ~84% accuracy.

---

## Insights
- **Month-to-month contracts** have the highest churn rate.  
- **Short-tenure** and **high monthly charge** customers are more likely to churn.  
- **Electronic check** payment users show higher churn.  
- **Fiber optic** users churn more than DSL users.

---

## Business Impact
- Helps identify **at-risk customers** early.  
- Enables **targeted retention campaigns**.  
- Reduces customer acquisition costs.
- As in any Business, It’s more economical to retain existing customers than to acquire new ones. 

Even a small reduction in churn leads to major revenue savings for the company.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, xgboost, shap  
- **Environment:** Google Colab  
- **Deployment:** Streamlit  

---

## Future Improvements
- Build and host Streamlit app  
- Automate model monitoring using **MLflow / EvidentlyAI**  
- Try ensemble stacking for better accuracy  

---


### Author
**[Kumar Shreshth]**  
Data Science Enthusiast | Machine Learning | Python | SQL  
