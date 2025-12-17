# Olist Brazilian E-commerce Analytics Project

##  Project Overview
This project presents an end-to-end analysis of the **Olist Brazilian E-commerce dataset**, focusing on understanding **sales performance, customer behavior, seller efficiency, logistics operations, payment behavior, and customer review sentiment**.

The goal of the project is to transform raw transactional data into **business-ready insights** using Python for data preparation and Power BI for interactive dashboarding. The final output is a multi-page Power BI dashboard supported by a detailed analytical report, suitable for real-world business decision-making.



##  Business Objectives
- Analyze overall sales and revenue performance
- Identify high-performing product categories and products
- Understand customer acquisition and retention behavior
- Evaluate seller performance in relation to delivery efficiency
- Assess logistics performance and delivery delays
- Explore customer review sentiment and its business impact
- Provide actionable recommendations based on data insights



##  Dataset Description
**Source:** Olist Brazilian E-commerce Public Dataset  
The dataset consists of multiple relational tables representing real-world e-commerce operations in Brazil.

### Key datasets used:
- Orders
- Order Items
- Customers
- Products
- Sellers
- Payments
- Reviews
- Geolocation
- Product Category Translation

These datasets were cleaned, standardized, and merged into a single analytical table for visualization and modeling.


##  Data Preparation & Feature Engineering
Data cleaning and preparation were performed in **Python (Jupyter Notebook)** and included:
- Handling missing and inconsistent values
- Standardizing date and time formats
- Translating product category names from Portuguese to English
- Aggregating geolocation data by ZIP code prefix
- Creating new analytical features such as:
  - Delivery Time (Days)
  - Delivery Delay Flag
  - Units Sold
  - Total Revenue
  - Customer Type (New vs Returning)
  - Repeat Purchase Rate
  - Seller Performance Metrics

## Exploratory Data Analysis (EDA)
EDA was conducted to understand:
- Revenue distribution across product categories
- Seasonal sales trends
- Customer purchase frequency
- Delivery time patterns and delays
- Relationship between delivery performance and review scores
- Payment method and installment usage

Insights fr

