# Telecom-Churn-Analysis
# Customer Churn Analysis (EDA)

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a telecom customer dataset (`Customer Churn.csv`) to identify patterns and factors affecting customer churn. 

Churn (customer attrition) is a critical metric for subscription-based businesses, and this analysis helps uncover key behaviors and customer profiles associated with churn.

---

## 📂 Dataset
- **File:** `Customer Churn.csv`
- **Rows:** ~7,000 customers
- **Target Variable:** `Churn` (Yes/No)
- **Features include:**
  - Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Services: `PhoneService`, `InternetService`, `StreamingTV`, etc.
  - Account Info: `tenure`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`

---

## ⚙️ Steps Performed

1. **Data Loading**
   - Read the dataset using `pandas`.
   - Checked shape, duplicates, and missing values.

2. **Data Preprocessing**
   - Converted `SeniorCitizen` (0/1 → Yes/No).
   - Handled categorical variables for better interpretation.

3. **Exploratory Data Analysis (EDA)**
   - Distribution of churn vs. non-churn customers.
   - Count plots for categorical features (e.g., `Contract`, `InternetService`).
   - Violin plots for numerical features like `tenure` and `MonthlyCharges`.
   - Pair plots to analyze multi-feature relationships.

4. **Insights**
   - Customers with **shorter tenure** tend to churn more.
   - **Month-to-month contracts** show higher churn rates compared to yearly contracts.
   - Higher **monthly charges** are correlated with churn.
   - Customers with **fiber optic internet** and **no online security** are more likely to churn.

---

## 📊 Visualizations
- **Churn distribution plots**
- **Count plots** for service types
- **Violin plots** for tenure & monthly charges
- **Correlation heatmaps**

---

## 🛠️ Tech Stack
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (Label Encoding)

---

## 🚀 How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/churn-analysis.git

