                                           # Amazon-Sales-Analysis

# Amazon Sales Analysis Dashboard


## Overview
This project showcases an in-depth analysis of Amazon's sales data using a Tableau dashboard, with data hosted on a MySQL localhost server. The dashboard provides insights into key sales metrics, including total revenue, profit, and sales trends across different regions, item types, and sales channels.


## Key Metrics
- **Total Profit**: $797.10M
- **Total Revenue**: $2,409.67M
- **Average Shipment Days**: 24.31 days
- **Number of Units Sold**: 9.09M


## Data Source
The dataset used in this analysis contains the following fields:
- **Country**: Country where the sale occurred
- **Item Type**: Type of product sold (e.g., Cosmetics, Office Supplies, etc.)
- **Order Date**: Date when the order was placed
- **Order ID**: Unique identifier for each order
- **Order Priority**: Priority level of the order (Low, Medium, High, Critical)
- **Region**: Geographical region of the sale
- **Sales Channel**: Mode of sale (Online or Offline)
- **Ship Date**: Date when the order was shipped
- **Total Cost**: Total cost incurred for the order
- **Total Revenue**: Revenue generated from the order
- **Units Sold**: Number of units sold


## Insights



### 1. **Region-Wise Profit**
- **Top-Performing Regions**:
  - Sub-Saharan Africa: $225.41M in revenue
  - Europe: $190.92M in revenue
  - Middle East & North Africa: $126.27M in revenue
- The dashboard highlights the performance of specific countries like the Democratic Republic of the Congo and the United Kingdom.


### 2. **Sales Channel Performance**
- **Offline Sales**: 59.15% of total revenue
- **Online Sales**: 40.85% of total revenue


### 3. **Order Priority Analysis**
- **High Priority Orders**: 522 orders with $339.61M in profit
- **Medium Priority Orders**: 477 orders with $205.82M in profit
- **Critical Priority Orders**: 378 orders with $115.47M in profit
- **Low Priority Orders**: 333 orders with $136.20M in profit


### 4. **Revenue Trends by Year**
- The dashboard visualizes revenue trends from 2010 to 2017, showing steady growth in the Asia region.
- North America shows some fluctuations due to economic and consumer behavior changes.


### 5. **Item Type Analysis**
- **Top Revenue-Generating Items**:
  - Cosmetics: $724.38M in revenue
  - Office Supplies: $530.62M in revenue
  - Household: $469.81M in revenue
- **Cost and Profit Breakdown**:
  - Cosmetics: $436.30M in cost, yielding $288.08M in profit
  - Office Supplies: $353.29M in cost, yielding $102.87M in profit


## Tools Used
- **MySQL**: Used as a localhost server to store and query the Amazon sales dataset.
- **Tableau**: For creating the interactive data visualizations and dashboard.
- **Data Source**: The dataset was provided in CSV format and imported into MySQL for querying and further analysis.



Conclusion
This Amazon Sales Analysis dashboard offers valuable insights into the company’s performance across regions, item types, and sales channels. By using MySQL for data management and Tableau for visualization, this project highlights the power of data analytics in uncovering key business insights.
