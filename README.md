# Advanced_sales_analysis_using_Google_Looker 
# Project Overview
This project analyzes **sales data** to extract actionable insights and create interactive visualizations using **SQL, Python, and Google Looker Studio**. The dataset consists of multiple tables — `customer_details`, `order_details`, `sku_details`, and `payment_details` — representing customers, orders, products, and payments.

**Objectives:**
- **Derive Key Business Insights:** Identify top-performing products, analyze category trends, and support data-driven decision-making.
- **Visualize Data Effectively:** Build interactive dashboards for stakeholders.
- **Analyze Customer Behavior:** Examine payment patterns to enable targeted marketing campaigns.

---

## Pre-requisites
Before running this project, the following knowledge and tools are recommended:

**SQL:**
- Writing queries with `SELECT`, `JOIN`, `GROUP BY`, `WHERE`, and `HAVING`
- Understanding relational database concepts

**Python:**
- Data manipulation using **Pandas**
- Visualizations using **Matplotlib** and **Seaborn**
- Data cleaning, transformation, and feature engineering

**Google Looker Studio:**
- Connecting data sources and building interactive dashboards
- Implementing dynamic filters, drill-downs, and visualizations

**Data Analysis Concepts:**
- Trend analysis, time period comparison, and KPI aggregation
- Metrics like total sales, growth percentages, and category performance

**Tools & Technologies:**
- SQL Database
- Python IDE (Jupyter Notebook)
- Google Looker Studio

---

## Key Steps and Analysis

### 1. Data Preparation
- **Database Setup:**
  - Created a normalized sales database for scalability
  - Key tables:
    - `customer_details`: Customer information
    - `order_details`: Order transactions
    - `sku_details`: Product details (categories, pricing)
    - `payment_details`: Payment methods and statuses
- **Data Transformation with Python:**
  - Extracted data via SQL queries
  - Cleaned and enriched data using Pandas
  - Calculated features like `qty_growth` and `delta_2022_2021`

### 2. Analysis and Visualization
**Top Product Analysis (2022):**
- Identified Top 5 products in the "Mobiles & Tablets" category by sales quantity
- Visualized results using **bar charts**

**Category Trend Analysis (2021 vs 2022):**
- Compared category-wise sales performance across two years
- Focused on "Others" category to identify Top 20 declining products
- Visualized using **horizontal bar charts**

**Customer Payment Behavior:**
- Identified customers with pending payments despite completing checkout (`is_gross = 1`)
- Segmented customers for **targeted follow-ups**

**Google Looker Studio Dashboards:**
- Developed interactive dashboards showcasing:
  - Year-on-year sales performance by category
  - Top-performing and declining products
  - Customer payment patterns
- Dashboards support dynamic filtering, drill-downs, and real-time exploration

---

## Tools and Technologies Used
- **SQL:** Database creation, querying, and aggregation
- **Python:** Data processing (**Pandas**) and visualization (**Matplotlib**)
- **Google Looker Studio:** Interactive dashboards with dynamic filters

---

## Key Deliverables
- **Actionable Insights:** Top products, category trends, inventory and promotional recommendations
- **Interactive Dashboards:** Real-time exploration and intuitive visualizations
- **Customer Targeting:** Identified customers for payment follow-ups to optimize cash flow and conversions

---

## Impact
This project empowers stakeholders with **actionable insights and interactive visualizations**, supporting strategic decisions in marketing, sales, and customer management. Looker Studio dashboards make complex data **accessible and easy to interpret**, enabling data-driven strategies for improved business outcomes.
