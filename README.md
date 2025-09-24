# 🚴 Toman Bike Shop - Power BI Dashboard

# 📂 Project Overview
This project analyzes bike rental data (CSV file) for Toman Bike Shop.  
I imported the dataset into Power BI, performed data cleaning with Power Query, and created DAX measures to visualize revenue, profit, rider demographics, and seasonal patterns.

# 📊 Key Insights
- **Revenue:** $4M  
- **Profit:** $2.78M (≈70% margin)  
- **Riders:** 1M (79% registered, 21% casual)  
- **Peak Hours:** 10 AM – 3 PM  
- **Top Days:** Wednesday & Friday  
- **Seasonal Revenue:** Highest in Q3 ($1.33M), lowest in Q1 ($0.50M)  
- **Monthly Trend:** Peaks in May–July, declines after September  

# 🛠️ Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (KPIs & Calculations)  

1 Data Import
. Source: CSV file containing hourly sales, rider demographics, and seasonal performance.
. Imported into Power BI Desktop.

2. Data Transformation
.Used Power Query to clean null values, rename columns, and format data types.
.Applied transformations to calculate time-based trends.

3. Data Modeling & DAX
.Created measures for:
.Total Revenue (SUM(Revenue))
.Total Profit (SUM(Profit))
.Profit Margin ([Profit] / [Revenue])
.Used relationships to connect time, season, and rider tables.

4.Dashboard Design
.KPI Cards → Revenue, Profit, Riders
.Line & Column Chart → KPI Over Time
.Bar Chart → Revenue by Season
.Donut Chart → Rider Demographic
.Table → Hourly Sales Pattern

**Clean layout for storytelling (business questions at the top: “When are we making money?”).**
