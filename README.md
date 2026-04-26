# 📊 Customer Churn Prediction using Machine Learning

## 📌 Problem Statement
Customer churn is a critical issue in telecom and subscription-based businesses. 
Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to:
> Predict whether a customer will churn and identify key factors driving churn behavior.

---

## 📊 Dataset
- Telco Customer Churn Dataset  
- 7043 customer records  
- 21 features including demographic, service, and billing information  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🔍 Approach

### 1. Data Preprocessing
- Converted `TotalCharges` to numeric and handled missing values  
- Removed irrelevant features (`customerID`)  
- Encoded categorical variables using one-hot encoding  

---

### 2. Exploratory Data Analysis (EDA)
Key findings:
- Customers with **month-to-month contracts** have the highest churn rate  
- Customers with **low tenure** are more likely to churn  
- Pricing and service-related features significantly influence churn  

---

### 3. Model Building
Models implemented:
- Logistic Regression  
- Random Forest  

---

### 4. Handling Class Imbalance
- Dataset was imbalanced (majority non-churn customers)  
- Applied `class_weight='balanced'` to improve churn detection  

---

## 📈 Results

| Model | Accuracy | Recall (Churn) |
|------|--------|----------------|
| Logistic Regression | 75% | **82%** |
| Random Forest | 79% | 46% |

👉 Logistic Regression was selected as the final model due to higher recall.

---

## 🧠 Key Insights
- Customers using **fiber optic internet** have higher churn probability  
- Customers using **electronic check payment methods** are more likely to churn  
- Customers with **streaming services** show increased churn tendency  
- High-value customers may churn due to pricing sensitivity  

---

## 💡 Business Recommendations
- Encourage long-term contracts through discounts or incentives  
- Improve service quality for high-paying customers  
- Promote automatic payment methods to increase retention  
- Offer bundled service packages to reduce churn  

---

## 🚀 Future Improvements
- Implement advanced models (XGBoost, Neural Networks)  
- Deploy model using Streamlit or Flask  
- Build interactive dashboard using Power BI  

---

## 📌 Conclusion
This project demonstrates how machine learning can be applied to solve a real-world business problem by:
- Predicting customer churn  
- Identifying key risk factors  
- Providing actionable business insights  

---
