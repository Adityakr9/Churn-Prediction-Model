# 🚀 Customer Churn Prediction Model

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** and building a **classification model** to predict which customers are likely to churn.  

The objective is to help businesses identify high-risk customers and take proactive retention actions.

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand customer behavior and churn patterns:

- Checked missing values and data types
- Handled categorical encoding and feature scaling
- Analyzed churn distribution
- Correlation analysis
- Visualized churn trends based on:
  - Contract Type
  - Tenure
  - Monthly Charges
  - Payment Method
  - Internet Service

### 🔍 Key Insights
- Customers with **Month-to-Month contracts** churn more frequently.
- Customers with **low tenure** are more likely to leave.
- Higher **Monthly Charges** increase churn probability.
- Fiber optic users show relatively higher churn rates.

---

## 🤖 Predictive Modeling

Built and compared **three classification algorithms**:

1. Logistic Regression  
2. Random Forest Classifier  
3. XGBoost Classifier  

### 📈 Evaluation Metrics Used
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 🏆 Model Comparison
- Logistic Regression → Strong baseline model
- Random Forest → Better handling of non-linear relationships
- XGBoost → Best overall performance (Highest ROC-AUC)

Final model selected based on **Recall and ROC-AUC score**, as minimizing false negatives is critical in churn prediction.

---

## ⭐ Top 5 Important Features Driving Churn

Based on feature importance analysis:

1. **Contract Type**  
2. **Tenure**  
3. **Monthly Charges**  
4. **Total Charges**  
5. **Internet Service Type**

These features significantly influence customer churn behavior.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 🎯 Business Impact

- Identify high-risk customers
- Improve retention strategies
- Reduce revenue loss
- Enable data-driven decision-making

---

## 📌 Conclusion

This project demonstrates end-to-end implementation of:
- Data Cleaning
- EDA
- Feature Engineering
- Model Building
- Model Evaluation
- Feature Importance Analysis

The model can be further improved using hyperparameter tuning and deployment strategies.
