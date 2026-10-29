# Banking Loan & Credit Risk Analytics Dashboard

## 1. Introduction

The Banking Loan & Credit Risk Analytics Dashboard is an interactive Power BI project designed to analyze loan portfolios, evaluate credit risk, track loan defaults, and monitor loan repayment performance. It helps users understand loan distribution, identify default patterns, and analyze payment collections through interactive visualizations.

## 2. Objectives

- Analyze the overall loan portfolio and total loan amount.
- Understand loan distribution across different loan types.
- Compare loan amounts across different loan types and tenures.
- Monitor loan statuses and identify defaulted loans.
- Analyze credit scores and default patterns across employment types.
- Track monthly loan collections and payment statuses.
- Understand loan repayment activity using payment details.

## 3. Tools and Technologies Used

- **Power BI:** For data visualization and interactive dashboard development.
- **Power Query:** For data cleaning and transformation.
- **DAX (Data Analysis Expressions):** For creating measures and performing calculations.
- **CSV Files:** For storing and importing datasets.

## 4. Dataset Description

The project uses three datasets to analyze customers, loans, and repayment activities.

- **customers.csv:** Contains customer-related information used for customer and credit score analysis.
- **loans.csv:** Contains loan-related information used to analyze loan amounts, loan types, tenure, loan status, and defaults.
- **payments.csv:** Contains payment-related information used to analyze payment dates, due dates, paid amounts, and payment statuses.


## 5. Methodology

1. **Data Collection:** Imported customer, loan, and payment datasets into Power BI.
2. **Data Cleaning:** Checked data types, missing values, duplicate records, and data consistency using Power Query.
3. **Data Modeling:** Created relationships between customer, loan, and payment tables using the relevant IDs.
4. **Data Analysis:** Created DAX measures to calculate key metrics such as total loans, total loan amount, average loan amount, and defaulted loans.
5. **Data Visualization:** Developed interactive charts and KPI cards to analyze loan portfolio performance, credit risk, and repayment activity.

## 6. Dashboard Visualizations

The dashboard contains two main pages designed to analyze loan portfolio performance, credit risk, and loan repayment activity.

### Page 1: Loan Portfolio Overview

**Key Performance Indicators (KPIs)**

- **Average Loan Amount Card:** Displays the average amount per loan.
- **Total Loan Amount Card:** Displays the combined value of all loans.
- **Total Loans Card:** Displays the total number of loans.

**Charts**

- **Loan Distribution by Type:** Shows the distribution of loans across different loan types.
- **Loan Amount by Type:** Compares the total loan amount across different loan types.
- **Total Loan Amount by Loan Tenure:** Compares total loan amounts across different loan tenure periods.
- **Loan Status Distribution:** Shows the distribution of loans by status.

### Page 2: Credit Risk & Payment Analysis

**Key Performance Indicators (KPIs)**

- **Average Credit Score Card:** Displays the average credit score of borrowers.
- **Defaulted Loans Card:** Displays the total number of loans that are in default.

**Charts**

- **Defaults by Employment Type:** Compares the number of defaulted loans across employment categories.
- **Monthly Loan Collections:** Shows the total paid amount by month using payment dates.
- **Payment Status Distribution:** Displays the distribution of payments by payment status.
- **Defaults by Loan Type:** Compares the number of defaulted loans across different loan types.
- **Loan Repayment Details:** Presents loan repayment information, including due dates, payment dates, paid amounts, and payment statuses.

These visualizations help users explore loan portfolio performance, identify default patterns, monitor payment collections, and understand repayment activity.

## 7. Results and Insights

The dashboard helps users:

- Understand the overall loan portfolio and total loan exposure.
- Identify the most common loan types and compare loan amounts.
- Analyze loan status distribution and monitor defaulted loans.
- Compare loan defaults across employment types and loan categories.
- Track monthly payment collections and understand payment status distribution.
- Review repayment details to support better loan monitoring and credit risk analysis.


## 8. Conclusion

The Banking Loan & Credit Risk Analytics Dashboard provides an interactive view of loan portfolio performance, credit risk, and repayment activities. By combining customer, loan, and payment data, the project demonstrates how Power BI can be used to transform raw data into meaningful insights that support loan monitoring and risk analysis.

## 9. Project Files

- `customers.csv` — Customer dataset.
- `loans.csv` — Loan dataset.
- `payments.csv` — Payment dataset.
- `.pbix` file — Power BI dashboard project.
- `README.md` — Project documentation.

## 📊 Dashboard Preview

### 1. Loan Portfolio Overview
![Loan Portfolio Overview](<Loan Portfolio Overview.png>)

### 2. Credit Risk and Payment Analysis
![Credit Risk and Payment Analysis](<Credit Risk & Payment Analysis.png>)


## 10. References

- [Microsoft Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [Microsoft DAX Documentation](https://learn.microsoft.com/en-us/dax/)
- [Microsoft Power Query Documentation](https://learn.microsoft.com/en-us/power-query/)
