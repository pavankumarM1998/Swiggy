# Swiggy Restaurant Analytics Dashboard in Power BI

### Dashboard : 
https://app.powerbi.com/links/DFoWj8qx-_?ctid=a18b16fa-09b6-41cb-b871-6034e38f437f&pbi_source=linkShare

## Problem Statement
In the dynamic food delivery industry, specifically for platforms like Swiggy, restaurant managers require an analytical tool that provides a holistic view of their performance metrics. This project aims to develop an interactive Power BI dashboard that consolidates key restaurant data, including customer engagement, delivery efficiency, and sales performance. By leveraging this dashboard, stakeholders can identify trends, optimize operations, and enhance customer satisfaction.

## Solution Overview
This project encompasses the creation of a comprehensive Power BI report designed to visualize essential metrics related to restaurants, segmented by city and area. The report includes the following features:

### Features
#### Step 1 :  Key Metrics Overview:

- Total number of Restaurants
- Total number of Customers
- Average Customer Rating
- Average Delivery Time
- Total Sales Amount, including card details

#### Step 2 :City-Wise Analysis:

- Column chart displaying the number of restaurants by city.
- Line chart showing average delivery times across different cities.
- Pie chart representing average ratings and the number of orders by city.

#### Step 3 : Sales Insights:

- Display of the top 5, 10, 20, and 50 restaurants ranked by sales.

#### Step 4 :Drill-Through Functionality:

- Interactive element allowing users to click on a city, redirecting them to a detailed view of the restaurants in that city.

#### Step 5 :Area Performance Analysis:

- Average metrics by area.
- Line chart illustrating average delivery times by area.
- Rankings of the top 5, 10, 20, 50, and 100 areas based on the number of restaurants and sales.

### Step-by-Step Solution

#### Step 1 : Data Collection:

Extracted restaurant performance data from Excel, including customer ratings, sales data, and delivery metrics.
#### Step 2 : Data Loading:

Utilized SQL Server Integration Services (SSIS) to load the extracted data into SQL Server, ensuring proper data transformation and structuring.
#### Step 3 :Data Processing:

Processed the data within SQL Server to compute key metrics such as total customers, average ratings, average delivery times, and total sales.
#### Step 4 :Power BI Integration:

Imported the processed data into Power BI to create dynamic visualizations.
#### Step 5 :Data Visualization:

Developed visual components in Power BI, including:
Column charts for restaurant distribution by city.
Line charts for average delivery times.
Pie charts for average ratings and order counts.
#### Step 6 :Interactive Dashboard Creation:

Designed a user-friendly dashboard layout that enables seamless navigation and exploration of the data.
#### Step 7 :Drill-Through Implementation:

Configured drill-through functionality to allow detailed insights into individual cities and their restaurant performances.
#### Step 8 :Area Performance Ranking:

Calculated and displayed rankings for areas based on sales figures and the number of restaurants.

### Technologies Used
- Data Source: Excel
- ETL Tool: SQL Server Integration Services (SSIS)
- Database: SQL Server
- Visualization Tool: Power BI

### Conclusion
The Swiggy Restaurant Analytics Dashboard provides restaurant managers and stakeholders with essential insights into performance metrics, enabling them to make informed decisions. By utilizing interactive visualizations and drill-through capabilities, this tool supports strategic planning and operational improvements in the competitive food delivery market.

![Home](https://github.com/user-attachments/assets/188a0af1-b526-4457-aa4b-e55252b3fba9)

Drill through

![Drill through](https://github.com/user-attachments/assets/13f91999-fc82-4ade-9285-0e67a07ed738)
