# Finance KPI & Budget Performance Dashboard

## 📊 Project Overview

The **Finance KPI & Budget Performance Dashboard** is an interactive Power BI project developed to analyze financial transaction data and provide a clear overview of an organization's budget and actual expenditure.

The dashboard compares **Budget Amount** with **Actual Amount** and helps identify budget variances across different departments, categories and regions. It also provides insights into transaction patterns based on different payment methods.

The main goal of this project is to transform raw financial data into meaningful visual insights that can support better financial monitoring and decision-making.

---

## 🎯 Problem Statement

Organizations often have large amounts of financial transaction data, but raw data can be difficult to interpret and analyze effectively.

This project focuses on developing an interactive Power BI dashboard that helps management:

* Monitor overall budget allocation and actual expenditure.
* Compare budgeted amounts with actual spending.
* Identify budget variances.
* Analyze expenditure across different departments.
* Understand category-wise spending.
* Analyze transaction distribution by payment method.
* Compare financial performance across different years and regions.

---

## 📁 Dataset

The dataset contains **10,010 financial transaction records**.

### Dataset Columns

| Column         | Description                                |
| -------------- | ------------------------------------------ |
| Date           | Date of the financial transaction          |
| Department     | Department associated with the transaction |
| Category       | Category of expenditure                    |
| Region         | Region associated with the transaction     |
| Budget Amount  | Amount allocated as budget                 |
| Actual Amount  | Actual amount spent                        |
| Payment Method | Method used for the transaction            |
| Transaction ID | Unique identifier for each transaction     |

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query**
* **Microsoft Excel**
* Data Visualization
* Financial KPI Analysis

---

## 🔄 Project Methodology

### 1. Data Collection

The finance transaction dataset containing 10,010 records was obtained for analysis.

### 2. Data Import

The dataset was imported into Microsoft Power BI Desktop using the **Get Data** option.

### 3. Data Cleaning

The dataset was checked for:

* Missing values
* Data type inconsistencies
* Incorrect date formats
* Numerical data formatting
* Unnecessary fields

The Date, Budget Amount and Actual Amount fields were verified and prepared for analysis.

### 4. Data Modeling

DAX measures were created to calculate important financial KPIs such as:

* Total Budget
* Total Actual Amount
* Budget Variance
* Average Budget
* Average Actual Amount
* Total Transactions

### 5. Dashboard Development

Different Power BI visualizations were used to present the financial analysis in an interactive format.

---

## 📐 DAX Measures

### Total Budget

```DAX
Total Budget =
SUM('Sheet1'[Budget Amount])
```

### Total Actual Amount

```DAX
Total Actual Amount =
SUM('Sheet1'[Actual Amount])
```

### Budget Variance

```DAX
Budget Variance =
SUM('Sheet1'[Actual Amount]) -
SUM('Sheet1'[Budget Amount])
```

### Average Budget

```DAX
Average Budget =
AVERAGE('Sheet1'[Budget Amount])
```

### Average Actual Amount

```DAX
Average Actual Amount =
AVERAGE('Sheet1'[Actual Amount])
```

### Total Transactions

```DAX
Total Transactions =
COUNTROWS('Sheet1')
```

---

## 📈 Dashboard Visualizations

The dashboard includes the following visualizations:

### 1. Annual Budget and Actual Expenditure Comparison

A clustered column chart is used to compare the total budget with actual expenditure across different years.

### 2. Actual Expenditure by Category

A donut chart shows how actual expenditure is distributed across different expenditure categories.

### 3. Department-wise Budget Variance Analysis

A waterfall chart is used to analyze the contribution of different departments to the overall budget variance.

### 4. Transaction Distribution by Payment Method

A pie chart shows the distribution of transactions across payment methods such as:

* UPI
* Card
* Cash
* Bank Transfer

### 5. Category-wise Actual Expenditure

A treemap represents the actual expenditure across different categories, making it easier to identify high-spending categories.

### 6. Department-wise Financial Performance

A matrix provides a detailed comparison of:

* Total Actual Amount
* Total Budget
* Budget Variance

for different departments.

### 7. Interactive Filters

The dashboard contains slicers for:

* Date
* Region
* Category
* Payment Method

These filters allow users to perform focused analysis on specific parts of the dataset.

---

## 💡 Key Insights

The dashboard helps identify:

* Differences between allocated budgets and actual expenditure.
* Departments with significant budget variances.
* Categories contributing the most to total expenditure.
* Transaction distribution across different payment methods.
* Changes in financial expenditure across different years.
* Regional spending patterns.
* Areas where actual expenditure may require further financial review.

---

## 📊 Dashboard Preview

*Add your Power BI dashboard screenshot here.*

```text
Finance KPI & Budget Performance Dashboard
```

---

## 🚀 Project Outcome

The project successfully converts raw financial transaction data into an interactive financial analysis dashboard.

The dashboard provides management with a centralized view of **budget allocation, actual expenditure and budget variance**, making it easier to monitor financial performance and identify areas that require attention.

It demonstrates the use of **Power BI, DAX, data cleaning, KPI development and interactive data visualization** for financial analysis.

---

## 🔮 Future Enhancements

The dashboard can be further improved by adding:

* Budget Utilization Percentage
* Year-over-Year Growth Analysis
* Drill-through pages
* Department-level detailed reports
* Conditional formatting for positive and negative variance
* Forecasting of future expenditure
* Automated data refresh
* Additional financial KPIs

---

## 👨‍💻 Author

**Maharshi Goswami**

**Project:** Finance KPI & Budget Performance Dashboard
**Tool:** Microsoft Power BI

---

## 🔗 GitHub Repository

**GitHub:**
Add your actual GitHub repository link here.

