# 📊 Power BI Sales Analysis Dashboard Project
This project demonstrates the development of a comprehensive Sales Analysis Dashboard in Power BI, fulfilling all requirements outlined in the Business/Functional Requirements Document. The dashboard consolidates sales data, provides meaningful insights, and showcases trends and performance metrics for strategic decision-making.

## Data Sets Used
 - <a href="https://github.com/ridumjeetsingh/Data-Analysis-Sales-Report/blob/main/Data%20Set.zip"> Excel Data Sets </a> 
 - <a href="https://github.com/ridumjeetsingh/Data-Analysis-Sales-Report/blob/main/Sales%20Dashboard%20Image.png"> Image of Dashboard </a> 
 - <a href="https://github.com/ridumjeetsingh/Data-Analysis-Sales-Report/blob/main/Report_of_project.pbix"> Visualisation File In Power Bi Tool </a> 
 
## Project Highlights
## 1. Data Gathering and Automation
-	Consolidated sales data from various file formats (Excel, CSV, Database).
-	Developed a resilient mechanism to load yearly sales data dynamically:
-	Automatically integrates new files added to the sales folder.
-	Handles missing files without causing errors.

## 2. Data Modeling and Transformation
### Data Cleaning and Preparation:
-	Split the "Location" field into Country and City columns for accurate geographical mapping.
-	Adjusted date formats to enable time-series analysis.
-	Custom Function:
-	Created a reusable function to clean and format ID columns in SalesRep and SubCategory tables.
### Data Modeling:
-	Connected all tables using relationships and a prebuilt Calendar Table.
-	Added a unique GeoKey to link the Sales and Geography tables.

## 3. DAX Calculations
### 	Implemented key measures for actionable insights:
-	Total Revenue: Product’s Retail Price × Units Sold.
-	Total Cost: Product’s Standard Cost × Units Sold.
-	Gross Profit: Total Revenue - Total Cost.
-	Gross Profit MoM Growth %: Month-over-Month growth rate for profit.
-	Average Sales per Day: Average Total Revenue per sales day.
-	QoQ Growth: Quarter-over-Quarter growth for the Quarterly Business Review (QBR) report.
-	Product-Level Breakdown: Analyzed trends for product performance (drop or increase).

## 4. Visualizations
Designed a one-page interactive dashboard to showcase sales insights:
•	KPI Cards: Display key metrics such as Total Revenue, Gross Profit, and Average Sales per Day.
•	Geo Maps: Highlight sales performance by Country and City.
•	Bar and Line Charts: Track MoM and QoQ growth, and compare sales across categories.
•	Product Analysis Visuals: Identify top-performing and underperforming products.
•	Sorted Month Axis: Ensures months are arranged from January to December for clarity.
![Sales Dashboard Image](https://github.com/user-attachments/assets/5ab86533-3fa5-4cbe-baee-81aad552b17f)


## Key Features and Outcomes
-	Dynamic Data Handling: Seamless integration of new or missing data files without errors.
-	Actionable Insights: Comprehensive metrics and trends for better decision-making.
-	Professional Design: Engaging visuals to communicate complex insights clearly.

## Technology Stack
-	Power BI: For visualization and dashboard creation.
-	DAX (Data Analysis Expressions): For advanced metrics and calculations.
-	ETL (Extract, Transform, Load): To clean and transform data for modeling.

## Future Enhancements
-	Add support for more dimensions, such as customer demographics or product reviews.
-	Automate dashboard updates with real-time data.

