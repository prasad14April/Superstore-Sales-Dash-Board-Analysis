                                                                     Title- Superstore-Sales-Dash-Board-Analysis
 Problem Statement-
 -A retail superstore wants to understand its overall sales performance across different segments,regions,categories and time periods.The Management needs a consolidated dashboard to identify Sales across region,demographics and other parameters

 Objectives-
-Analyze overall business
-Compare Sales by customer segment
-Monitoring Profit Trends
-Understanding Customer Demographics
-Help Management to make Data-driven strategic decision 


 1. Sales Performance Representation
- Total Sales, Profit, and Quantity KPIs  
- Year-wise & Month-wise trend analysis  
- Category and Sub-category analysis  

 2. Insights
- Shipping Mode is the preferred mode of Delivery .Same day mode is less used but profitable because of premium pricing.
- 'Cash on Delivery' is a favourite mode of payment
- When it comes to 'Regional Performance', Western region often leads in Sales while noting that Southern region performs moderately.

 3. Metrics Included
- Total Sales (1.57 M) shown by Donut Chart.
- Quantity Sold (22 K) shown by KPI Card
- Total Profit (175.26 K)
- Average Delivery Days ( Dax Measure used- Dated Iff )

 4. Forecasting
- Sales Forecast using a DAX-based summarize model  
- Trend line for future sales prediction  

 5. DAX Measures Used
- Total Profit = SUM (Superstore_Sales_Dataset (Profit) )
-  Avg Delivery = Dated IFF (Superstore_Sales_Dataset[Order date] , Superstore_Sales_Dataset[Ship date], Day)
