# Blinkit_Analysis_Report

## Snapshots

![Blinkit Report](https://github.com/user-attachments/assets/4f48668d-6259-4251-bb7f-d1d341f387bd)

The Blinkit Sales Analysis Dashboard is a Power BI project designed to help business stakeholders of "Blinkit" – a fictional last-minute delivery app – gain deep insights into sales performance, customer satisfaction, and outlet efficiency. The dashboard consolidates data from various sources to create a single view of the business, enabling stakeholders to make informed decisions based on data-driven insights.

## Table of Contents

1. Objective
2. Features
3. Dashboard Components
4. Approach and Steps
5. Key Insights


## Objective

The primary objective of this dashboard is to:

* Provide a high-level overview of Blinkit’s sales and item availability.
* Allow detailed analysis by filtering on parameters like outlet type, outlet size, and item categories.
* Offer visual insights to help management identify trends, optimize operations, and improve customer satisfaction.

## Features

  This dashboard provides a comprehensive set of features to explore and analyze sales data effectively:
  
  ### 1. Filter Panel
  The filter panel on the left side allows users to dynamically adjust the displayed data, enhancing the interactivity of the report.
  
  * Outlet Location Type: Filter sales by the type of location, such as Tier 1, Tier 2, and Tier 3 areas. This enables comparison across different location segments.
  * Outlet Size: Adjust the data based on outlet size (Small, Medium, Large) to assess which sizes perform better in terms of sales and customer ratings.
  * Item Type: Filter based on item categories, such as Snacks, Dairy, Household, Beverages, etc., allowing a deep dive into individual item performance.
    
  ### 2. Key Metrics Display
  A set of key metrics provides a quick summary of Blinkit’s performance:
  
  * Total Sales: Displays the total revenue generated, providing an at-a-glance understanding of the overall business scale.
  * Average Sales: Calculates the average sales per item, helping identify revenue per item type and gauge product-level profitability.
  * Average Rating: Shows the average customer rating, offering insights into customer satisfaction and potential areas for improvement.
  * Number of Items: Indicates the total number of unique items offered across all outlets, reflecting product diversity.
    
  ### 3. Visualizations and Analysis
  The dashboard includes several visualizations for exploring data from different angles:
  
  * Outlet Establishment Trend: A line chart tracking outlet establishment dates and sales growth over time. This chart reveals how Blinkit’s outlets expanded and their corresponding       impact on sales.
  * Outlet Size Distribution: A donut chart showing sales distribution by outlet size (Small, Medium, High), allowing management to see which size generates the highest revenue.
  * Outlet Location Breakdown: A horizontal bar chart representing sales across Tier 1, Tier 2, and Tier 3 locations, enabling region-specific sales analysis.
  * Item Type Analysis: A bar chart listing sales for each item category. This breakdown helps identify popular items and high-performing categories.
  * Fat Content Analysis: A comparative visualization analyzing the sales of Low Fat and Regular items by outlet location. This helps in understanding customer preferences for healthier     options.
  
### 4. Data Table Summary
A data table at the bottom right provides a summarized view of key metrics by outlet type:

* Outlet Type: Displays outlet categorization, such as Grocery, Supermarket, etc.
* Total Sales: Total sales revenue for each outlet type.
* Avg Sales: Average sales value for each outlet type.
* Number of Items: Count of unique items available in each outlet type.
* Avg Rating: Average customer rating, useful for gauging customer satisfaction.
* Item Visibility: Indicates the visibility/popularity of items based on the number of items shown for each outlet type.

## Dashboard Components
  Here’s a breakdown of the main components of the dashboard:

* Sales Summary Cards: These display total sales, average sales, and ratings, giving a quick overview of business performance.
* Trend Analysis Chart: A year-by-year visualization of sales and outlet establishment, providing insights into historical trends and growth patterns.
* Donut and Pie Charts: Visualizations of outlet size and fat content distribution, offering insights into sales by store type and product healthiness preference.
* Bar Charts: Item type and outlet location bar charts help identify the contribution of each segment to overall sales.
* Data Table: A detailed table with color-coded metrics for quick reference, making it easy to identify top and low-performing outlet types.

## Approach and Steps

### Step 1: Data Collection and Preparation
* Gathered data from various sources, including databases and spreadsheets, containing information on sales, outlet attributes, item categories, and ratings.
* Cleaned and transformed the data in Power BI or SQL to ensure accuracy and consistency. This included handling missing values, standardizing formats, and performing necessary       
  calculations.
  
### step 2: Data Modeling
* Built a relational data model in Power BI to define relationships between data tables, ensuring efficient query performance and meaningful connections between data points.
* Added calculated columns and measures to support complex metrics, such as average sales and item visibility.

### step 3: Design the Dashboard Layout
* Created a wireframe for the dashboard to plan the layout and decide on visualization types.
* Ensured that the layout is intuitive, with a filter panel on the left, key metrics at the top, and detailed visualizations and tables below for easy navigation.

### step 4: Build Visualizations
* Developed various visuals in Power BI such as bar charts, donut charts, line charts, and summary cards, to convey insights effectively.
* Configured interactivity in the dashboard allowing users to drill down into data by selecting filters in the panel.

### step 5: Add Calculations and Measures
* Created DAX (Data Analysis Expressions) measures for advanced calculations like total sales, average sales per item, and ratings, improving the analytical depth of the dashboard.
* Configured conditional formatting for metrics in the table to highlight key figures for better readability.

## Key Insights
This dashboard provides a variety of insights that help in making strategic decisions:

* Sales by Outlet Type and Size: The donut chart and data table reveal which outlet sizes and types contribute most to overall sales, guiding decisions on outlet expansion or downsizing.
* Regional Performance: The Outlet Location Breakdown chart shows how sales are distributed across different location tiers, highlighting the areas with the highest customer demand.
* Item Popularity and Sales Contribution: The Item Type Analysis chart allows stakeholders to see which product categories (e.g., Snacks, Beverages) generate the most revenue.
* Health Trends: The Fat Content Analysis provides insights into consumer preferences for Low Fat vs. Regular products, which can inform inventory and product development decisions.
* Customer Satisfaction: By analyzing average customer ratings across outlet types, Blinkit can identify outlets with lower ratings and take steps to improve customer experience in 
  those areas.
* Sales Trends Over Time: The trend chart helps in understanding how sales have evolved with the growth in the number of outlets, indicating the impact of expansion strategies.





