# 📊 E-Commerce Sales Performance Analytics

## Project Overview

This project analyzes an **Amazon e-commerce product dataset** to evaluate product performance, pricing strategies, and customer satisfaction.

The objective is to simulate a **real-world business analytics workflow**, where raw sales data is cleaned, analyzed, and visualized to generate **actionable insights for decision-making**.

The final output is an **interactive Tableau dashboard** highlighting:

- Revenue contribution by product category
- Top revenue-generating products
- Product distribution across categories
- Customer rating patterns
- Impact of discounts on product ratings


---

# Tools & Technologies Used

| Tool | Purpose |
|-----|------|
| Python (Jupyter Notebook) | Data cleaning and preprocessing |
| Pandas | Data manipulation and transformation |
| Tableau Public | Data visualization and dashboard creation |
| GitHub | Project documentation and version control |


---

# Dataset

Dataset: **Amazon Product Dataset**

The dataset contains **1465 products across multiple categories**.

## Key Columns

| Column | Description |
|------|-------------|
| Product ID | Unique identifier for each product |
| Product Name | Product title |
| Category | Product category |
| Discounted Price | Selling price after discount |
| Actual Price | Original product price |
| Discount Percentage | Discount applied |
| Rating | Customer rating (1–5) |
| Rating Count | Number of customer reviews |


---

# Data Cleaning & Preparation

Data preprocessing was performed using **Python (Pandas)** to ensure accuracy before visualization.

## Cleaning Steps

- Removed ₹ currency symbols from price columns
- Converted price columns to numeric format
- Cleaned rating count values by removing commas
- Converted discount percentages to numeric values
- Handled missing or inconsistent values


---

# Feature Engineering

A new metric was created to approximate product performance.

Estimated Revenue Formula:

Estimated Revenue = Discounted Price × Rating Count

This metric helps identify:

- High-performing products
- Revenue-generating categories


---

# 📊 Dashboard Visualizations

The Tableau dashboard includes **five key visualizations**.

---

## Revenue by Category

Shows which product categories generate the **highest estimated revenue**.

![Revenue by Category](images/Revenue_By_Category.png)

---

## Top 10 Products by Revenue

Displays the **highest performing products** based on estimated revenue.

![Top Products](images/Top_Products.png)

---

## Products per Category

Shows the **distribution of products across categories**.

![Products per Category](images/Products_per_Category.png)

---

## Rating Distribution

Analyzes the spread of customer ratings to understand **customer satisfaction levels**.

![Rating Distribution](images/Rating_Distribution.png)

---

## Discount vs Rating

A scatter plot analyzing the **relationship between discount levels and product ratings**.

![Discount vs Rating](images/Discount_vs_Rating.png)


---

# 📈 Key Insights

### 1️. Electronics Drives the Majority of Revenue

- The **Electronics category contributes the highest estimated revenue**.
- This indicates strong demand for electronics products.

---

### 2️. High Customer Satisfaction

Most products have ratings between:

4.0 – 4.5

This suggests **overall strong customer satisfaction**.

---

### 3. Discounts Do Not Significantly Impact Ratings

- The scatter plot shows **no strong negative relationship between discounts and product ratings**.
- Discounted products still maintain **high ratings**.

---

### 4. Uneven Product Distribution

- Some categories contain significantly more products than others.
- This suggests **inventory concentration in certain segments**.


---

# Business Recommendations

### Expand High-Revenue Categories

Increase inventory and marketing efforts in **high-performing categories such as Electronics**.

---

### Promote Best-Selling Products

Top-performing products should be prioritized for **advertising and promotional campaigns**.

---

### Maintain Strategic Discounting

Since discounts do **not significantly reduce ratings**, discount strategies can be used to **increase sales without harming customer perception**.

---

### Optimize Category Inventory

Review product distribution across categories to ensure **balanced inventory and improved category performance**.


---

# 📊 Tableau Dashboard

Explore the interactive dashboard here:

🔗 Tableau Public Dashboard  
(Add your Tableau Public link here)


---

# Project Structure

```
Ecommerce-Sales-Analytics
│
├── data
│   └── amazon_sales_dataset.csv
│
├── notebooks
│   └── data_cleaning_analysis.ipynb
│
├── dashboard
│   └── tableau_dashboard.twbx
│
├── images
│   ├── dashboard.png
│   ├── revenue_category.png
│   ├── top_products.png
│   ├── rating_distribution.png
│   ├── discount_rating.png
│   └── products_per_category.png
│
└── README.md
```


---

# Future Improvements

Possible extensions of this project include:

- Performing **time-series analysis on sales trends**
- Conducting **sentiment analysis on customer reviews**
- Building **predictive models for product performance**
- Creating **advanced KPI dashboards**


---

# Conclusion

This project demonstrates a complete **data analytics workflow**, including:

- Data cleaning and preparation
- Exploratory data analysis
- Data visualization
- Business insight generation

The dashboard provides insights that can help businesses:

- Identify revenue drivers
- Understand customer satisfaction
- Optimize pricing strategies
- Improve product and category management
