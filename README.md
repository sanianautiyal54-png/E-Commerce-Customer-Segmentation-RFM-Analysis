E-Commerce Customer Segmentation (RFM Analysis)

Project Overview

This project focuses on analyzing e-commerce customer behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

The objective is to identify different customer groups based on their purchasing behavior and provide marketing recommendations to improve customer retention, engagement, and revenue.

Project Objectives

- Analyze customer purchasing behavior.
- Calculate Recency, Frequency, and Monetary values.
- Assign RFM scores to customers.
- Apply K-Means clustering to identify customer groups.
- Visualize customer segments using Power BI.
- Recommend suitable marketing campaigns for different customer segments.

Tools & Technologies

- Excel: Data cleaning and preparation.
- Python: Data analysis and customer segmentation.
- Pandas: Data manipulation.
- Scikit-learn: K-Means clustering.
- Power BI: Interactive dashboards and visualization.

Dataset

Source: UCI Online Retail Dataset

The dataset contains e-commerce transaction information, including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

Project Workflow

1. Data Cleaning

- Checked missing values.
- Removed duplicate records.
- Handled cancelled transactions and invalid entries.
- Prepared data for customer-level analysis.

2. RFM Analysis

Calculated three important customer metrics:

- Recency: How recently a customer made a purchase.
- Frequency: How frequently a customer purchased.
- Monetary: How much money a customer spent.

Created RFM scores to understand customer purchasing patterns.

3. K-Means Clustering

Applied the K-Means clustering algorithm using Python to group customers based on their purchasing behavior.

Identified four clusters and used customer purchasing patterns to understand the groups.

4. Customer Segmentation

Customers were categorized into six business-friendly segments:

- Champions
- Loyal Customers
- Potential Loyalists
- New Customers
- At Risk
- Lost Customers

5. Power BI Dashboard

Created a three-page interactive dashboard.

Page 1: Customer Overview & RFM Analysis

- Total Customers
- Total Revenue
- Average Monetary
- Average Frequency
- Average Recency
- Average RFM Score
- Revenue by Customer Segment

Page 2: Customer Segmentation Analysis

- Customer count by segment
- Average Recency by segment
- Average Monetary by segment
- Average Frequency by segment
- Revenue contribution percentage
- Average RFM Score by segment

Page 3: K-Means Clustering Analysis

- Total Clusters
- Total Customers
- Average RFM Score
- Frequency vs. Monetary scatter plot
- Cluster-based analysis

Key Findings

Based on the Power BI dashboard:

- Total customers analyzed: 4,312
- Total revenue: 8.80M
- Average monetary value: 2.04K
- Average purchase frequency: 4.46
- Average recency: 91.17 days
- Average RFM score: 9.00
- Total K-Means clusters: 4

Champions contribute the highest revenue among the customer segments.

Business Recommendations

Customer Segment| Recommended Strategy
Champions| Exclusive rewards and loyalty benefits
Loyal Customers| Repeat purchase discounts
Potential Loyalists| Personalized product recommendations
New Customers| Welcome offers and onboarding campaigns
At Risk| Special re-engagement discounts
Lost Customers| Win-back email campaigns

Priority: Focus on At-Risk customers with personalized re-engagement campaigns to encourage repeat purchases and reduce customer loss, while maintaining loyalty among Champions.

Conclusion

This project helped me understand how RFM analysis and K-Means clustering can be used to identify meaningful customer segments.

By combining Python analysis with Power BI visualization, I transformed customer transaction data into useful business insights and marketing recommendations.

The project provided practical experience in data cleaning, customer analytics, clustering, data visualization, and business decision-making.

Project Files

- "RFM_Analysis.xlsx" – Customer-level RFM data.
- "E_Commerce_Customer_Segmentation.ipynb" – Python analysis and clustering.
- "E-Commerce RFM Analysis.pbix" – Power BI dashboard.
E-commerce customer segmentation project using RFM analysis and K-Means clustering with Python, Excel, and Power BI to identify customer groups and generate actionable marketing recommendations.
