# Pizza Sales Analysis Dashboard

## Overview

This project focuses on analyzing pizza sales data to gain valuable insights into the sales performance of different pizza categories, sizes, and order patterns. The analysis is presented through an interactive **Power BI** dashboard that highlights key metrics, trends, and visualizations. The dashboard allows users to explore data such as total revenue, average order value, total pizzas sold, top-selling pizzas, and much more.

## Features

- **Total Revenue**: Displays the overall revenue generated from pizza sales.
- **Average Order Value**: Shows the average amount spent per order.
- **Total Pizzas Sold**: Tracks the total number of pizzas sold over time.
- **Sales Percentages by Category**: Shows the percentage contribution of each pizza category (e.g., Pepperoni, Veggie, etc.) to total sales.
- **Sales Percentages by Size**: Breaks down sales percentages by pizza size (e.g., Small, Medium, Large).
- **Top and Bottom Selling Pizzas**: Displays the top and bottom pizzas based on revenue, quantity, and total orders.
- **Monthly Trends**: Shows the monthly sales trend and identifies peak sales months.
- **Daily Trends**: Displays daily sales trends for more granular insights.

## Technologies Used

- **Power BI**: Data visualization and dashboard creation tool.
- **SQL**: Used to query the sales data and prepare the data model for Power BI.
- **Power query editior**: Data cleaning and preprocessing (if required).
- **DAX (Data Analysis Expressions)**: Used for creating measures and calcuations.
- 
## Data Sources

- **Pizza Sales Dataset**: The data used for this analysis contains information on pizza orders, including:
  - Order ID
  - Pizza Category
  - Pizza Size
  - Quantity Sold
  - Order Value (Price)
  - Order Date
  
The data is simulated to represent a typical pizza sales scenario.

## Data Analysis Process

1. **Data Import**: Import the pizza sales dataset into Power BI using the built-in data connectors.
2. **Data Cleaning**: Clean the data by handling missing values, removing duplicates, and filtering out irrelevant data.
3. **Data Modeling**: Use Power BI’s data model features to relate different tables (if applicable).
4. **Measure Creation**: Create custom DAX measures to calculate total revenue, average order value, total pizzas sold, and other key metrics.
5. **Dashboard Creation**: Design the dashboard by creating various visualizations like bar charts, pie charts, line graphs, and KPI indicators to present the key insights.

## How to Use

1. **Download the Project**: Clone the repository or download the project files to your local machine.
2. **Open the Power BI File**: Open the `.pbix` file in Power BI Desktop to view and interact with the dashboard.
3. **Explore the Dashboard**:
   - Use slicers to filter by pizza category, size, or time period (e.g., daily or monthly).
   - Hover over charts and graphs to view detailed tooltips.
   - Analyze key metrics like total revenue, top-selling pizzas, and sales trends.
   
## Key Metrics & Insights

- **Top 5 Pizzas by Revenue**: Displays the pizzas that generated the most revenue.
- **Bottom 5 Pizzas by Revenue**: Displays pizzas that contributed the least to total sales.
- **Monthly Trends**: Helps identify peak sales periods, making it easier for business owners to plan promotions or stock inventory.
- **Sales by Pizza Size**: Allows analysis of which pizza sizes are the most popular among customers.

## Conclusion

The **Pizza Sales Analysis Dashboard** provides valuable insights into pizza sales performance, enabling business owners and analysts to make informed decisions. By exploring key metrics such as total revenue, average order value, and pizza category breakdowns, users can identify trends, top-selling pizzas, and sales patterns that drive business growth. This dashboard helps businesses optimize inventory, marketing strategies, and sales operations by providing a clear understanding of sales performance over time.

The project also demonstrates the power of Power BI in turning raw data into actionable insights, with features such as slicers, dynamic charts, and KPI indicators to enhance data exploration. Future improvements, such as forecasting and real-time dashboards, will further enhance the capabilities of this analysis tool.


