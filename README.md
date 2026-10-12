# 📈 Stock Market Investor Dashboard | Power BI

## 📌 Project Overview

The **Stock Market Investor Dashboard** is an interactive Power BI project designed to help users understand customer investment patterns, track stock performance, and analyze profit and loss.

The dashboard brings customer details, stock quantities, buying prices, current prices, investment amounts, and profit/loss information into one place. Users can explore the data using interactive filters and visuals to understand how different customers and stocks are performing.

## 🎯 Project Objectives

- Track customer investments and overall profit or loss.
- Identify the most preferred stocks among customers.
- Analyze stock quantities and investment amounts.
- Compare buying prices with current stock prices.
- Identify customers making profits or facing losses.
- Understand the relationship between investment amount and profit.

## 📊 Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard provides a quick overview of the investment data through key metrics:

- **Total Customers:** Number of customers included in the dataset.
- **Average Buying Price:** Average price at which stocks were purchased.
- **Average Current Price:** Average current price of the stocks.
- **Total Investment Amount:** Overall amount represented in the dataset.
- **Top Performing Stock:** Highlights the stock with the highest performance according to the dashboard's calculation.
- **Total Quantity:** Total number of stock units represented in the dataset.

### 2. Customer Profit & Loss Analysis

A donut chart shows how many customers are in profit and how many are facing losses.

Users can select a status, such as Profit or Loss, to filter the dashboard and explore the corresponding customer details.

### 3. Customer Distribution by Interested Stock

A bar chart displays the number of customers interested in each stock, such as TCS, Reliance, Infosys, Zomato, and ICICI Bank.

This helps identify which stocks are most popular among the customers in the dataset.

### 4. Customer Investment Details

A detailed table displays customer-level investment information, including:

- Customer Name
- Interested Stock
- Total Amount
- Quantity
- Total Profit or Loss
- Investment Status

This allows users to compare individual customer investments and identify who is making a profit or experiencing a loss.

### 5. Stock Quantity Analysis

A treemap visualizes the total quantity associated with each stock.

By comparing the size of the blocks, users can quickly identify which stocks account for larger quantities in the dataset.

### 6. Buying Price vs. Current Price

A line chart compares the aggregated buying prices and current prices across different stocks.

This helps users explore price differences between stocks and identify where current prices are higher or lower than buying prices.

### 7. Investment Amount vs. Total Profit

A scatter plot compares the total investment amount with the total profit or loss for customers.

It helps identify patterns such as:
- Customers investing more but generating relatively low profits.
- Customers investing less but generating higher profits.
- Customers experiencing significant gains or losses.

### 8. Stock-Wise Profit & Loss Summary

A summary table presents the number of customers in profit and loss for each interested stock.

This provides a quick comparison of customer outcomes across different stocks.

### 9. Individual Customer Profitability

The dashboard includes a gauge-style visual for examining customer profitability.

When a customer is selected, the visual helps show their profit or loss relative to the overall scale used in the dashboard. Supporting measures can also be used to display the profit percentage and the difference between buying and current values.

### 10. Interactive Filters

Users can filter the dashboard by:

- Interested Stock
- Customer Name

The visuals update based on the selected filters, making it easier to investigate individual customers or specific stocks.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data preparation and transformation, where applicable
- **DAX** – Measures and calculations, where applicable
- **Data Visualization** – KPI cards, donut chart, bar chart, treemap, line chart, scatter plot, tables, and gauge visual

## 💡 Key Insights

The dashboard helps users explore questions such as:

- Which stocks attract the most customers?
- How many customers are making profits versus losses?
- Which stocks account for the highest quantities?
- How do buying prices compare with current prices?
- Which customers have invested the most?
- Are higher investments associated with higher profits?
- How does customer profitability vary across different stocks?

## 🚀 How to Use the Dashboard

1. Download or clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Allow the report to load and refresh the data if required.
4. Use the stock and customer filters to explore the dataset.
5. Select chart elements to cross-filter other visuals.
6. Review the KPI cards, customer table, and charts to understand the investment patterns and profitability.

## 📷 Dashboard Preview

The dashboard provides a single-page overview of customer investments, stock preferences, and profit/loss performance.


## 📁 Repository Contents

- `Stock Market Investor Dashboard.pbix` – Power BI dashboard file
- `README.md` – Project documentation
- `images/dashboard-preview.png` – Dashboard screenshot

## ⚠️ Disclaimer

This dashboard is intended for data analysis and visualization purposes only. The results depend on the dataset and the calculations used in the report. The dashboard does not provide financial advice or predict future stock market performance.

---

**Built with Power BI | Stock Market Data Analysis & Visualization**
