# BigBasket Pricing & Sales Analysis

**Associated with SkillCircle**

## Project Overview

This project focuses on analyzing 27,000+ BigBasket product records to understand pricing patterns, category-level discounts, and sales-related trends.

The objective was to transform raw retail data into meaningful business insights through data cleaning, exploratory data analysis, feature engineering, and interactive dashboarding.

---

## Business Problem

Retail businesses deal with large product catalogs where pricing, discounts, and sales patterns can vary significantly across categories.

The challenge was to analyze the available product data and identify meaningful patterns that could help understand:

- Pricing differences across product categories
- Discount patterns across categories
- Products and categories associated with higher sales
- The relationship between discounts and sales

---

## What I Did

### 1. Data Cleaning

- Cleaned missing and duplicate values.
- Checked the dataset for inconsistencies.
- Identified extreme values affecting the analysis.
- Removed outliers using the **Interquartile Range (IQR)** method.

### 2. Feature Engineering

Created a new **Discount Percentage** feature to make discount patterns easier to analyze across products and categories.

### 3. Exploratory Data Analysis

Performed EDA to investigate:

- Product pricing patterns
- Category-level discount behavior
- Sales trends
- Pricing differences across categories
- Relationship between discounts and sales

### 4. Dashboard Development

Built an interactive **Power BI dashboard** with:

- Key Performance Indicators (KPIs)
- Charts and visualizations
- Category-level analysis
- Interactive filters

The dashboard was designed to make the analysis easier to explore and communicate.

---

## Challenges

One of the key challenges was handling extreme product prices in the dataset.

Some products contained unusually high values that could distort statistical analysis and visualizations. I addressed this by identifying and removing outliers using the **IQR method**, resulting in a cleaner dataset for further analysis.

---

## Business Insights

The analysis was used to explore several business-oriented questions:

- Which product categories offer higher discounts?
- Which products and categories show stronger sales performance?
- How does pricing vary across categories?
- What relationship can be observed between discounts and sales?

These analyses help convert raw retail data into information that can be used for better understanding of product pricing and promotional patterns.

---

## Business Impact

The project demonstrates how retail data can be used to support data-driven decision-making.

The analysis and dashboard can help businesses:

- Compare pricing patterns across product categories
- Understand category-level discount behavior
- Identify important sales-related trends
- Evaluate discount and sales relationships
- Communicate business insights through interactive reporting

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
