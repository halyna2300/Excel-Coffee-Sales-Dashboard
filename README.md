<h1 align="center">Excel-Coffee-Sales-Dashboard</h1>

<p align="center">
  <img src="https://github.com/halyna2300/Excel-Coffee-Sales-Dashboard/blob/main/Coffee%20Sales%20Dashboard%20Picture.jpg"/>
</p>

## Project Overview
This project focuses on cleaning, preparing, and analyzing coffee sales data to uncover business insights and build an interactive dashboard. The goal is to support decision-making through data-driven insights on customer behavior, product performance, and regional sales trends.

## Tools Used
- Microsoft Excel
- Pivot Tables
- Slicers
- Data Cleaning Techniques

## Data Cleaning & Preparation Steps
1. Standardized Column Names  
   Ensured uniform naming conventions for easier formula referencing and consistency.

2. Handled Missing Values  
   Checked critical fields like Customer Email, Loyalty Card, and Address. Missing emails were left blank, avoiding imputation that could skew results.

3. Corrected Data Types  
   - Converted *Order Date* to date format  
   - Converted *Quantity*, *Unit Price*, and *Sales* to numerical types for accurate calculations

4. Standardized Coffee and Roast Type Names  
   - Mapped codes like "Ara" to "Arabica", "Rob" to "Robusta", etc.  
   - Translated roast types: "L" to "Light", "M" to "Medium", etc.

5. Created Calculated Fields  
   - Sales = Quantity × Unit Price  
   - Price per 100g = Unit Price / Size × 100  
   - Profit = Sales – Estimated Cost (based on internal pricing strategy)

## Pivot Tables & Key Insights
1. Total Sales by Country  
   - Purpose: Identify top-performing markets  
   - Insight: The United States and Ireland are the biggest revenue contributors

2. Top 5 Customers by Sales  
   - Purpose: Recognize high-value customers  
   - Insight: A few customers generate a significant portion of total revenue

3. Product Performance (by Coffee Type & Roast Type)  
   - Purpose: Analyze best-selling products  
   - Insight: Arabica and Robusta are top coffee types; Medium and Light roasts are preferred

4. Monthly Sales Trend Analysis  
   - Purpose: Track sales seasonality  
   - Insight: Sales vary month to month, revealing seasonal demand patterns

5. Customer Loyalty Analysis  
   - Purpose: Understand impact of loyalty programs  
   - Insight: Loyalty card holders spend more on average, supporting the promotion of such programs

## Interactive Dashboard Features

Slicers Added for Filtering:
- Date Slicer – Filter by year, quarter, or month to analyze time-based trends  
- Country Slicer – Drill down into country-specific sales data  
- Coffee Type Slicer – Filter by types like Arabica, Robusta, Excelsa  
- Roast Type Slicer – Analyze customer preferences by roast level  
- Loyalty Card Slicer – Compare behavior of loyalty members vs non-members

## Key Business Insights
- The U.S. and Ireland are major sales hubs
- Arabica and Robusta dominate customer preferences
- Medium and Light roasts outperform Dark roasts
- Loyalty members purchase more per order, indicating strong retention value
- Seasonal trends exist, useful for inventory and marketing planning

## Final Thoughts
This project demonstrates how well-structured data preparation and analysis in Excel can uncover meaningful insights. It also highlights the power of pivot tables and slicers in building a dynamic, user-friendly dashboard.
