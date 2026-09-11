# Amazon Sales Analysis Dashboard

## 📊 Project Overview
This Power BI dashboard analyzes Amazon's sales data to understand overall business performance, product category trends, regional sales distribution, and customer purchasing behavior. By examining revenue, order volume, discounts, and customer ratings, the dashboard helps identify which products and regions drive the most growth.

## 🎯 Objective
The goal of this project is to build an interactive, multi-page Power BI dashboard that provides actionable insights into sales performance, product trends, and customer satisfaction — enabling data-driven decisions for inventory planning, regional expansion, and marketing strategy.

## 🛠️ Tools Used
- **Power BI** – Data visualization and interactive dashboard
- **Excel** – Data cleaning, preparation, and validation

## 📁 Data Source
https://www.kaggle.com/datasets/aliiihussain/amazon-sales-dataset

## 📁 Dataset
The analysis is based on order data including:
order_id,
order_date, 
product_id,
product_category,
price, 
discount_percent,
discounted_price,
quantity_sold, 
total_revenue, 
customer_region,
payment_method, 
rating, 
review_count

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

- TOTAL REVENUE = SUM('amazon-1'[REVENUE])
- TOTAL QUANTITY SOLD = SUM('amazon-1'[QUANTITU_SOLD])
- YTD REVENUE = TOTALYTD(SUM('amazon-1'[REVENUE]),'amazon-1'[ORDER_DATE])
- AVERAGE DISCOUNT % = AVERAGE('amazon-1'[DISCOUNT_%])
  
## 📄 Dashboard Pages
1. **Overview** – Cover page with project summary
2. **Product View** – Revenue, quantity sold, and discount analysis by product category and region
3. **Customer Rating** – Customer count, rating distribution, and revenue by rating
   
## Dashboard link 
https://github.com/anuradhaghosh-byte/Amazon-Sales-Analysis-Dashboard/blob/main/amazon2.pbix

## 📸 Dashboard Preview
<img width="1421" height="802" alt="OVERVIEW" src="https://github.com/user-attachments/assets/872841b4-8182-479f-9347-95fd0c8a7c75" />
<img width="1532" height="871" alt="PRODUCT VIEW" src="https://github.com/user-attachments/assets/03dc75e1-8b1d-4b3a-bee6-abd1aecdc191" />
<img width="1542" height="871" alt="CUSTOMER RATING VIEW" src="https://github.com/user-attachments/assets/9a7910a8-0cbe-41d4-b8cd-448701871227" />


## 📈 Key Insights
- Identified top-performing product categories by revenue and region
- Analyzed monthly revenue trends (MTD/YTD)
- Compared customer ratings against revenue by product
- Segmented sales performance across four global regions

## 🙋 About Me
**Anuradha Ghosh**
B.Sc. in Biosciences | Aspiring Data Analyst
Skills: Excel, Power BI

Feel free to reach out for feedback or collaboration!
