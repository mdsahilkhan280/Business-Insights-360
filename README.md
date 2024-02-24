# Business-Insights-360
## Link to my Dashboard
🔷Power BI Service  - https://app.powerbi.com/view?r=eyJrIjoiZTVhZWNmZjMtYTBiYi00YzYwLTkzZTItZWYxYzQ0YmY0YjkwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9

## Overview:
Project: Provide Insights on Finance, sales, Marketing, Supply Chain to the Management.

Domain: Manufacturing Domain

*AtliQ Hardware is a company that Sells and Manufactures Hardware.They have Customers all over the world and Products under various categories.
AtliQ Team use MS excel for data analysis but as the business expands globally company's Top management decides to use Power BI for data analytics.
So Top management wanted the analytics team to Provide insights through SQl to make decisions and as later part of the Project a dashboard to be created for various key departments, so they can get insights on  important metrics and make data driven Decisions*


 ## Task:

* Create an fully functional Dashbord for Data Driven Decisiosn, which gives insights on various departments like Finance, sales, marketing and Supply chain.


## Tech stack used in the project:

* MySQL
* MS Excel
* Power BI

### PowerBI Dashboard

- Established a connection between Power BI, MySQL, and Excel, and implemented a robust data pipeline (ETL) using Power Query. Conducted data transformation and modeling to establish relations following the snowflake schema, and performed initial data validation against benchmark values.
- Utilized DAX to craft calculated columns and measures, crafting a dynamic dashboard featuring KPIs for sales, finance, marketing, and supply chain metrics.
- Published a comprehensive report on the Power BI service for user acceptance testing (UAT), and conducted data validation using Excel Analyze.
- Incorporated stakeholder feedback to develop an Executive Dashboard, addressing quality issues and optimizing performance. Successfully deployed the dashboard to the Power BI service, establishing a gateway for automatic data refresh from MySQL Database and local Excel files.
- Demonstrated proficient project management skills including project charter development, stakeholder mapping analysis, and utilization of Kanban boards for task assignment, enhancing overall productivity.
- Designed a multi-tiered dashboard facilitating in-depth analysis, proficiently addressing stakeholder inquiries regarding top-performing products, markets, customers, percentage changes, and P&L metrics trends. Improved supply chain forecast accuracy for effective inventory management, significantly enhancing overall business performance.
- Crafted intuitive department-specific dashboards, offering a comprehensive overview of company performance tailored to various departments.

✔ Finance View
✔ Sales View
✔ Marketing View
✔ Supply Chain View
✔ Executive View

## Key Features in Finance View:
* The profit and loss Statement, explains on varoius P&L Metrics form Gross Sales to Net Profit.BM indicates the  bench,ark , which is Either Last year or the Target.    which can be selected through Slicer Provided.
* KPI’s for Net Sales, Gross Margin %, Net Profit %.
* Net sales Performance Trend in comparision with Target/Last Year which can be selected Dynamically.
* Top / Bottom Product and Top / Bottom Customers based on Net Sales

## Key Features in Sales View:
* Unit Economics 1: Net Sales vs Total Post Invoice Discount Amount and Pre-Invoice Discount Amount given by the Company
* Unit Economics 2: Total Cost of Goods Sold (COGS) spent by the Company and then finally got the actual Gross Margin
* Customer and Product Performance analysis based on Net Sales, Gross Margin and Gross Margin %
* Performance Matrix analysis for Market, Customer and Region based on Net Sales and Gross Margin %
* Sales Trend Tooltip for every single Customer based on Net Sales and Gross Margin %
  
## Key Features in Marketing View:
* Unit Economics: There are some Operational Expenses spent for Product. After subtracting this Expenses got the actual scenario of Net Profit
* Performance Matrix analysis for Segment, Category and Product based on both “Net Sales & Net Profit %” and “Net Sales & Gross Margin %” by using a dynamic toggle button

## Key Features in Supply Chain View:
* KPI’s for Forecast Accuracy, Net Error, ABS Error
* Risk Factor analysis
* Accuracy vs Net Error Trend analysis
* Key Metrics for both Customer and Products based on FA%, FA% LY, Net Error, Net Error%, Risk Factor

## Key Features in Executive View:
Report Page for the Top Level Management of the Company who want to check on all key metrics and KPI's.
* Market Share Trend analysis for AtliQ and other competitors
* Revenue analysis by Division and Channel
* Top 5 Products and Top 5 Customers by Revenue
* Key Insights by Sub Zone with Revenue Contribution % analysis

## Key Learnings.

* The most helpful measures for senior management are the Gross Margin and Net Profit (Gross Margin - Operational Costs).
* Gross Margin and Net Sales are more significant to the sales team than Net Profit since, in most cases, they have little to no control over operating costs.
* Understanding the changes in marketing spend over time and how those changes affect revenue and gross margin is crucial for the marketing team.
* Forecast Accuracy & Risk (Out of Stock or Excess Inventory) and Net Error & Absolute Error are crucial KPIs for the supply chain team.
* One of the most helpful abilities that aids in the creation of insightful visuals is the managing of stakeholder expectations.
