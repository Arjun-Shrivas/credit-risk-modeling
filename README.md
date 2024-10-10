# 🏦 Credit Risk Modeling

## Overview
This project focuses on enhancing the credit score calculation process by introducing key financial metrics and aggregating customer financial data over different timeframes. These features help better assess credit risk and provide a more detailed understanding of customer creditworthiness, which is crucial in the **fintech industry**.

The project introduces a **Hypothetical Credit Score Calculation** based on various financial features, designed specifically for **fintech companies** to improve lending decisions, risk management, and customer segmentation.

---

## 🚀 Key Features
### 1. Hypothetical Credit Score Calculation
A dynamic feature created to provide a comprehensive view of a customer’s financial health by calculating:
- **Debt-to-Income Ratio (DTI)**
- **Total Financial Accounts**
- **Total Savings**

These metrics are particularly important in the **fintech domain**, where they enable more precise risk assessments and help provide personalized financial products.

### 2. Scaled Credit Score Aggregation
- **Scaled_Credit_Score_3m**: Tracks customer credit score trends over the last 3 months.
- **Scaled_Credit_Score_6m**: Tracks customer credit score trends over the last 6 months.
- This feature allows fintech companies to assess both short-term and long-term credit risk.

---

## 📊 Case Study: Hypothetical Credit Score Calculation

### Key Metrics Involved:
1. **📉 Debt-to-Income Ratio (DTI)**
   - **Definition**: The ratio of a customer’s total monthly debt payments to their monthly income.
   - **Relevance in Fintech**: Lower DTI indicates reduced risk of default, making it essential for lenders when evaluating borrowing capacity.

2. **💼 Total Financial Accounts**
   - **Definition**: Total number of financial accounts, including savings accounts, credit cards, and loans.
   - **Relevance in Fintech**: Customers with more accounts and positive histories may be viewed as more financially responsible.

3. **💰 Total Savings**
   - **Definition**: Total savings a customer has across various financial instruments.
   - **Relevance in Fintech**: More savings provide a financial cushion, signaling lower credit risk.

---

## 🧑‍💻 Steps Followed
1. **Data Collection**: Collected financial data for each customer, including monthly debt, income, and payment history.
2. **Data Preprocessing**: Cleaned and normalized the data to ensure consistency and accuracy.
3. **Feature Engineering**:
   - **Debt-to-Income Ratio**: Calculated based on the monthly debt and income data.
   - **Total Financial Accounts**: Aggregated the number of financial accounts held by each customer.
   - **Total Savings**: Derived from various customer savings accounts.
4. **Hypothetical Credit Score Calculation**: Created a dynamic credit scoring model based on these features.
5. **Aggregation**: Computed **Scaled_Credit_Score_3m** and **Scaled_Credit_Score_6m** for trend analysis.
6. **Visualization**: Produced plots and summary statistics for better insights.

---

## 📈 Results Summary

| Customer_ID | Name              | Timeframe        | Scaled_Credit_Score_3m | Scaled_Credit_Score_6m |
|-------------|-------------------|------------------|------------------------|------------------------|
| CUS_0x21b1  | Rick Rothackerj    | First 3 months   | 850.00                 | 850.00                 |
| CUS_0x21b1  | Rick Rothackerj    | Last 3 months    | 850.00                 | 850.00                 |
| CUS_0x2dbc  | Langep            | First 3 months   | 300.00                 | 300.00                 |
| CUS_0x2dbc  | Langep            | Last 3 months    | 300.00                 | 300.00                 |
| CUS_0xd40   | Aaron Maashoh      | First 3 months   | 753.95                 | 516.99                 |
| CUS_0xd40   | Aaron Maashoh      | Last 3 months    | 753.95                 | 516.99                 |

### Insights:
- **Customer 1** consistently maintains high scores across both 3- and 6-month periods, reflecting excellent financial health and low credit risk.
- **Customer 2** shows low scores, indicating potential financial distress or high-risk factors.
- **Customer 3** has fluctuating scores between the 3- and 6-month periods, possibly due to inconsistent financial behavior or changes in payment history.

---

## 📢 Recommendations

1. **For Low-Scoring Customers**:
   - **Financial Counseling**: Encourage counseling to help improve debt management and overall financial health.
   - **Structured Repayment Plans**: Suggest implementing structured payment plans to manage debt more effectively.

2. **For High-Scoring Customers**:
   - **Offer Premium Products**: Consider offering premium financial products to customers with high scores.
   - **Incentive Programs**: Provide incentives to encourage continued financial responsibility.

3. **For Customers with Fluctuating Scores**:
   - **Monitor Payment Consistency**: Help stabilize payment behavior to avoid score fluctuations.
   - **Credit Education**: Provide education on maintaining a low credit utilization ratio and improving savings.

---

## 💼 Relevance to the Fintech Domain
In the fintech domain, accurately assessing creditworthiness is critical for risk management, lending decisions, and customer segmentation. The **Hypothetical Credit Score Calculation** feature introduces important financial metrics, such as **Debt-to-Income Ratio**, **Total Financial Accounts**, and **Total Savings**, that allow fintech companies to:
- **Improve Credit Risk Models**: Create more accurate, data-driven models to predict credit risk.
- **Personalize Financial Products**: Tailor products to customers based on their unique financial profiles.
- **Optimize Lending Decisions**: Make more informed decisions by leveraging comprehensive financial data.

---

## 📚 Conclusion
The **Credit Risk Modeling** project integrates essential financial metrics into a comprehensive credit scoring model. This approach enhances the credit risk assessment process, making it more reliable for fintech companies to evaluate customer financial health, manage risk, and offer tailored financial products. The features developed in this project align closely with real-world fintech practices, offering a significant improvement over traditional credit scoring models.

Feel free to explore the project, and let's connect if you'd like to discuss any aspects in more detail!

---
