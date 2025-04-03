# Zomato
Zomato Restaurant Analysis
# Zomato Restaurant Analysis

This Power BI project analyzes restaurant performance on the Zomato platform with a focus on popularity, revenue, and success drivers such as location, pricing, and cuisine. The goal is to provide insights that can guide strategic decisions for promotions, partnerships, and operational improvements.

## 🔍 Project Objective

To identify what makes certain restaurants more successful by answering:
- Which restaurants receive the most orders and revenue?
- How do pricing, ratings, and cuisine types affect performance?
- Is revenue driven more by volume or price point?
- Are certain locations or menu styles linked to better outcomes?

## 📊 Key Dashboards

1. **Overall Restaurant Performance** – Top performers by revenue, orders, and ratings.
2. **Location-Based Performance** – Regional comparisons in popularity and revenue.
3. **Popularity & Order Trends** – High-demand restaurants and customer patterns.
4. **Pricing & Revenue Insights** – Analysis of price tiers vs. profitability.

## 📁 Data Sources

- `restaurant.csv`
- `orders.csv`
- Datasets were joined on `restaurant_id` and cleaned to ensure consistency.

## 📐 Key Metrics

- Total Revenue = SUM(price × quantity)
- Order Count
- Avg Order Value
- Avg Rating
- Unique Customers

## 📈 Visualizations Used

- Bar charts (Top Restaurants by Revenue)
- Stacked column charts (Revenue by Cuisine)
- Scatter plots (Rating vs Revenue)
- Donut charts (Orders by Cuisine)
- Map visualizations (Regional performance, if supported)

## 📌 Insights

- High-rated restaurants don’t always have the most orders—but often have high revenue.
- Some cuisine types dominate in both popularity and profitability.
- Lower price tiers tend to increase order volume, but not always total revenue.
- Location is a critical factor for restaurant performance.

## 🛠 Tools Used

- Power BI Desktop
- DAX (for calculated columns and KPIs)
- Power BI Service (for publishing and sharing dashboards)

## ✅ Outcome

The dashboard provides an at-a-glance view of top performers, trends, and patterns—helping business users and restaurant owners make data-driven decisions.

---

🚀 Created as a capstone project for a data analytics course using Power BI.
