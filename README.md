# 🛒 Customer Shopping Behavior – Data Analytics Project

> Forked from [Adityaranjan2003/Customer_Behavior_Analysis](https://github.com/Adityaranjan2003/Customer_Behavior_Analysis). Original project by Aditya Ranjan. My changes are listed below.

## My changes
- Ran the Python notebook to explore the cleaned dataset (3,900 rows, 18 columns).
- Loaded the data into MySQL and ran all 10 business queries myself.
- Added a "Customer Satisfaction" page to the Power BI dashboard showing average review rating by category.

## 📌 Overview
This project analyzes 3,900 shopping transactions to understand customer behavior, spending trends, product preferences, and loyalty patterns, using Python, SQL and Power BI.

## 📂 Dataset
- Rows: 3,900 | Columns: 18
- Features: demographics, purchase details, discounts, ratings, purchase frequency, subscription status
- 37 missing ratings were filled using the median rating of each category (in the original cleaning step)

## 🛠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- MySQL (SQL queries)
- Power BI (dashboard)

## 🔍 SQL Business Questions
Revenue by gender, discount users who still spend above average, top-rated products, express vs standard shipping, subscribers vs non-subscribers, discount-dependent products, customer segments (New / Returning / Loyal), top 3 products per category, repeat buyers and subscriptions, revenue by age group.

## 📊 Dashboard
- KPIs: ~2.7K customers (with the Male filter on), $59.54 average purchase, 3.75 average rating
- Sales and revenue by category, subscription split, age group performance
- New page: average review rating by category

## 📈 What I observed
- Clothing is the biggest category by sales and revenue
- Young adults bring in the most revenue
- About 60% of customers are non-subscribers, and non-subscribers spent more than subscribers
- Average ratings are very similar across categories

## ▶️ How to Run
1. Run the notebook on the cleaned CSV
2. Load the data into MySQL (table `mytable`, database `customer_behavior`)
3. Run `customer_behavior_sql_queries.sql`
4. Open `customer_behavior_dashboard.pbix` in Power BI Desktop

## 👤 Credits
Original project by Aditya Ranjan ([LinkedIn](https://www.linkedin.com/in/aditya-ranjan-3bab11248)). Adapted and extended by Ankitha P.
