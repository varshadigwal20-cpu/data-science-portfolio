# BigBasket Pricing & Sales Analysis

**Associated with SkillCircle**

## Project Overview

This project focuses on analyzing 27,000+ BigBasket product records to understand pricing patterns, category-level discounts, product performance, and sales-related trends.

The objective was to transform raw retail data into meaningful business insights through data cleaning, exploratory data analysis, feature engineering, and interactive Power BI dashboarding.

---

## Business Problem

Retail businesses manage large product catalogs where pricing, discounts, product ratings, and sales performance can vary significantly across categories.

Without structured analysis, it can be difficult to understand:

- How sale prices differ from market prices
- Which categories contribute most to sales
- How discounts vary across product categories
- Which products show stronger sales performance
- Whether product ratings are associated with sales performance

The goal of this project was to analyze these patterns and present the findings through an interactive dashboard.

---

## Project Objectives

- Analyze pricing patterns across products and categories
- Understand category-level discount behavior
- Identify products and categories with stronger sales performance
- Compare sale prices with market prices
- Analyze product rating patterns
- Create meaningful business visualizations
- Build an interactive Power BI dashboard for reporting and decision-making

---

## What I Did

### 1. Data Cleaning

- Cleaned missing and duplicate values.
- Checked the dataset for inconsistencies.
- Identified extreme values affecting the analysis.
- Removed outliers using the **Interquartile Range (IQR)** method.

### 2. Feature Engineering

Created a **Discount Percentage** feature to make discount patterns easier to compare across products and categories.

### 3. Exploratory Data Analysis

Performed EDA to investigate:

- Product pricing patterns
- Category-level discount behavior
- Sales trends
- Pricing differences across categories
- Product-level performance
- Relationship between discounts and sales
- Average product ratings

### 4. Data Visualization

Created visualizations to compare:

- Total Sales Price vs. Market Price
- Category-level sales performance
- Category-level market prices
- Sub-category pricing patterns
- Average product ratings
- Top products by sales and market price

### 5. Power BI Dashboard

Built an interactive **Power BI dashboard** with:

- Key Performance Indicators (KPIs)
- Product and brand filters
- Category and sub-category analysis
- Sales vs. market price comparisons
- Product rating analysis
- Interactive charts and visualizations

The dashboard was designed to make the analysis easier to explore and communicate from a business perspective.

---

## Challenges

One of the key challenges was handling extreme product prices in the dataset.

Some products contained unusually high values that could distort statistical analysis and visualizations. I addressed this by identifying and removing outliers using the **IQR method**, resulting in a cleaner dataset for further analysis.

---

## Key Findings

### Pricing & Discount Patterns

- Sale prices are generally lower than market prices, indicating a **discount-driven pricing strategy**.
- The dashboard compares sale prices with market prices across products to identify pricing differences.

### Category Performance

- **Beauty & Hygiene** and **Kitchen & Gourmet** are among the major contributors to total sales.
- Category-level analysis shows significant differences in sales and market-price patterns across product categories.

### Product Performance

- The dashboard compares the top products based on **Total Sales Price** and **Total Market Price**.
- This comparison helps identify products with stronger sales performance and understand their pricing position.

### Ratings

- Average product ratings were analyzed at the product level.
- Higher ratings do not always correspond directly with higher sales, suggesting that product performance can depend on factors beyond ratings alone.

### Category & Sub-category Pricing

- Total Sales Price and Total Market Price were compared across categories and sub-categories.
- These comparisons help identify differences in pricing and sales patterns across the product catalog.

---

## Business Impact

The project demonstrates how retail data can be transformed into actionable business information through structured analysis and visualization.

The analysis and dashboard can help businesses:

- Compare pricing patterns across product categories
- Understand discount-driven pricing strategies
- Identify categories with stronger sales contribution
- Compare product and category performance
- Evaluate the relationship between market prices and sale prices
- Monitor product rating patterns
- Communicate business insights through interactive reporting

These insights can support better **pricing, promotional, category, and sales-related decisions**.

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Power BI**
- **Excel**
- **Jupyter Notebook**

---

## Project Workflow

```text
Raw Retail Data
       ↓
Data Cleaning
       ↓
Outlier Detection using IQR
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Data Visualization
       ↓
Power BI Dashboard
       ↓
Business Insights
