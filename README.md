

# 📊 Sales Dashboard | Excel Data Analyst Project

An interactive Excel dashboard that analyzes **9,994 retail orders (2014–2017)** across product categories, states, customers, and time. It is built with Pivot Tables, Pivot Charts, and Slicers.


## 📌 Project Overview

The goal of this project is to turn raw transactional sales data into a dashboard that answers common business questions:

- Which products and sub-categories drive the most revenue?
- How have sales and profit changed from year to year?
- Which states contribute the most sales?
- When is the busiest time of the year?
- Which customers generate the most profit?

## 📈 Dataset Summary

| Metric | Value |
|---|---|
| Orders / rows | 9,994 |
| Period | Jan 2014 – Dec 2017 |
| Total sales | ≈ $2.30M |
| Total profit | ≈ $286K |
| Customers | 793 |
| States | 49 |
| Categories | Furniture, Office Supplies, Technology |

**Columns:** Order Date, Month, Year, Customer Name, State, Category, Sub-Category, Product Name, Sales, Quantity, Profit

## ✨ Dashboard Features

- **Slicers:** filter the whole dashboard by **Year** and **Category**
- **Sales by Sub-Category:** bar chart of revenue per sub-category
- **Profit Trend by Year:** line chart that responds to the selected category
- **Count by Year:** number of sales transactions per year
- **Share of Sales by Region (State):** pie chart of each state's contribution
- **Monthly Sales:** area chart showing seasonality
- **Top 5 Customers Making Profits:** pie chart of the most profitable customers

## 🛠️ Tools & Techniques

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- Formulas (`TEXT` to extract month and year from the order date)
- Data preparation and dashboard formatting

## 🔍 Key Insights

- **Technology** has the highest sales (~$836K) and is also the most profitable category (~$145K).
- **Furniture** has high sales (~$742K) but very low profit (~$18K), so its margins are thin.
- **Phones** (~$330K) and **Chairs** (~$328K) are the top-selling sub-categories.
- Sales grew every year after 2015, from ~$484K in 2014 to ~$733K in 2017.
- Order volume rose from 1,993 orders in 2014 to 3,312 in 2017.
- Sales are strongly seasonal. **September, November, and December** are the peak months.
- **California** (~$458K) and **New York** (~$311K) contribute the largest share of sales.
- The top 5 most profitable customers are Tamara Chand, Raymond Buch, Sanjit Chand, Hunter Lopez, and Adrian Barton.


## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.xlsx` file in Microsoft Excel (2013 or later, for slicer support).
3. Go to the **Dashboard** sheet.
4. Click the **Year** and **Category** slicers to filter all charts at once.

> **Note:** The `salesdata` sheet holds the raw data and `Sheet1` holds the pivot tables behind the charts.





<img width="2036" height="932" alt="image" src="https://github.com/user-attachments/assets/11b79c29-365c-44e8-ba28-1d124e605e93" />
