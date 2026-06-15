# Bank Customer Complaint Analytics

## Table of Contents

1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Dataset Description](#dataset-description)
4. [Tools & Technologies](#tools--technologies)
5. [Project Methodology](#project-methodology)
6. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
7. [Hypothesis Testing](#hypothesis-testing)
8. [Dashboard Overview](#dashboard-overview)
9. [Dashboard Pages](#dashboard-pages)
10. [Key Insights Visualized](#key-insights-visualized)
11. [Results & Business Conclusions](#results--business-conclusions)
12. [How to Run](#how-to-run)
13. [Future Enhancements](#future-enhancements)

---

## Project Overview

A data analytics project focused on understanding customer complaint behaviour, identifying major complaint drivers, evaluating service performance, and assessing geographic complaint concentration within the banking sector.
Using SQL (SQLite), Python, and Power BI, the project applies a hypothesis-driven analytical framework to transform customer complaint data into actionable business insights and interactive dashboards.

Business Problem
Customer complaints provide valuable insight into service quality and customer experience. However, large volumes of complaint records make it difficult to identify recurring issues, monitor response performance, and prioritize operational improvements.
This project aims to answer key business questions:
•	Which products generate the most complaints?
•	What issues drive customer dissatisfaction?
•	How effective is complaint handling performance?
•	Are operational bottlenecks present?
•	Which geographic regions require attention?
## Dataset Description

Dataset: Bank of America Customer Complaints

The dataset contains customer complaint records across multiple banking products and services, including complaint dates, products, issues, sub-issues, response status, and geographic information.

Key Fields:
- Complaint ID
- Date Submitted
- Date Received
- Product
- Issue
- Sub-Issue
- State
- Timely Response
- Submitted Via

## Tools & Technologies

- SQL (SQLite)
- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- Power BI
- Microsoft Excel

## Project Methodology

Data Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Hypothesis Testing
↓
Dashboard Development
↓
Business Insights

## Key Performance Indicators

- Total Complaints
- Timely Response Rate
- Delayed Response Rate
- Missing Response Rate
- Top State Contribution %
- Top 5 States Contribution %
- Product Complaint Share %

## Hypothesis Testing

| Hypothesis | Result |
|------------|---------|
| Product Complaint Distribution | Supported H1 |
| Issue Concentration | Supported H1 |
| Response Performance | Supported H0 |
| Product-Level Operational Performance | Supported H0 |
| Geographic Concentration | Supported H1 |

## Dashboard Overview

Four interactive Power BI dashboards were developed to support executive reporting, root cause analysis, operational performance evaluation, and geographic risk assessment.
## Dashboard Pages

### Dashboard 1 – Executive Overview
- Complaint trends
- Product distribution
- Response performance
- Interactive slicers

### Dashboard 2 – Root Cause Analysis
- Product → Issue → Sub-Issue analysis
- Drill-down investigation
- Customer pain point identification

### Dashboard 3 – Service Performance & Response Effectiveness
- Timely vs delayed responses
- Product-level SLA analysis
- Complaint handling performance

### Dashboard 4 – Geographic Risk & Regional Concentration
- State-level complaint distribution
- Geographic hotspots
- Regional concentration analysis
## Screenshots

### Dashboard 1 – Executive Overview
![Dashboard 1](images/Dashboard1(Executive Summary).png)

### Dashboard 2 – Root Cause Analysis
![Dashboard 2](images/Dashboard2(Product & Root Cause Analysis).png)

### Dashboard 3 – Service Performance & Response Effectiveness
![Dashboard 3](images/Dashboard3(Service Performance & Response Effectiveness).png)

### Dashboard 4 – Geographic Risk & Regional Concentration
![Dashboard 4](images/Dashboard4(Geographic Risk & Regional Complaint Concentration).png)

## Key Insights Visualized

- Top three products accounted for approximately 77.9% of all complaints.
- Customer dissatisfaction was concentrated within a small number of recurring issues and sub-issues.
- 93.77% of complaints received timely responses.
- Product-level response performance remained above 90% across all major banking products.
- The top five states contributed more than 40% of total complaints.
- California alone accounted for approximately 21.9% of all complaints.

## Results & Business Conclusions

The analysis revealed that complaint activity is concentrated within a small number of products, recurring issues drive the majority of customer dissatisfaction, and complaint volume is geographically clustered within specific states. While overall response performance remains strong, opportunities exist to further improve operational efficiency and customer service processes.

## How to Run

1. Clone the repository.
2. Open SQL scripts for data analysis.
3. Run Python notebooks for data preparation and exploratory analysis.
4. Open the Power BI (.pbix) file to explore dashboards.

## Future Enhancements

- Incorporate customer sentiment analysis using NLP.
- Develop predictive models for complaint volume forecasting.
- Integrate external economic and demographic datasets.
- Build automated refresh pipelines for real-time monitoring.
