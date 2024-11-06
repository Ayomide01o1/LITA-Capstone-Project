# LITA-CAPSTONE-PROJECT--- SALES DATA

## RETAIL SALES PERFORMANCE ANALYSIS

### INTRODUCTION
This repository contains data and analysis for evaluating the sales performance of a retail store. The goal is to provide insights into key areas such as top-selling products, regional performance, and monthly sales trends.

### DATASET DESCRIPTION:

- Sales data (transactional)
- Product information (product ID, name, category, price)
- Regional information (store location, region)
- Date information (date, month, quarter, year)

### KEY INSIGHTS
1. Top-selling products
2. Regional sales performance
3. Monthly sales trends
4. Product category sales


### POWER BI DASHBOARD

The dashboard includes:

- Total sales revenue, top 5 customers, regional sales performance
- Product analysis page: Product category sales, product sales trend
- Regional analysis page: Regional sales performance, store-level sales performance, regional sales trend
- Monthly trends page: Monthly sales trend.
  ![Screenshot 2024-11-06 204700](https://github.com/user-attachments/assets/27bee4ba-646b-4714-b61f-59fd18c4dde4)

### TOOLS USED:
- Power BI
  1. Visualization
- Microsoft Excel
  1. Analysis
  2. Visualization
  3. ![Screenshot 2024-11-06 202835](https://github.com/user-attachments/assets/8c89bd07-e986-4508-9c61-99bef0f4251d)

- SQL server
  1. Structured query language for quering data

  ### Data Analysis
  The following are some of the basic line of code/quaries/DAX exressions used during the analysis:
   1. Count of sales = COUNT(SalesData[Sales])
   2. SELECT
      Product,
      SUM(Sales) AS TOTAL_SALES
      FROM
      [LITA Capstone Dataset ]
      GROUP BY 
      PRODUCT;
  3. =SUMIF(D2:D50001,"North",H2:H50001)
  4. =F2*G2
  5. Average = AVERAGE(SalesData[Sales])
 

### Benefits and Decision Making:

The insights gained from this analysis can benefit organizations in Strategic Decision Making in the following ways:

1. Optimize Product Portfolio: Identify top-selling products and categories to inform product development and inventory management decisions.
2. Regional Expansion: Analyze regional sales performance to determine areas for expansion or consolidation.
3. Marketing Strategies: Develop targeted marketing campaigns based on seasonal sales patterns and product category sales.

