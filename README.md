# Marketing Campaign Performance Analysis

## Project Overview

This project analyzes an 8,000-customer marketing campaign dataset to understand which campaign characteristics and customer behaviors are most associated with conversion.

I used **Excel** for data preparation and validation and **Tableau** for analysis, visualization, and dashboard development.

## Business Question

> What factors in our marketing campaigns and customer behavior are most associated with conversion, and where should a marketing team focus its attention?

The analysis examines:

- Campaign channel
- Campaign type / objective
- Ad spend
- Website engagement
- Email engagement
- Customer age group

## Data Source

The raw dataset was sourced from Kaggle:

**Digital Marketing Campaign Dataset — Kaggle**  
https://www.kaggle.com/datasets/rabieelkharoua/predict-conversion-in-digital-marketing-dataset

The dataset contains **8,000 customer records and 20 variables**, including demographic information, campaign characteristics, advertising spend, website and email engagement, and conversion outcomes.

The Kaggle dataset is listed under the **CC BY 4.0** license. The analysis and dashboard in this repository are my own work based on the source dataset.

## Tools Used

- **Microsoft Excel** — data cleaning and validation
- **Tableau** — exploratory analysis, calculated fields, visualization, dashboard development, and interactive filters

## Data Preparation

Before building the Tableau dashboard, I reviewed the dataset in Excel and:

- Checked for duplicate records
- Checked for missing values
- Reviewed data types
- Standardized text fields where needed
- Reviewed the dataset structure and fields used for analysis

## Key Findings

### 1. Overall Performance

- **8,000 customers** were included in the dataset.
- **7,012 total conversions** were recorded.
- Overall conversion rate shown on the dashboard: **87.65%**.
- Average ad spend: **$5,000.94**.

### 2. Campaign Channel Has Limited Impact

Average conversion rates were tightly clustered across the five campaign channels, roughly in the **86%–88%** range.

**Takeaway:** Campaign channel alone does not appear to create a large difference in conversion in this dataset.

### 3. Campaign Type Shows the Clearest Difference

Conversion-type campaigns averaged **93.36%** conversion, compared with approximately **85.56%** for awareness and consideration campaigns — an approximately **8-percentage-point gap**.

**Takeaway:** Campaign type / objective appears to be a stronger differentiator than campaign channel.

### 4. Conversion Increases Around the $5,000 Spend Level

Using $1,000 ad-spend bands, the analysis showed a noticeable step around the $5,000 level: conversion was approximately **83% below $5K** and approximately **92% at or above $5K**.

**Important:** This is an observed association, not proof that increasing ad spend causes conversion to rise.

### 5. Converted Customers Show Stronger Website Engagement

Converted customers had higher average website engagement:

- Average time on site: approximately **8 vs. 6**
- Average website visits: approximately **16 vs. 12**
- Average pages per visit: approximately **5.5 vs. 4.8**

**Takeaway:** Higher website engagement is associated with conversion in this dataset.

### 6. Converted Customers Engage More With Email

Converted customers averaged approximately **9.5 email opens** and **4.0 email clicks**, compared with approximately **7.5 opens** and **3.5 clicks** among non-converted customers.

**Takeaway:** Email engagement is also associated with conversion.

### 7. Age Has Relatively Little Effect

Conversion rates were relatively stable across age groups:

| Age Group | Conversion Rate |
|---|---:|
| 18–24 | 86.13% |
| 25–34 | 87.31% |
| 35–44 | 89.59% |
| 45–54 | 87.10% |
| 55+ | 87.59% |

**Takeaway:** Age does not appear to be a strong standalone explanation for conversion.

## Dashboard

The final Tableau dashboard brings the analysis together using KPI cards, comparison charts, engagement analysis, ad-spend analysis, age-group analysis, and interactive filters.

### Dashboard Preview
<img width="1440" height="900" alt="Marketing Campaign Performance Dashboard" src="https://github.com/user-attachments/assets/9e732778-fc0f-41cb-9ec7-c35ee966bded" />

The completed dashboard includes:

- KPI cards for total customers, total conversions, overall conversion rate, and average ad spend
- Conversion rate by campaign channel
- Conversion rate by campaign type / objective
- Ad-spend bands showing the $5,000 step
- Website engagement comparison between converted and non-converted customers
- Email engagement comparison
- Conversion rate by age group
- Interactive filters for campaign type, age group, and gender

## Analytical Approach

1. Started with the business question rather than immediately building visualizations.
2. Prepared and validated the dataset in Excel.
3. Loaded the prepared data into Tableau and reviewed the available dimensions and measures.
4. Built individual worksheets to examine conversion from multiple perspectives.
5. Compared campaign channel and campaign type / objective.
6. Compared website and email behavior between converted and non-converted customers.
7. Examined ad spend using both a scatter plot and spend bands.
8. Compared conversion across age groups.
9. Selected the strongest findings and organized them into an interactive dashboard.
10. Added filters so a stakeholder can explore different customer and campaign segments.

## Business Implications

The analysis suggests that campaign type / objective and customer engagement deserve more attention than channel or age when investigating conversion performance. However, the findings should be treated as associations rather than causal conclusions.

Before making a major marketing budget decision, I would recommend additional analysis of:

- Cost per conversion
- Conversion volume
- Campaign-level performance
- Performance over time
- Whether the $5,000 spend pattern holds across campaign types and channels
- Whether website and email engagement can help identify customers with a higher likelihood of conversion

## Limitations

This analysis identifies patterns and associations in the available dataset. It does not establish causation. In particular, the observed relationship between higher ad spend and conversion should not be interpreted as proof that increasing spend causes conversion to increase.

## Skills Demonstrated

- Data cleaning and validation
- Excel data quality checks
- Tableau dashboard development
- Data visualization
- Calculated fields and aggregation
- KPI development
- Segmentation analysis
- Marketing analytics
- Business-focused data storytelling
- Translating analysis into actionable insights

## Portfolio Project

This project demonstrates my ability to take a business question from **raw data → data validation → analysis → visualization → business insight** and communicate the results to a non-technical stakeholder.
