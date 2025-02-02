## Customer Churn Prediction
![image](https://github.com/user-attachments/assets/ff82b6a5-d593-4d4a-a9ed-33bc301a095d)

📉 High customer churn rates lead to significant revenue losses and reduced business growth.
This project focuses on predicting customer churn using machine learning to help businesses develop effective retention strategies.

## 🛑 Problem Statement
🔴 Over 56.71% of customers have churned, leading to major revenue loss.
💰 Total cost of churn exceeds $135 million, impacting profitability.
📞 Customers with lower tenure, frequent payment delays, and higher support calls are more likely to churn.

## 📊 Dataset Overview
📂 Source: Kaggle Customer Churn Dataset
📌 Total Records: 505,206 customer records
📌 Features: 12 predictive variables
📌 Target Variable: Churn (1 = Customer Left, 0 = Customer Stayed)

🔹 Training Data: 440,832 customer records
🔹 Testing Data: 64,374 customer records

## 🛠 Data Preprocessing
✔️ Data Cleaning:
Removed rows with missing values.
Dropped irrelevant columns.

✔️ Data Transformation:
📌 Categorical Encoding: One-Hot Encoding applied to categorical features (Gender, Subscription Type, Contract Length).
📌 Feature Scaling: Scaled numerical features for consistency.
✔️ Handling Imbalanced Classes:

Applied stratified sampling to improve model performance.

## 🚀 Machine Learning Models & Performance
Model	Accuracy	Precision	Recall
Logistic Regression	Baseline Model	Benchmark for comparison	
Random Forest	🔼 Higher Accuracy	🔼 Improved Precision & Recall	
XGBoost	🚀 Best Performance	📊 Effective in identifying churners	

## 🔍 Feature Importance & Key Insights
🔹 Most Important Features:
✅ Support_Calls - High support calls correlate with churn
✅ Total_Spend - Higher spending customers are less likely to churn
✅ Contract_Length_Monthly - Short-term contracts have higher churn rates

## 📌 Key Takeaways:
📞 Customers with frequent support calls are more likely to churn.
📅 Shorter contract lengths increase churn risk.
💎 Premium subscriptions show lower churn rates compared to basic plans.

## 💡 Business Strategy:
📈 Develop personalized retention programs for high-risk customers.
🎯 Prioritize early engagement with customers who have higher support call volumes and shorter tenure.
