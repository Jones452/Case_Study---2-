# Case_Study---2-
Bright_TV
Recently, Bright Motors hired a new Head of Sales, whose goals are to increase dealership network size, boots sales and maximize inventory. To derive useful insights, identify issues and offer suggestions to direct future sales and marketing strategies, this project analyses past auto sales data.
 
Objective
•	Analyse historical vehicle sales data (bright.car.sales)
•	Identify trends, top-performing models, manufacturers, and seasonal patterns.
•	Evaluate profitability and margin performance.
•	Provide insights and recommendations for sales, inventory, and pricing strategy.

Data Source
•	Dataset: bright.car.sales
•	Key Columns:
o	year, make, model, trim, body, transmission, vin, state, condition, odometer, color, interior, seller, mmr, sellingprice, saledate
Derived Metrics:
•	profit_vs_mmr = Selling Price – MMR
•	profit_margin_pct
•	profit_tier (High, Medium, Low, Loss)
•	market_position (Above/At/Below Market)
•	Date parts: Year, Month, Quarter, Weekday

Analysis Summary
•	Top-Selling Models: Altima, F-150, Fusion
•	Profitability: 51% of vehicles sold below MMR; only ~5% generate medium or high profit
•	Seasonal Trends:
o	Q3 and July → highest selling prices
o	Q4 → lowest selling prices; clearance-focused period
•	Manufacturer Margins: manufacturers consistently show negative average margins.

Pivot Tables & Visualizations
•	Sales by Model, Manufacturer, and Month/Quarter
•	Profit Tier Distribution
•	Seasonal & Yearly Trends
•	Charts: Column, Bar, Line and Pie

Key Problems Identified
1.	Pricing & Profitability: High proportion of below-MMR sales reduces overall profitability
2.	Inventory & Demand Alignment:  low-demand models are overstocked, while high-demand vehicles could be prioritized

Recommendations
•	Set inventory priorities for top-selling models and high-margin cars.
•	Review pricing strategies to lower losses and increase margins.
•	Seasonally adjust inventory to correspond with periods of high demand (Q2–Q3).
•	Monitor manufacturers and models with negative margins.
•	Implement dashboards for continuous sales, margin, and model performance.

Project Timeline
Duration: 1 week (can be accelerated to 3 days for a crash plan)
Key Tasks:
Data Extraction & Cleaning
Exploratory Analysis
Pivot Tables & Visualizations
Insights & Recommendations
Presentation Preparation & Submission

Deliverables
1.	Cleaned and transformed dataset
2.	Pivot tables and visualizations
3.	Insights and recommendations report
4.	Power point presentation slides
5.	Gantt chart and miro project plan

Tools Used
•	Databricks SQL – Data extraction and transformations
•	Excel  – Pivot tables, charts, dashboards
•	Miro – Project flow and visualization mapping
•	PDF / PPTX – Deliverable reporting



