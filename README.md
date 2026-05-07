#  Revenue and Cost Analysis

##  Description

This project presents a full-cycle sales data analysis for an international company operating through both offline stores and online sales channels.


##  Data Sources

The project is based on three datasets:

- `events.csv` — sales data collected over several years  
- `products.csv` — product and category information  
- `countries.csv` — countries and regions information  


##  Data Analysis

At the initial stage, the following steps were completed:

- explored the data structure  
- described columns in each table  
- identified key fields used for merging:
  - `product_id`
  - `country_code`


##  Data Cleaning

A full data cleaning process was performed.

### Missing Values Handling

- analyzed the percentage of missing values  
- identified possible causes of missing data  
- applied:
  - missing value imputation  
  - removal of data that did not affect the current analysis  

### Data Types

- validated column data types  
- performed datatype conversions (`datetime`)  

### Additional Data Quality Checks

- identified duplicates  
- resolved issues caused by inconsistent letter casing  
- checked data for anomalies and outliers  


##  Final Analytical Dataset Preparation

- merged all tables into a single dataframe  
- removed unnecessary columns  
- renamed fields for better readability  
- added calculated fields required for further analysis  


##  Key Metrics

The following business metrics were calculated:

- total number of orders  
- total revenue  
- total profit  
- total costs  
- number of countries  
- number of product categories  
- average order value  


## Sales Analytics

### Product Category Analysis

- analyzed costs, revenue, and profit by product category using pivot tables  
- analyzed sales, revenue, profit, and costs by category across sales channels (online/offline)  

### Geographic Analysis

- analyzed sales, revenue, costs, and profit by country  
- identified the most and least profitable countries  

### Sales Channel Analysis

- analyzed online and offline sales across regions  
- compared channel contribution to sales, revenue, costs, and profit  


##  Order Processing Time Analysis

Analyzed the time between order placement and shipment:

- by product category  
- by country  
- by region  
- by sales channel (online/offline)  

Additionally, the impact of delivery time on profit was investigated.


##  Trend Analysis

Performed sales trend analysis, including:

- overall sales dynamics over time  
- trends by:
  - product categories  
  - top-10 countries  
  - regions  


##  Sales by Day of Week

Analyzed sales performance by weekday:

- identified the most profitable days  
- detected possible product seasonality  


##  Visualizations

The analysis includes the following visualizations:

- line charts (trend analysis)  
- bar charts (comparisons)  
- scatter plots (relationship analysis)  


##  Results

The project helped identify:

- regions and countries with the highest sales  
- the most profitable product categories  
- the impact of delivery time on profit  
- seasonality patterns in sales  
- key sales and revenue trends over time  

## Technologies Used

- Python (`pandas`, `numpy`)  
- Data Visualization (`matplotlib`, `seaborn`)  
- Google Colab  
