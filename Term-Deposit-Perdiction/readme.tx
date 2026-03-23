# Project: Term Deposit Subscription Prediction (Explainable AI) 🏦

### 🎯 Task Objective
The primary objective is to predict whether a bank customer will subscribe to a term deposit based on a marketing campaign dataset. A key goal is to implement **Explainable AI (XAI)** to understand the model's decision-making process and extract actionable business insights.

### 🛠️ My Approach
1. **Data Engineering:** Handled semicolon-separated data, removed special characters, and transformed categorical variables into a professional Standard Case format.
2. **Feature Encoding & Scaling:** Applied One-Hot Encoding for categorical features and StandardScaler for numerical features to prepare data for machine learning.
3. **Predictive Modeling:** Trained and evaluated two models:
   - *Logistic Regression:* Used as a linear baseline.
   - *Random Forest Classifier:* Optimized with multi-core processing (`n_jobs=-1`) and depth limits for fast and accurate non-linear predictions.
4. **Explainable AI (SHAP):** Replaced traditional "Black Box" evaluations with **SHAP** (SHapley Additive exPlanations) to extract global business drivers and explain local (individual) predictions.

### 📊 Results and Findings
- **Model Performance:** Random Forest outperformed Logistic Regression, achieving a strong ROC-AUC score, effectively distinguishing between potential subscribers and non-subscribers.
- **Business Impact Translation:** Traditional confusion matrices were translated into business metrics (Successful Hits vs. False Alarms) for stakeholder clarity.
- **Key Business Drivers (SHAP Insights):** 
  - **Contact Duration:** The length of the conversation was the most dominant factor driving subscriptions.
  - **Economic Context:** Macroeconomic indicators like `Euribor3m` (interest rates) heavily influenced customer willingness to invest.
  - **Previous Success:** Customers who converted in previous campaigns were highly likely to subscribe again.
