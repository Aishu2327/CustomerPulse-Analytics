# CustomerPulse Analytics

## Customer Segmentation & RFM Analytics for Asian Markets

CustomerPulse Analytics is a customer segmentation and business analytics project that uses **RFM (Recency, Frequency, Monetary) analysis** to understand customer purchasing behavior and identify high-value, loyal, and at-risk customers.

The project combines **Python/Jupyter Notebook** for data processing and RFM analysis with **Power BI** for interactive visualization and business insights.

## Problem Statement

Businesses have customers with different purchasing behaviors. Treating every customer the same can lead to ineffective marketing and retention strategies.

This project analyzes customer transaction data from Asian markets and segments customers based on:

* **Recency** – How recently a customer purchased
* **Frequency** – How often a customer purchased
* **Monetary** – How much a customer spent

The goal is to identify valuable customer groups and provide actionable insights for customer retention and targeted marketing.

## Project Workflow

```text
Raw Sales Data
      ↓
Data Cleaning & Preparation
      ↓
RFM Feature Engineering
      ↓
RFM Scoring
      ↓
Customer Segmentation
      ↓
RFM_Asia.csv
      ↓
Power BI Dashboard
      ↓
Business Insights
```

## Tech Stack

### Data Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Matplotlib
* PyCountry

### Business Intelligence

* Microsoft Power BI
* Power BI Desktop

### Development Tools

* VS Code
* Git
* GitHub

## Project Structure

```text
CustomerPulse-Analytics/
│
├── dashboards/
│   └── CustomerPulse-Analytics.pbix
│
├── Customer_Segmentation_Asia.ipynb
│
├── RFM_Asia.csv
│
├── sales_asia.csv
│
├── README.md
│
└── RFM_Analysis.png
```

## RFM Analysis

RFM analysis evaluates customers using three important behavioral metrics:

| Metric    | Meaning                                  |
| --------- | ---------------------------------------- |
| Recency   | Days since the customer's last purchase  |
| Frequency | Number of purchases made by the customer |
| Monetary  | Total amount spent by the customer       |

Each RFM dimension is scored using a **1–5 scoring approach**. These scores are combined to create an overall RFM score, which is then used to classify customers into behavioral segments.

## Customer Segments

The analysis identifies multiple customer behavior groups:

* Champions
* Loyal Customers
* Potential Loyalists
* New Customers
* Promising
* Need Attention
* At Risk
* Can't Lose
* Hibernating
* Lost
* About to Sleep

These segments convert numerical RFM scores into meaningful business categories.

## Power BI Dashboard

The Power BI dashboard provides an interactive view of customer behavior and segment performance.

### KPI Cards

The dashboard includes:

* Total Customers
* Total Monetary Value
* Average Recency
* Average Frequency

### Customer Distribution

A donut chart shows the number of customers belonging to each RFM segment.

### RFM Scatter Plot

The scatter plot visualizes customer behavior using:

* Recency
* Frequency
* Monetary value
* Customer segment

This helps identify behavioral patterns across customer groups.

### Revenue by Customer Segment

A treemap compares the monetary contribution of different customer segments and highlights which customer groups generate the most revenue.

### Country Slicer

A country slicer allows users to filter the dashboard by individual Asian markets and analyze customer behavior at the country level.

## Current Dashboard Summary

The Power BI dashboard currently shows approximately:

* **16.57K customers**
* **358.38M total monetary value**
* **118.33 average recency**
* **7.52 average frequency**

The dashboard metrics update when country filters are applied.

## Business Insights

The analysis can help businesses identify:

1. High-value customers who contribute significantly to revenue.
2. Loyal customers who purchase frequently.
3. Customers whose activity is declining.
4. At-risk customers who may require re-engagement.
5. Lost customers who may be targeted through win-back campaigns.
6. Differences in customer behavior across Asian countries.
7. Revenue concentration across customer segments.

## Business Recommendations

### Champions

Reward high-value customers with loyalty benefits, exclusive offers, and early access to products.

### Loyal Customers

Use loyalty programs and personalized recommendations to maintain engagement.

### Potential Loyalists

Encourage repeat purchases through targeted promotions and personalized recommendations.

### At Risk / Can't Lose

Prioritize these customers with personalized offers and re-engagement campaigns.

### Hibernating / Lost

Use targeted win-back campaigns while controlling marketing costs.

## Author

Aishwarya Rustagi

B.Tech Biotechnology | Data Analytics & Machine Learning Enthusiast
