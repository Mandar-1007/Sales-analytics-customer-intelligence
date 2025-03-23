# Overview

This project presents a performance dashboard created using Tableau to help executives analyze key business metrics for 2022.
The dashboard is based on Excel data and answers essential business questions related to **sales performance**, **regional contribution**, **top customers**, and **top-selling products**.
It also includes a custom managerial insight to demonstrate additional value.
This repository holds the tableau workbook (.twbx) file contain all interactive visualizations.

# Tools Used

- **Tableau Desktop**
- **Tableau Public**
- **Microsoft Excel**


# Dashboard Visuals & Business Insights

**Final Dashboard**

![image](https://github.com/user-attachments/assets/7c50da15-9ea0-4eea-8269-d61388093c58)

*View the Interactive Dashboard on Tableau Public:* https://public.tableau.com/app/profile/mandar.nadkarni/viz/SalesAnalyticsandCustomerIntelligenceDashboardwithTableau/ExecutiveDashboardSalesPerformance2022 


# Business Questions Answered

1. **How have sales developed in 2022 – compared to the year before?**

![image](https://github.com/user-attachments/assets/4c334258-2d01-43d6-bb99-accd3b651e3c)

This line chart visualizes the year-over-year growth in total sales using SUM(Order_Price_Total). It shows a significant increase in revenue from $1.86M in 2021 to $2.26M in 2022, reflecting positive business growth. Interactive filters for customers and products allow users to analyze how specific segments contributed to this trend.

2. **How were sales distributed over the regions?**

![image](https://github.com/user-attachments/assets/a87b3bc2-17df-45ec-b02f-93647b07f0c5)

This horizontal bar chart shows total sales by country using SUM(Order_Price_Total). The USA, Germany, and Austria emerged as the top-performing regions in 2022. The chart is interactive—clicking on a country filters all other visuals in the dashboard, helping executives analyze regional contributions to revenue.

3. **Who were our top 5 customers in 2022?**

![image](https://github.com/user-attachments/assets/1567aa37-8e86-4633-81fe-9e57ae3657f8)

This bar chart ranks the top 5 customers by total sales revenue using SUM(Order_Price_Total). Save-a-lot Markets, QUICK-Stop, and Ernst Handel lead the list, with each contributing significantly to 2022 revenue. The chart acts as a dynamic filter—clicking on a customer updates other dashboard elements to show their specific sales trends and product preferences.

4. **What were our top 5 products in 2022?**

![image](https://github.com/user-attachments/assets/28ba9df2-595e-4951-891f-68e9f2badcb7)

This bar chart highlights the top 5 products by total revenue using SUM(Product_Order_Price_Total). Côte de Blaye, Thüringer Rostbratwurst, and Raclette Courdavault were the highest-selling products in 2022. The chart supports interactivity—clicking on a product filters all other visuals to reveal related sales trends and top customers.

# Additional Insight: Managerial Question

**Q: Which product category generated the most revenue in 2022?**  

![image](https://github.com/user-attachments/assets/7f4dc5c5-14ca-49ef-8f17-36bf73072d32)

This bar chart answers the question, “Which product category generated the most revenue in 2022?” Using SUM(Product_Order_Price_Total), it shows that Beverages and Dairy Products were the most profitable categories. The chart includes interactivity, allowing executives to filter the entire dashboard by selecting a specific product category—supporting deeper insights into customer behavior and regional performance.

> This insight helps guide decisions related to inventory, marketing focus, and investment priorities.
