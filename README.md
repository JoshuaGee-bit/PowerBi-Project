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

![Image_alt](https://github.com/JoshuaGee-bit/PowerBi-Project/blob/c43bb5ebd2b670b4b0d33c55d342c3cdec1a92e3/Screenshot%202025-07-23%20195857.png)

## Key Insights 


### Product Analysis 
1. **Which product categories generate the highest profits?**
- Toys are the most profitable, contributing $1.08M (26.89%) of total profits. 
- Electronics follow closely with $1M (25%). 
- Sports & Outdoor products generate the lowest profit at $500K.
  
2. **Are these profit trends location-dependent?** 
- Electronics dominate in Airport and Commercial locations. 
- Toys perform best in Downtown and Residential areas.
  
3. **Top Performing Products**
Highest Profit-Generating Products: 
1. Colorbuds - $835K 
2. Action Figure - $348K 
3. Lego Bricks - $298K 
4. Deck of Cards - $252K 
5. Glass Marbles - $190K

4. **Most Sold Products:**
1. Colorbuds - 104K units (23.5%) 
2. Playdoh Can - 103K units (23.2%) 
3. Barrel O’Slime - 91K units 
4. Deck of Cards - 84K units 
5. Magic Sand - 61K units

![image_alt](
   
• Notably, Playdoh Can ranks high in sales volume but not in profitability. 
Store & Location Analysis 
Which locations generate the highest profits? 
• Downtown stores lead with over $2M in profits. 
• Airport stores yield the lowest profit at $378K. 
Most Profitable Stores: 
1. Maven Toys Ciudad de Mexico 2 - $170K 
2. Maven Toys Guadalajara 3 - $121K 
3. Maven Toys Ciudad de Mexico 1 - $111K 
4. Maven Toys Monterrey 2 - $107K 
5. Maven Toys Toluca - $105K 
Least Profitable Stores: 
• Maven Toys Cuernavaca 1 - $57K 
• Maven Toys La Paz 1 - $57K 
Seasonal Trends & Patterns 
• Peak Sales & Profits: March–July 
o Highest Sales: April (112K units) 
o Highest Profit: March ($406K) 
• Lowest Sales & Profits: October 
o Sales: 48K units 
o Profit: $179K 
• Quarterly Trends: 
o Q2 (April–June): Highest sales 
o Q4 (October–December): Lowest sales 
Yearly Trends: 
• 2017: Sales peaked towards year-end. 
• 2018: Stronger sales from February–July, with March leading.
