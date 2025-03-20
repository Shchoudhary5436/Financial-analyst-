**# Data Analysis Report: Bank Personal Loan Modeling**

## **1. Introduction**
This report analyzes the customer dataset from a financial institution to understand factors influencing personal loan acceptance. The dataset consists of 5,000 customer records with various demographic and financial attributes.

## **2. Dataset Overview**
- **Total Records:** 5,000
- **Columns:** 14 (Demographics, Financial Details, and Banking Features)
- **Key Variables:**
  - **Demographics:** Age, Experience, ZIP Code, Family Size
  - **Financials:** Income, Credit Card Spending (CCAvg), Mortgage
  - **Banking Services:** Securities Account, CD Account, Online Banking, Credit Card Usage
  - **Target Variable:** Personal Loan Acceptance (1 = Accepted, 0 = Not Accepted)

## **3. Key Insights & Trends**

### **3.1 Loan Acceptance Rate**
- **Only 9.6% of customers accepted a personal loan**, indicating a low conversion rate despite marketing efforts.

### **3.2 Factors Affecting Loan Acceptance**
1. **Income (Correlation: 0.50)** – Higher income significantly increases loan acceptance probability.
2. **Credit Card Spending (Correlation: 0.36)** – Customers with high credit card usage are more likely to take loans.
3. **CD Account Ownership (Correlation: 0.31)** – Customers with CD accounts tend to accept personal loans.
4. **Mortgage (Correlation: 0.14)** – Customers with existing mortgages show a slight increase in loan acceptance.
5. **Education Level (Correlation: 0.13)** – Higher education levels correlate with higher loan acceptance.

### **3.3 Weak or No Influence on Loan Acceptance**
- **Securities Account (0.02)** – Minimal impact on loan decisions.
- **Online Banking Usage (0.006)** – No significant effect.
- **Credit Card Ownership (0.0028)** – Owning a credit card does not necessarily increase loan acceptance.

## **4. Recommendations for the Bank’s Marketing Strategy**
✅ **Target High-Income Customers:** Focus on individuals earning **above ₹75,000** as they are more likely to take loans.
✅ **Engage Customers with High Credit Card Usage:** Prioritize users with **monthly credit card spending over ₹2,500**.
✅ **Leverage CD Account Holders:** Offer tailored loan products to customers who already have **CD accounts**.
✅ **Improve Loan Awareness for Middle-Income Customers:** Implement **better financial education and customized loan offers** to increase adoption rates.

## **5. Conclusion**
This analysis provides actionable insights into customer behavior and loan acceptance trends. The findings will help improve **targeted marketing strategies** and enhance **conversion rates** for personal loans.

---

### **Next Steps: Power BI Report**
To visualize this analysis, import the cleaned dataset into Power BI and create:
- **Bar Chart:** Loan Acceptance vs. Income Levels
- **Pie Chart:** Loan Acceptance by Education Level
- **Scatter Plot:** Loan Acceptance vs. Credit Card Spending
- **Heatmap:** Correlation of financial factors with loan acceptance

These visualizations will provide a clearer understanding of the patterns and help refine business strategies.

---
**Prepared by:** Shubham Choudhary  
**Role:** Data Analyst

