# Amazon Sales Dashboard in Power BI
## project-Objective
The objective of this project is to design and develop an interactive Power BI dashboard that provides comprehensive insights into Amazon sales performance. The goal is to help stakeholders monitor key sales metrics, identify trends, and make data-driven decisions to improve overall business efficiency and profitability.
## Dataset used
- <a href= "https://github.com/Pdibyajyotipalei/Data-analysis-Dashboard/blob/main/Amazon%20Store%20Sales%20Data.xlsx%20-%20Sheet1%20(1).xlsx">Dataset </a>
## Questions(KPIs)

- Which shipping mode is most frequently used for product deliveries?
- What is the most preferred payment method by customers (Cards, COD, Online)?
- What percentage of orders are returned?
- Which U.S. states are generating the highest sales?
- How do sales and profits vary by region (East, West, Central, South)?
- Which quarter had the highest sales and profit?
- Which months had peak sales volume?
- Which sub-category (Phones, Accessories, Copiers, etc.) drives the most profit?

- Dashbord Interaction <a href="https://github.com/Pdibyajyotipalei/Data-analysis-Dashboard/blob/main/amazon.pbix" >View Dashbord</a>
## process
Get the Data
I used Excel or CSV file with Amazon sales details like:
Order ID, Product Name, Category, Region, Segment
Sales, Profit, Shipping Mode, Payment Mode, etc.

2️⃣ Clean the Data
Opened data in Power Query.
Removed errors or blanks.
Changed data types (dates, numbers, text).
Created new fields like:
Total Cost = Sales - Profit

3️⃣ Build Relationships
Linked the tables (Orders, Products, Region) using keys.
Followed a star schema to keep things organized and fast.
4️⃣ Create Measures (Formulas)
Used DAX to calculate:
Total Sales
Total Profit
Profit Margin
Returns %
Sales by Month or Segment

5️⃣ Design the Dashboard
Used charts like:
Donut charts for ship mode and payment mode
Map for sales by state
Bar/Column charts for profit by category/sub-category
Line chart for monthly sales trends
Used slicers to filter by State and Region

6️⃣ Make It Interactive
Click on one chart → see all visuals update.
Used tooltips and colors to improve user experience.










Ask ChatGPT

