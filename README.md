# E-commerce Sales & Profitability Analysis

## Project Overview

This project analyzes an e-commerce sales transaction dataset using **Google Sheets** to explore sales performance, profitability, order trends, and shipping costs.

The project was created as a beginner data analytics portfolio project to practice an end-to-end analytical workflow:

**Data → Cleaning → Validation → Analysis → Visualization → Insights**

The final output is an interactive-style dashboard supported by detailed analysis and an audit sheet used to validate the main KPIs.

**Dataset note:** The dataset is a synthetic e-commerce transaction dataset sourced from Kaggle and is used for educational and portfolio purposes.
**Data source:** [E-commerce Sales Transactions Dataset – Kaggle](https://www.kaggle.com/datasets/miadul/e-commerce-sales-transactions-dataset)

## Project Objectives

The main objectives was to understand:

* How revenue and order volume change over time
* Overall sales and profitability performance
* How profitability varies across product categories
* How shipping costs affect profitability
* Whether lower-value orders have different shipping-cost characteristics
* Whether the analysis reveals any areas that warrant further investigation


### Business Question

**How are sales, profitability, and shipping costs performing across time, product categories, and order values?**


## Dataset

The dataset used for this project is the **E-commerce Sales Transactions Dataset** from Kaggle.

**Source:** [Kaggle — E-commerce Sales Transactions Dataset](https://www.kaggle.com/datasets/miadul/e-commerce-sales-transactions-dataset)

The dataset is a **synthetic e-commerce transaction dataset** containing **34,500 transaction records**. It includes fields covering orders, customers, products, pricing, quantities, payment methods, dates, delivery information, regions, returns, revenue, shipping costs, and profit.

### Key fields used in the analysis

* `order_id`
* `customer_id`
* `product_id`
* `category`
* `price`
* `discount`
* `quantity`
* `payment_method`
* `order_date`
* `delivery_time_days`
* `region`
* `returned`
* `total_amount`
* `shipping_cost`
* `profit_margin`
* `customer_age`
* `customer_gender`

Additional calculated fields were created during the project, including:

* `Shipping % of Revenue`
* `Profit Status`
* `Order Value Band`
* `Profit Before Shipping`

> **Note:** The dataset's `profit_margin` field is treated in this analysis as a profit amount in currency rather than a percentage. Profit margin percentages are calculated as **profit divided by revenue**.



