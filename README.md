# Maven Toy Store Analysis


## Project Overview
This analysis evaluates sales and inventory data from Maven Toy Store, a toy retail chain in Mexico. Using Microsoft Power BI, key insights were derived on product profitability, store performance, seasonal trends, and inventory management. Findings revealed that Toys and Electronics drive the highest profits, with Downtown stores performing best. Sales peak between March and July, while October sees the lowest revenue. Inventory analysis indicates stock will last 15-17 days. Recommendations include optimizing inventory, investing in high-performing locations, and addressing seasonal sales fluctuations to enhance profitability and business growth.


![image alt](https://github.com/JoshuaGee-bit/PowerBi-Project/blob/1b29b187cd14e1241c2516f5e2d9e514987511c5/Screenshot%202025-07-23%20195934.png)


## Table of Content


## Objectives of the Analysis 
The primary goal of this analysis is to generate actionable insights into Maven Toy Store's overall sales 
performance and profitability by evaluating: 
1. Store location performance 
2. Seasonal sales trends 
3. Product profitability and sales effectiveness
   
Based on these findings, recommendations will be provided to optimize business strategies.

## Key Business Questions 
1. Which product categories yield the highest profits, and how do these trends vary across different store locations? 
2. Are there identifiable seasonal sales patterns? 
3. What is the company's current market reach in terms of store distribution and geographic presence? 
4. What is the total inventory value, and how long can it sustain current sales levels? 
5. Which stores perform best and worst in terms of revenue and profitability?

## Tools and Methodologies 
### Tool Used:** **Microsoft Power BI**  [Website](https://www.microsoft.com/en-us/power-platform/products/power-bi)

### Techniques 
• Data Cleaning & Transformation using Power Query 
• Data Modeling to establish structured relationships between tables 
• DAX Implementation for advanced calculations and metrics 
• Data Visualization for interactive and insightful dashboards 
• Comprehensive Project Documentation for clear reporting of insights

## Data Processing 

### Data Importation and Cleaning 

Importation Process: 
• Data was ingested using Power BI’s Excel connector. 

### Cleaning Steps: 
• Promoted headers for consistent column naming. 
• Converted ID columns from whole numbers to text (as they serve as unique identifiers rather than numerical values). 
• Added calculated fields for total product cost, total product price, and profit in the sales dataset. 
• Corrected data types to ensure consistency. 
• Trimmed redundant store names in the Stores Table for clarity. 
• Created a Dates Table using CALENDARAUTO() to facilitate temporal analysis, extracting year, quarter, month, and day attributes. 

### Data Modeling 
Effective data modeling structures raw data into an analytical framework, allowing seamless relationship-building between tables. In this project, Power BI automatically identified table relationships, forming **a star schema model**: 
• Fact Table: Sales Table, Inventory 
• Dimension Tables: Products, Stores, and Dates

![Image_alt]()
