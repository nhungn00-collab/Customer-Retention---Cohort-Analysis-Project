# Customer Retention & Cohort Analysis

Most customers make purchases only within their first month, indicating a generally low retention rate. 
However, a small group of customers demonstrates consistently high transaction frequency and long-term engagement, representing high-value VIP segments.

Additionally, some customers generate high transaction volume within a short period but fail to return afterward, suggesting potential loss of valuable bulk or campaign-driven customers.

This project analyzes customer retention behavior using cohort analysis techniques to evaluate customer loyalty, retention trends, and acquisition effectiveness.

## Overview
- Analyzed customer purchase behavior over time
- Evaluated retention rates across monthly customer cohorts
- Identified high-value customer groups and retention patterns


## Objectives
- Measure customer retention over time
- Identify high-quality customer cohorts
- Evaluate effectiveness of customer acquisition
- Support retention strategy and CRM decisions


## Key Insights

### Declining New Customer Acquisition
- The number of new customers decreases over time
- Recent acquisition campaigns may not be performing effectively

### Strong Retention in November 2011
- November 2011 shows the highest customer retention rate
- Existing loyalty or customer engagement programs likely performed well during this period

### Highest-Quality Customer Cohort
- Customers acquired in December 2010 demonstrate the strongest long-term retention
- Average repeat purchase rate remains around 35–50%, significantly higher than other cohorts (15–30%)

## Business Impact
The analysis helps businesses:
- Improve customer retention strategies
- Optimize acquisition campaigns
- Identify high-value customer segments
- Enhance loyalty and engagement programs

## Customer Behavior Analysis

Customers were segmented based on:
- Recency of activity (`last_active_month`)
- Transaction frequency (`num_transactions`)

### Key Customer Segments
- **One-time buyers**: Purchased once and churned immediately
- **VIP customers**: Long-term active customers with high transaction frequency
- **Bulk buyers**: High-volume short-term customers with low retention
- **Super VIP customers**: Extremely loyal customers contributing significant transaction activity over time

### Business Insight
A small number of highly loyal customers generate substantial long-term value, while most customers churn early.  
This indicates the need for stronger retention and loyalty strategies.

## Recommendations
- Investigate successful retention strategies implemented in November 2011
- Analyze characteristics of high-retention cohorts for replication
- Improve acquisition campaign effectiveness
- Focus on long-term customer value rather than short-term acquisition volume

## Tools Used
- Python (Pandas, Cohort Analysis)
- Matplotlib / Seaborn
- Data Visualization

## Project Files
- `.ipynb` – Python analysis notebook
- `.pdf` – Full report
- `.html` – Project website

## Project Website: https://nhungn00-collab.github.io/Customer-Retention---Cohort-Analysis-Project/

