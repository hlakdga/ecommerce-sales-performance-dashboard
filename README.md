# E-commerce Sales Performance Dashboard

## 1. Project Overview

This project analyzes e-commerce sales performance using Power BI. The dashboard is designed to monitor key business metrics such as revenue, completed orders, units sold, average order value, profit, return rate, product performance, customer segments, traffic sources, sales channels and device types

The project simulates a real-world e-commerce analytics workflow, including data preparation, KPI calculation, dashboard design, insight generation and business recommendation

The main goal of this project is to support business users in understanding overall sales performance, identifying high-performing products and categories and making better decisions related to promotion, inventory, sales channels, and customer engagement

---

## 2. Dataset

The dataset used in this project is a large-scale synthetic e-commerce dataset from Kaggle:

**Global E-Commerce Dataset (+1M Records, 2024–2026)**

The dataset contains transaction-level e-commerce data, including:

* Order information
* Customer attributes
* Product details
* Category and product performance
* Pricing and profit
* Stock quantity
* Traffic source
* Device type
* Sales channel
* Order status

> Note: This is a synthetic dataset used for learning and portfolio purposes. Some fields such as stock quantity are treated as indicative operational metrics rather than real-time inventory balances

---

## 3. Tools Used

* Power BI
* Power Query
* DAX
* Excel
* GitHub

---

## 4. Data Preparation

The dataset was prepared and transformed in Power Query before building the dashboard

Main preparation steps included:

* Checked and adjusted data types for date, revenue, profit, quantity, stock, and order status fields
* Created time-based fields for monthly trend analysis
* Filtered and calculated completed orders for business KPI tracking
* Prepared measures for revenue, profit, order volume, units sold, AOV, and return rate
* Organized fields for product, category, customer, channel, traffic source, and device-level analysis

---

## 5. Key Metrics

The dashboard tracks the following business KPIs:

* **Total Revenue**: Total sales revenue generated from e-commerce transactions
* **Completed Orders**: Number of successfully completed orders
* **Units Sold**: Total quantity of products sold
* **Average Order Value (AOV)**: Average revenue per completed order
* **Total Profit**: Total profit generated from sales
* **Return Rate**: Percentage of returned orders compared with total orders
* **Revenue by Month**: Monthly revenue trend across the analyzed period
* **Revenue by Category**: Revenue contribution by product category
* **Profit by Category**: Profit contribution by product category
* **Revenue by Sales Channel**: Revenue performance across e-commerce channels
* **Revenue by Customer Segment**: Revenue contribution by customer segment
* **Orders by Device Type**: Order distribution by desktop, mobile, and tablet

---

## 6. Dashboard Pages

### Page 1: Executive Overview

This page provides a high-level summary of overall business performance

Key metrics and visuals:

* Total Revenue
* Completed Orders
* Units Sold
* Average Order Value
* Total Profit
* Return Rate
* Revenue by Month
* Top Products by Revenue
* Revenue by Sales Channel
* Orders by Status

### Page 2: Product & Category Performance

This page focuses on product and category-level performance

Key metrics and visuals:

* Revenue by Category
* Profit by Category
* Top Products by Profit
* Top Products by Average Stock
* Units Sold
* Average Stock Quantity

### Page 3: Customer & Channel Analysis

This page analyzes customer segments, age groups, traffic sources and device types

Key metrics and visuals:

* Revenue by Customer Segment
* Revenue by Age Group
* Revenue by Traffic Source
* Orders by Device Type
* Average Order Value
* Return Rate

---

## 7. Key Insights

* Electronics is the leading product category in both revenue and profit, indicating that this category is a major business driver
* Lazada and Shopee are the leading sales channels, while TikTok Shop contributes lower revenue compared with the other two channels
* Regular customers generate the highest revenue among customer segments, suggesting that the main revenue base comes from mass-market customers rather than only high-tier segments
* Customers aged 55+ generate the highest revenue, which may indicate differences in purchasing power or product preference by age group
* Revenue is distributed across multiple traffic sources, including Direct, Social, Email, Referral, and Search, showing the importance of maintaining multiple acquisition channels
* Orders are relatively evenly distributed across desktop, mobile, and tablet, suggesting that the shopping experience should be optimized across all device types
* Products with high average stock should be monitored together with revenue and profit performance to avoid potential overstock risk
* The sharp drop in February 2026 should be interpreted carefully because the dataset may only contain partial data for that month

---

## 8. Business Recommendations

* Prioritize high-revenue and high-profit categories such as Electronics when planning promotions, inventory and merchandising strategies
* Monitor products with high average stock but lower profit contribution to reduce potential overstock risk
* Continue optimizing Lazada and Shopee as key revenue channels while exploring ways to improve TikTok Shop performance
* Strengthen customer retention and engagement strategies for Regular customers because they contribute the largest share of revenue
* Maintain multiple acquisition channels instead of relying on a single traffic source
* Ensure the e-commerce experience is consistent across desktop, mobile, and tablet because order volume is relatively balanced across device types
* Treat incomplete months carefully in time-series analysis to avoid misleading business conclusions

---

## 9. Dashboard Preview

### Executive Overview

![Executive Overview](screenshots/executive_overview.png)

### Product & Category Performance

![Product & Category](screenshots/product_category.png)

### Customer & Channel Analysis

![Customer & Channel](screenshots/customer_channel.png)

---

## 10. Project Files

```text
ecommerce-sales-performance-dashboard/
│
├── data/
│   └── raw/
│
├── powerbi/
│   └── Power BI file is available upon request due to file size limitations
│
├── screenshots/
│   ├── executive_overview.png
│   ├── product_category.png
│   └── customer_channel.png
│
├── insights.md
└── README.md
```

> Note: The Power BI `.pbix` file is not included in this repository due to GitHub file size limitations. Dashboard screenshots and project documentation are provided for review. The Power BI file can be shared upon request

---

## 11. What I Learned

Through this project, I practiced:

* Cleaning and preparing e-commerce data in Power Query
* Creating DAX measures for business KPIs
* Designing a multi-page Power BI dashboard
* Building executive-level and operational-level dashboard pages
* Analyzing product, category, customer, channel, and traffic source performance
* Translating data analysis into business insights and recommendations
* Presenting a data analytics project professionally on GitHub

---

## 12. Possible Improvements

In the future, this project can be improved by:

* Adding more detailed campaign-level analysis
* Comparing conversion performance across traffic sources
* Adding customer retention and repeat purchase analysis
* Building a more detailed inventory monitoring page
* Creating more advanced DAX measures for year-over-year and month-over-month performance comparison
