# Customer Segmentation using RFM Analysis

## Project Overview

This project analyzes customer purchasing behavior using **RFM (Recency, Frequency, Monetary) segmentation** to identify high-value customers, improve retention strategies, and drive revenue growth.

The analysis is supported by an interactive **Power BI dashboard** and Python-based data processing.

---

## Business Problem

Businesses often struggle to:

* Identify their most valuable customers
* Reduce customer churn
* Allocate marketing budgets efficiently

This project addresses these challenges by segmenting customers based on behavioral patterns and providing actionable insights.

---

## Dataset

This project uses the **Online Retail dataset** from the UCI Machine Learning Repository, which contains transactional data for a UK-based online retail store.

- Source: [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Time Period: 2010–2011
- Features: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

> Note: The original dataset is not included in this repository due to GitHub file size limitations. A cleaned and processed dataset is available in the `output/` folder for analysis and dashboarding.

> Data preprocessing includes handling missing values, removing cancellations/returns, and feature engineering for customer and campaign analysis.

---

## Tools & Technologies

* **Python** (Pandas, NumPy)
* **Jupyter Notebook**
* **Power BI**
* Data Visualization & Statistical Analysis

---

## Methodology

### 1. Data Cleaning & Preparation

* Removed missing and duplicate values
* Filtered invalid transactions
* Created customer-level aggregation

### 2. RFM Calculation

* **Recency** → Days since last purchase
* **Frequency** → Number of transactions
* **Monetary** → Total spending

### 3. Customer Segmentation

Customers were grouped into segments such as:

* Champions
* Loyal Customers
* Promising
* At Risk
* Lost

### 4. Advanced Analysis

* Cohort Retention Analysis
* Customer Lifetime Value (CLV)
* Pareto (80/20) Revenue Analysis

---

## Key Insights

* **Champions contribute ~72% of total revenue**, making them the most critical segment
* Revenue shows strong **seasonality with a peak in November**
* **Retention drops significantly after first purchase**, highlighting a key intervention point
* **Promising customers** represent a major growth opportunity
* Revenue is highly concentrated among a small group of top customers (Pareto principle)

---

## Dashboard Preview

Images/customer_analytics_dashboard_preview.png



---

## Business Recommendations

* Prioritize retention strategies for **Champions**
* Introduce **post-purchase engagement campaigns**
* Target **Promising customers** with personalized offers
* Optimize inventory and marketing for **peak seasonal demand**
* Diversify customer base to reduce geographic dependency

---

## Project Structure

```
rfm-customer-segmentation/
│
├── rfm_customer_segmentation.ipynb    # notebook
│
├── customer_analytics_dashboard.pdf   # dashboard
│
├── dashboard_preview.png
│
|── requirements.txt
│
└── README.md
```

## Conclusion

This project demonstrates how data-driven segmentation can significantly improve customer retention, revenue optimization, and strategic decision-making.

---

## Author

**Ayshi Mitra**
Aspiring Data Analyst
