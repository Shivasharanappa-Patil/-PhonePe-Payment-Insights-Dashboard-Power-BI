# 📱 PhonePe Payment Insights Dashboard | Power BI

An interactive digital payments analytics project built using Microsoft Power BI to analyze transaction performance, payment success rates, customer segments, service contributions, and usage patterns.

## 🎯 Business Problem

Digital payment data can reveal valuable information about transaction activity, payment outcomes, customer behavior, and service-level performance.

The objective of this project is to transform transaction and user data into an interactive dashboard that helps users monitor payment KPIs, compare transaction trends, explore customer segments, and evaluate service-wise transaction value.

## 📂 Dataset Overview

The supplied Excel workbook, `Phonepe-Final-Dataset.xlsx`, contains two worksheets:

**1. All_Users**
- User ID
- Name
- Age
- Join Date

**2. All_Transactions**
- Transaction ID
- Transaction Amount
- User ID
- Service and Service Type
- Payment Status and Reason
- Transaction Date

**Dataset scale:** 107,658 user records and 300,000 transaction records.

**Transaction period:** January 1 to December 30, 2024.

The original dataset publisher and collection methodology have not yet been verified. The dashboard is PhonePe-themed; this does not establish that the workbook contains official PhonePe production data.

## 🛠️ Tools & Technologies

- **Microsoft Power BI:** Interactive dashboard development and visualization
- **Power Query:** Data inspection, transformation, and preparation
- **DAX:** KPI calculations and analytical measures
- **Microsoft Excel:** Dataset inspection and supporting data preparation
- **Excel workbook:** Source dataset containing user and transaction records

## 🔄 Project Workflow

1. Inspected the user and transaction worksheets.
2. Examined data completeness, duplicate records, identifiers, dates, and numeric fields.
3. Checked the relationship between transaction records and user IDs.
4. Prepared the data for Power BI reporting.
5. Developed KPI cards, transaction trend charts, service comparisons, and customer-segment visualizations.
6. Added interactive month and payment-status filters.
7. Explored transaction activity, payment outcomes, and service-level contributions.

## 📊 Dashboard Features

### 1. Key Performance Indicators
- Total transactions
- Total transaction value
- Unique users
- Successful payment rate
- Month-over-month growth

### 2. Transaction Trend Analysis
Compare monthly transaction counts and transaction values over the reporting period.

### 3. Payment Status Analysis
Explore successful and unsuccessful payment outcomes, including failed transactions, wrong PIN, server errors, and insufficient amount.

### 4. Customer Age-Segment Analysis
Examine the distribution of users or transaction activity across age groups, depending on the measure used in the dashboard.

### 5. Service Transaction Value Analysis
Compare transaction values across Money Transfer, Loans, Insurance, and Recharge & Bills.

### 6. Top Users by Transaction Value
Identify users with the highest transaction values within the selected reporting context.

### 7. Weekday vs. Weekend Analysis
Compare payment activity across weekdays and weekends.

### 8. Interactive Filtering
Use month and payment-status controls to explore the available data.

## 💡 Data-Verified Observations

- The workbook contains 300,000 transaction records and 107,658 user records.
- The transaction data covers January through December 2024, ending on December 30.
- February 2024 contains 24,040 transactions with a total transaction value of approximately 278.88 million in the dataset's unspecified currency.
- The February successful payment rate is approximately 96.06%, calculated as successful transactions divided by all transactions in that month.
- The transaction table includes four main service categories and 16 service types.

These findings describe the supplied workbook. They should not be interpreted as verified official PhonePe business statistics.

## 📚 Key Learnings

- Inspecting and validating multi-sheet datasets
- Preparing data for business intelligence reporting
- Developing interactive Power BI dashboards
- Designing KPI cards and trend visualizations
- Comparing service and customer segments
- Communicating data findings through visual storytelling

## ⚠️ Limitations

- The dataset's original publisher and provenance remain unverified.
- The currency and exact business definitions of some metrics are not documented.
- Payment-status percentages depend on the selected date range and denominator.
- Observed patterns do not establish the causes of failed transactions or customer behavior.
- Results should not be generalized to PhonePe's actual platform without independently verified data.
  
## 🖼️ Final Dashboard Preview - https://github.com/Shivasharanappa-Patil/-PhonePe-Payment-Insights-Dashboard-Power-BI/blob/main/Screenshot%202026-10-18%20000647.png

## 👨‍💻 Author

**Shivasharanappa Patil**

Aspiring Data Analyst | Power BI | DAX | Power Query | Excel

This project demonstrates practical application of data preparation, KPI reporting, and interactive visualization to a digital payments analytics use case.
