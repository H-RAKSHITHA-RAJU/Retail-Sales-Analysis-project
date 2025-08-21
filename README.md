
# Retail Sales Performance Analysis

## Project Overview

This project involves an in-depth Exploratory Data Analysis (EDA) of a retail dataset with over 500,000 sales records. The primary objective is to identify key trends and patterns in product performance and customer behavior to provide actionable insights for inventory management and marketing strategies.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Key Findings & Visualizations](#key-findings--visualizations)
- [Actionable Insights](#actionable-insights)


## Dataset

The dataset used for this analysis is the "Online Retail" dataset from the UCI Machine Learning Repository. It contains transactional data for a UK-based online retail store from 2010 to 2011.

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Size:** 541,909 records
- **Attributes:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Technologies Used

- **Python:** The core programming language for the analysis.
- **Pandas:** Used for data manipulation, cleaning, and preprocessing.
- **Matplotlib & Seaborn:** Utilized for creating a wide range of static, animated, and interactive visualizations. [37, 38]
- **Jupyter Notebook:** The interactive environment for writing and presenting the code.

## Methodology

1.  **Data Cleaning and Preprocessing:**
    - Handled missing values, particularly in the `CustomerID` and `Description` columns.
    - Removed duplicate records.
    - Corrected data types, converting `InvoiceDate` to datetime objects and `CustomerID` to string.
    - This process improved the data quality for analysis by ensuring accuracy and consistency.

2.  **Exploratory Data Analysis (EDA):**
    - Performed descriptive statistical analysis to understand the data's central tendencies and distribution.
    - Analyzed sales trends over time (monthly and daily).
    - Investigated the top-selling products and product categories.
    - Segmented customer data to understand purchasing behavior by country.

3.  **Data Visualization:**
    - Created various plots to visualize the findings from the EDA.
    - Utilized bar charts, line plots, and heatmaps to present the insights in an easily digestible format.

## Key Findings & Visualizations

### 1. Top-Selling Products

A bar chart was created to visualize the top 10 most sold products. This helps in understanding which items are the most popular among customers.

![Top Selling Products](visualizations/top_selling_products.png)

### 2. Peak Sales Months

A line plot illustrating the total sales revenue for each month reveals the seasonal trends in purchasing behavior. This is crucial for planning inventory and marketing campaigns.

![Peak Sales Months](visualizations/peak_sales_months.png)

## Actionable Insights

Based on the analysis, the following actionable insights can help drive business decisions: [18, 27]

*   **Inventory Management:** Stock levels for the top-selling products should be increased to meet customer demand and avoid stockouts, especially during peak sales months. [29]
*   **Marketing and Promotions:** Marketing campaigns should be targeted around the peak sales months (e.g., November and December) to maximize their impact. Promotions can also be run on a monthly basis for the most popular products to drive sales.
*   **Customer Segmentation:** The majority of sales come from the United Kingdom. This suggests that targeted marketing efforts in other countries with high sales potential could be a valuable growth opportunity.
