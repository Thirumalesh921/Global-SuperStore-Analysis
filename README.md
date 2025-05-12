# Global-SuperStore-Analysis
The Global Superstore Analysis Dashboard is a business intelligence report built in Power BI that visualizes key metrics such as sales, profit, customer segments, and shipping performance. It enables stakeholders to identify high-performing products, profitable customer segments, and regional trends, helping in strategic decision-making.
📊 Global Superstore Analysis Dashboard
This Power BI dashboard presents a comprehensive analysis of sales, profit, and customer behavior from the Global Superstore dataset. The goal is to gain business insights across regions, segments, and product categories to support decision-making.

## 📁 Project Overview
Tool Used: Power BI

Data Source: Global Superstore dataset

Visualizations: Bar charts, pie charts, maps, and KPI cards

Key Focus: Sales performance, profit trends, customer segmentation, shipping modes

## 📊 Dashboard Features
Top 5 products and customers by profit

Sales and profit distribution by segment, country, and sub-category

Shipping mode analysis with volume breakdown

Interactive filters for Country, Year, and Category

KPIs for total customers, orders, shipping days, quantity, discount, sales, and profit

## 🧮 DAX Measures Used

```dax
Customers = DISTINCTCOUNT(Global_Superstore2[Customer ID])

Discount = sum(Global_Superstore2[Discount])

Profit = sum(Global_Superstore2[profit])

Quantity = sum(Global_Superstore2[Quantity])

Sales = sum(Global_Superstore2[Sales])

Shipping Days = ISO.CEILING(AVERAGE(Global_Superstore2[Shipping Days]))

Total orders = Countrows(Global_Superstore2)

```

## 📊 Dashboard
![DashBoard](https://github.com/user-attachments/assets/6a293b4e-0dde-4f19-9544-30228256c706)
