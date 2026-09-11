# Amazon Sales Analysis Dashboard

## 📊 Project Overview
This Power BI dashboard analyzes Amazon's sales data to understand overall business performance, product category trends, regional sales distribution, and customer purchasing behavior. By examining revenue, order volume, discounts, and customer ratings, the dashboard helps identify which products and regions drive the most growth.

## 🎯 Objective
The goal of this project is to build an interactive, multi-page Power BI dashboard that provides actionable insights into sales performance, product trends, and customer satisfaction — enabling data-driven decisions for inventory planning, regional expansion, and marketing strategy.

## 🛠️ Tools Used
- **Power BI** – Data visualization and interactive dashboard
- **Excel** – Data cleaning, preparation, and validation

## 📁 Data Source


## 📁 Dataset
The analysis is based on order data including:
- Product category
- Region
- Order date
- Quantity sold
- Unit price
- Discount percentage
- Revenue
- Payment method
- Customer rating

## 🧹 Data Cleaning (Power Query)
The raw data was cleaned and transformed using Power Query in Power BI:
- Imported the raw CSV file and promoted the first row as column headers
- Set correct data types for each column (text, number, date)
- Filtered out blank and invalid rows
- Removed duplicate and unnecessary entries
- Removed unused columns and reordered the remaining columns logically
- Extracted new columns from the order date: Year, Month, Month Name, Day Name, Quarter, and Week of Month (for time-based trend analysis)
- Renamed all columns for clarity and final consistency

## 📐 Key Measures (DAX)

- Total Revenue = SUM(Sales[Revenue])
- MTD Revenue = TOTALMTD([Total Revenue], Calendar[Date])
- YTD Revenue = TOTALYTD([Total Revenue], Calendar[Date])
- Average Discount % = AVERAGE(Sales[Discount_Percentage])
- Average Rating = AVERAGE(Sales[Rating])

## 📄 Dashboard Pages
1. **Overview** – Cover page with project summary
2. **Product View** – Revenue, quantity sold, and discount analysis by product category and region
3. **Customer Rating** – Customer count, rating distribution, and revenue by rating

## 📸 Screenshots


## 📈 Key Insights
- Identified top-performing product categories by revenue and region
- Analyzed monthly revenue trends (MTD/YTD)
- Compared customer ratings against revenue by product
- Segmented sales performance across four global regions

## 🙋 About Me
**Anuradha Ghosh**
B.Sc. in Biosciences | Aspiring Data Analyst
Skills: Excel, Power BI

## 🔗 Connect

Feel free to reach out for feedback or collaboration!
