# E-commerce Data Analytics with SQL: Zepto Retail Project

### Short Description / Purpose

This project demonstrates a complete SQL-based analytics workflow for Zepto’s e-commerce product data. It covers importing raw retail data into PostgreSQL, data exploration, cleaning, and advanced querying to solve real business problems and drive actionable insights.

### Tech Stack

- **PostgreSQL** (for data storage, cleaning, analysis)
- **SQL** (for data manipulation and business intelligence)

### Data Source

The dataset consists of **detailed product-level records** from Zepto, including:
- Product name, category
- Pricing (MRP, discount percent, discounted selling price)
- Inventory attributes (available quantity, weight, out-of-stock status)

Raw data was ingested as a flat table into PostgreSQL and transformed/cleaned via SQL queries for reliability and analysis readiness.

### Features / Highlights

- **Business Problem:**  
  Zepto retailers face the challenge of managing a vast inventory, optimizing discounts, stocking strategies, and tracking revenue across diverse categories and products.

- **Goal of the Dashboard/Analysis:**  
  To provide a repeatable SQL workflow for:
  - Cleaning and standardizing e-commerce product data
  - Exploring inventory structure and availability
  - Analyzing pricing strategies and stock performance
  - Answering core profitability and value questions
  
- **Key Visuals / Query Walkthrough:**  
  - **Data Exploration:**  
    - Count rows, find nulls, analyze category distribution, identify duplicate products, and in/out-of-stock splits.
  - **Data Cleaning:**  
    - Remove price-zero records and standardize currency units.
  - **Business Analysis with SQL:**  
    - **Top 10 best-value products by discount percent**
    - **Out-of-stock products with high MRP**
    - **Estimated revenue by category**
    - **Products with high MRP but low discount**
    - **Top 5 categories by average discount**
    - **Best price-per-gram analysis for products >100g**
    - **Categorizing products (Low, Medium, Bulk) based on weight**
    - **Total inventory weight per category**

- **Business Impact & Insights:**  
  - Revealed which products and categories drive the most revenue and offer the best value
  - Supported pricing and discounting strategy with concrete data
  - Identified stockout risks, helping optimize inventory management
  - Delivered actionable metrics (e.g., price per gram, inventory weight) to guide purchasing and promotional decisions
