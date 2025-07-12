<div style="font-family: Arial, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; background-color: #f9f9f9; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

# 🔹 Telecoms Customer Churn Analysis with Python 🔹

<div style="text-align: center; margin-bottom: 20px;">
  <img src="https://img.icons8.com/color/48/000000/telecom.png" alt="Telecom Icon" style="vertical-align: middle; margin-right: 10px;">
  <span style="font-size: 1.2em; color: #333;">Data Cleaning and Exploratory Data Analysis (EDA) on Telecom Customer Data</span>
</div>

---

## 1. Introduction

Customer churn refers to the phenomenon where clients discontinue their business with a company. Reasons for churn include affordability issues, dissatisfaction with services, or poor customer experiences.

**Objective**: Perform data cleaning and exploratory data analysis (EDA) to uncover trends, inconsistencies, and key insights related to customer churn in a telecom dataset.

**Dataset Overview**: The dataset includes telecom customer details such as demographics, service subscriptions, billing information, and churn status.

<div style="background-color: #e6f3ff; padding: 15px; border-radius: 8px; margin: 10px 0;">
  <strong>Dataset Source</strong>: Telecom customer data with attributes like CustomerID, Gender, SeniorCitizen, Partner, Dependents, Tenure, Services, Contract, PaymentMethod, MonthlyCharges, TotalCharges, and Churn.
</div>

---

## 2. Data Cleaning Process

### 2.1 Handling Missing Values
- Checked for missing values across all columns.
- Identified missing values in `TotalCharges` and imputed them with the column's mean or median after replacing empty strings.
  
### 2.2 Data Type Corrections
- Converted `TotalCharges` from string to numeric format.
- Ensured categorical variables (e.g., `Gender`, `Contract`, `PaymentMethod`) were correctly encoded for analysis.

### 2.3 Handling Duplicates
- Verified no duplicate `CustomerID` entries to ensure dataset integrity.

### 2.4 Addressing Outliers
- Used boxplots and the IQR method to detect outliers in `MonthlyCharges` and `TotalCharges`.
- Analyzed outliers' impact and applied capping for extreme values where necessary.

<div style="text-align: center; margin: 20px 0;">
  <img src="https://img.icons8.com/ios-filled/50/000000/data-cleaning.png" alt="Data Cleaning Icon" style="vertical-align: middle;">
  <span style="font-style: italic; color: #555;">Clean data is the foundation of meaningful insights.</span>
</div>

---

## 3. Exploratory Data Analysis (EDA)

### 3.1 Demographic Analysis
- **Gender Distribution**: Analyzed male vs. female customer proportions.
- **Senior Citizens**: Investigated if senior citizens have a higher churn rate.
- **Partner and Dependents**: Evaluated their influence on churn behavior.

### 3.2 Service Subscription Analysis
- **Phone and Internet Services**: Examined how service combinations affect churn.
- **Additional Features**:
  - Analyzed services like Online Security, Backup, Device Protection, Tech Support, and Streaming.
  - Identified services most associated with churn.

### 3.3 Contract and Billing Analysis
- **Contract Types**: Compared churn rates across month-to-month, one-year, and two-year contracts.
- **Payment Methods**: Assessed churn likelihood by payment methods (e.g., electronic check, credit card).
- **Monthly Charges vs. Churn**: Investigated correlation between high charges and churn.
- **Paperless Billing**: Evaluated churn among customers using paperless billing.

### 3.4 Churn Trend Analysis
- **Churn Rate Overview**:
  - Calculated the percentage of customers who churned.
  - Identified key characteristics of churned customers.
- **Tenure vs. Churn**:
  - Analyzed churn patterns based on customer tenure.
  - Determined if newer customers are more likely to churn.

<div style="background-color: #e6ffec; padding: 15px; border-radius: 8px; margin: 10px 0;">
  <strong>EDA Tools Used</strong>: Python libraries including Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.
</div>

---

## 4. Key Findings & Insights

- **Contract Impact**: Customers with month-to-month contracts exhibited the highest churn rates.
- **Demographic Trends**: Senior citizens and single customers (without partners or dependents) showed higher churn tendencies.
- **Service Influence**: Lack of tech support or security services correlated with higher churn.
- **Billing Patterns**: Higher monthly charges were linked to increased churn, though long-term customers were more loyal despite high charges.
- **Payment Method**: Electronic check users had the highest churn rate among payment methods.

<div style="text-align: center; margin: 20px 0;">
  <img src="https://img.icons8.com/color/48/000000/light-bulb.png" alt="Insights Icon" style="vertical-align: middle;">
  <span style="font-style: italic; color: #555;">Insights drive actionable strategies.</span>
</div>

---

## 5. Recommendations

- **Customer Retention Strategy**: Offer discounts or incentives to encourage long-term contracts.
- **Enhance Customer Support**: Promote tech support and security services to boost satisfaction.
- **Billing Optimization**: Address high churn among electronic check users by promoting alternative payment methods.
- **Loyalty Programs**: Implement first-year discounts or engagement programs to retain new customers.

---

## 6. Conclusion

This EDA revealed critical insights into customer churn trends and factors influencing churn behavior in the telecom industry. These findings provide a foundation for strategic decisions to enhance customer retention and reduce churn rates.

<div style="background-color: #fff3cd; padding: 15px; border-radius: 8px; margin: 10px 0;">
  <strong>Next Steps</strong>: Build predictive models (e.g., logistic regression, random forest) to forecast churn and evaluate feature importance for targeted interventions.
</div>

---

<div style="text-align: center; margin-top: 20px;">
  <strong>Tools & Technologies</strong>
  <p>
    <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" style="margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/pandas.png" alt="Pandas" style="margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/numpy.png" alt="NumPy" style="margin: 0 10px;">
    <img src="https://img.icons8.com/ios-filled/50/000000/matplotlib.png" alt="Matplotlib" style="margin: 0 10px;">
    <img src="https://img.icons8.com/color/48/000000/seaborn.png" alt="Seaborn" style="margin: 0 10px;">
  </p>
</div>

<div style="text-align: center; margin-top: 20px; font-size: 0.9em; color: #555;">
  <p>Project by [Samuel Idinotu Enyaude] | <a href="https://github.com/Enyaude" style="color: #007bff; text-decoration: none;">GitHub</a> | <a href="mailto:your.enyaudesamuel@gmail.com" style="color: #007bff; text-decoration: none;">Contact</a></p>
</div>

</div>
