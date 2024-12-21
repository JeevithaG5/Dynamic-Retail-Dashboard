### README for Dynamic Retail Dashboard

# Dynamic Retail Dashboard

## Overview

The **Dynamic Retail Dashboard** is an Excel-based analytical tool designed to provide comprehensive insights into retail operations. This dashboard uses data from three sheets: `Orders`, `People`, and `Returns`, offering a detailed view of key metrics and trends. The dashboard includes various interactive charts and visualizations to help users analyze sales performance, understand customer demographics, and track returns.

## Significance

The Dynamic Retail Dashboard is crucial for retail businesses to:
- **Monitor Key Performance Indicators (KPIs)**: Keep track of total sales, profit, quantity, number of orders, and profit margin.
- **Analyze Market Performance**: Gain insights into different segments, categories, and markets.
- **Identify Trends and Patterns**: Visualize yearly sales trends and market share.
- **Make Data-Driven Decisions**: Leverage detailed visualizations to inform strategic decisions.

## Getting Started

### Prerequisites

- Microsoft Excel (2016 or later)

### Installation

1. **Clone the Repository**: 
   ```sh
   git clone https://github.com/yourusername/dynamic-retail-dashboard.git
   ```
2. **Open the Excel File**: 
   - Navigate to the cloned repository and open the `Dynamic_Retail_Dashboard.xlsx` file.

## Data Sheets

### Orders

| Column Name     | Description                                                   |
|-----------------|---------------------------------------------------------------|
| Row ID          | Unique identifier for each row                                |
| Order ID        | Unique identifier for each order                              |
| Order Date      | Date when the order was placed                                |
| Ship Date       | Date when the order was shipped                               |
| Ship Mode       | Mode of shipment (e.g., Same Day, Second Class)               |
| Customer ID     | Unique identifier for each customer                           |
| Customer Name   | Name of the customer                                          |
| Segment         | Customer segment (e.g., Consumer, Corporate)                  |
| City            | City where the customer is located                            |
| State           | State where the customer is located                           |
| Country         | Country where the customer is located                         |
| Postal Code     | Postal code of the customer's address                         |
| Market          | Market classification (e.g., US, APAC)                        |
| Region          | Region within the market                                      |
| Product ID      | Unique identifier for each product                            |
| Category        | Product category (e.g., Technology, Furniture)                |
| Sub-Category    | Product sub-category                                          |
| Product Name    | Name of the product                                           |
| Sales           | Total sales amount                                            |
| Quantity        | Quantity of products ordered                                  |
| Discount        | Discount applied on the order                                 |
| Profit          | Profit from the order                                         |
| Shipping Cost   | Cost of shipping the order                                    |
| Order Priority  | Priority level of the order (e.g., Critical, Medium)          |

### People

| Column Name     | Description                                                   |
|-----------------|---------------------------------------------------------------|
| Person          | Name of the person                                            |
| Region          | Region where the person is responsible                        |

### Returns

| Column Name     | Description                                                   |
|-----------------|---------------------------------------------------------------|
| Returned        | Indicates if the order was returned (Yes/No)                  |
| Order ID        | Unique identifier for each returned order                     |
| Market          | Market classification of the returned order                   |

## Steps to Create the Dashboard

1. **Data Preparation**:
   - **Orders Sheet**: Import and clean order data, ensuring all relevant columns are included.
   - **People Sheet**: Import and clean data on people responsible for different regions.
   - **Returns Sheet**: Import and clean return data, ensuring accurate linkage to orders.

2. **Create KPIs**:
   - Define and calculate key performance indicators (KPIs) such as Total Sales, Total Profit, Total Quantity, Number of Orders, and Profit Margin.
   - Use pivot tables and formulas to summarize these metrics.

3. **Build Charts**:
   - **Segment, Category, and Market Analysis**: Create charts to analyze sales by segment, category, and market.
   - **Top 5 and Bottom 5 Analysis**: Create charts for top and bottom performers in terms of sales, profits, and order quantity.
   - **World Map**: Use a map visualization to display the top 10 countries by sales.
   - **Top Sub-Category**: Create charts showing top sub-categories and their contribution to overall sales.
   - **Market Share of Regions**: Create charts to visualize the market share of different regions.
   - **Yearly Sales Trend**: Create a line chart to show sales trends over the years.

4. **Make Charts Dynamic**:
   - Use slicers and filters to make the charts interactive, allowing users to drill down into specific data points.
   - Create a KPI table with dynamic symbols to visually represent key metrics.

## Detailed Solutions for Problem Statements

### 1. Important KPIs – Total Sales, Total Profit, Total Quantity, Number of Orders, Profit Margin
**Solution**:
   - Create pivot tables for each KPI.
   - Calculate the sum of sales, profit, quantity, and count of order IDs.
   - Calculate profit margin using the formula: 
     \[
     \text{Profit Margin} = \left( \frac{\text{Total Profit}}{\text{Total Sales}} \right) \times 100
     \]
   - Display these KPIs in a summary table with dynamic symbols.
![image](https://github.com/user-attachments/assets/13e5dadc-01f9-45f1-a4ae-e85e55323c98)

### 2. Charts Showing Segment, Category, and Market Analysis
**Solution**:
   - Create pivot charts for each analysis.
   - Use segments, categories, and markets as the axis fields.
   - Add data fields for sales, profit, and quantity to visualize their contribution.
![image](https://github.com/user-attachments/assets/4d01ad20-a29f-4ae6-851d-283f25db4a49)

### 3. Top 5 and Bottom 5 Charts for Sales, Profits, Order Quantity
**Solution**:
   - Sort the pivot tables to identify the top 5 and bottom 5 items.
   - Create bar charts to display the top and bottom performers in sales, profits, and order quantity.
![image](https://github.com/user-attachments/assets/53a285b6-9262-4052-8202-053d4c2a50e4)

### 4. World Map Showing the Top 10 Countries by Sales
**Solution**:
   - Use the "Filled Map" chart type in Excel.
   - Plot the top 10 countries by sales on the map.
   - Highlight the sales amount for each country.
     
![image](https://github.com/user-attachments/assets/0ea7cb27-f428-4010-a7ce-5b6d4239b047)

### 5. Top Sub-Category and Their Contribution to Overall Sales
**Solution**:
   - Create a pivot table to list sub-categories and their sales.
   - Calculate the percentage contribution of each sub-category to overall sales.
   - Use a pie chart or bar chart to visualize these contributions.
     
![image](https://github.com/user-attachments/assets/15e85dbd-241e-4e58-a5cb-a1b1019b1d2d)

### 6. Charts Showing the Market Share of Regions
**Solution**:
   - Calculate the market share for each region using the formula:
     \[
     \text{Market Share} = \left( \frac{\text{Region Sales}}{\text{Total Sales}} \right) \times 100
     \]
   - Create a pie chart or doughnut chart to represent the market share of each region.

![image](https://github.com/user-attachments/assets/bad7114d-4d46-45f1-96fb-0fcbd2e7efad)

### 7. Yearly Sales Trend
**Solution**:
   - Create a pivot table to summarize sales data by year.
   - Use a line chart to visualize the trend of sales over the years.

![image](https://github.com/user-attachments/assets/87c9ddc2-3663-4daa-bd41-93666947ef23)

**Visualization**:

![image](https://github.com/user-attachments/assets/51737f90-0a2e-4114-b26e-6ed4b5321a58)
