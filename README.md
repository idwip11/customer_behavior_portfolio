# Customer Behavior Analysis Portfolio

## 📌 Project Overview
This portfolio project focuses on analyzing customer shopping behavior to derive meaningful insights that can drive business decisions. Using a dataset of 3,900 customer records, I performed exploratory data analysis (EDA), customer segmentation, and performance metric evaluation using a combination of **Python**, **SQL**, and **Power BI**.

The goal of this project is to understand purchasing patterns, evaluating shipping and subscription impacts, and identifying key revenue drivers.

## 📂 Project Structure
This repository contains the following key files:

| File Name | Description |
|-----------|-------------|
| `notebook_baru.ipynb` | **Python Notebook**. Contains data cleaning, preprocessing (handling nulls in Review Rating), feature engineering (Age Groups), and exploratory analysis using Pandas. |
| `customer_porto.sql` | **SQL Script**. A collection of queries answering 10+ specific business questions, from revenue analysis to customer segmentation logic. |
| `customer_shopping_behavior.csv` | **Dataset**. The raw data source containing 3,900 rows and 18 columns (Demographics, Purchase Info, Shipping, etc.). |
| `dashboard_customer.pbix` | **Power BI Dashboard**. Interactive visualization of the insights. |
| `Business Problem Document.pdf` | Documentation defining the business problems addressed in this analysis. |
| `Imam_Customer Behavior Analysis.pdf` | Detailed written report of the analysis. |
| `Presentation_Customer-Shopping-Behavior-Analysis.pdf` | Presentation slides summarizing the findings. |

## 🛠 Tools & Technologies
- **Python (Pandas)**: For data manipulation, cleaning, and initial exploration.
- **SQL (MySQL)**: For querying data to answer specific business questions and performing complex aggregations.
- **Power BI**: For creating interactive dashboards and visualizations.

## 📊 Key Analysis & Insights
The analysis covers several critical business aspects. Below are some of the key questions answered in the SQL analysis (`customer_porto.sql`):

1. **Revenue Analysis**:
   - Total revenue breakdown by Gender and Age Group.
   - Comparison of spending between Subscribers and Non-Subscribers.
2. **Customer Segmentation**:
   - **RFM-style Segmentation**: Customers are categorized as 'New', 'Returning', or 'Loyal' based on their previous purchase history.
   - **High-Value Customers**: Identifying customers who use discounts but still spend above the average.
3. **Product & Operation Performance**:
   - Top 5 products by average review rating.
   - Most purchased products within each category (Clothing, Footwear, etc.).
   - Impact of Shipping Type (Standard vs. Express) on purchase amounts.
   - Discount impact on specific products.

## 💻 How to Use
1. **Python Analysis**:
   - Open `notebook_baru.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).
   - Ensure `customer_shopping_behavior.csv` is in the same directory to run the cells.

2. **SQL Analysis**:
   - Import the dataset into your SQL database (table name: `customer`).
   - Run the queries in `customer_porto.sql` to reproduce the insights.

3. **Dashboard**:
   - Open `dashboard_customer.pbix` using [Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) to view the visualizations.

---
*Created by Imam as part of the Data Analyst Portfolio.*
