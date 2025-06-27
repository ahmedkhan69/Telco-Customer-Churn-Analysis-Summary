# 📊 Telco Customer Churn - Exploratory Data Analysis (EDA)

This project presents an **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset. The goal is to understand customer behavior, identify churn trends, and visualize patterns that help guide business decisions.

---

## 📁 Dataset Overview
- **Total Records**: ~7,043 customers
- **Churn Rate**: ~26.5%
- **Retention Rate**: ~73.5%
- **Target Column**: `Churn` (Yes/No)

---

## 📌 Objectives
- Perform a clean, structured EDA on churn-related data.
- Visualize distributions and correlations between features.
- Highlight key churn indicators using countplots and percentages.

---

## 🔍 Key Insights
- 🔸 **Electronic Check** users show the **highest churn** (~45%).
- 🔸 Customers with **tenure <12 months** are more likely to churn.
- 🔸 **Month-to-month** contracts result in **3x higher churn** vs. annual plans.
- 🔸 Customers without **Tech Support** and **Online Security** churn more often.
- 🔸 **Fiber optic users** churn more than DSL customers.

---

## 📈 Visual Analysis
- **Countplots** used for categorical variable distribution.
- Plots by `Churn` show differences across services like:
  - `InternetService`
  - `PaymentMethod`
  - `Contract`
  - `TechSupport`, `OnlineSecurity`, etc.

---

## ✅ Recommendations
- 💡 Promote **annual contracts** through offers or discounts.
- 💡 Improve **onboarding** for new users (<6 months).
- 💡 Encourage **auto-pay methods** to reduce electronic check churn.
- 💡 Upsell **support and security add-ons** to monthly users.
- 💡 Monitor and enhance **fiber user experience**.

---

## 🛠️ Tools & Libraries
- **Python**: Pandas, NumPy
- **Visualization**: Seaborn, Matplotlib
- **Notebook**: Jupyter

---

## 📝 Summary Statement
> This EDA reveals service patterns and customer behaviors that drive churn. The findings can support data-driven retention strategies and deeper predictive modeling in future steps.

---

