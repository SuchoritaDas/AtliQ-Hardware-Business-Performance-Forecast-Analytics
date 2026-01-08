# AtliQ-Hardware-Business-Performance-Forecast-Analytics
A business-focused Power BI project for AtliQ Hardware that analyzes sales, profit, and 2022 forecasts across markets and channels, using SQL, Excel, and automated data refresh to support data-driven decisions.

AtliQ Hardware is an omnichannel consumer electronics company that sells products such as mouse, keyboard, and accessories through retail stores, online marketplaces, and its own direct-to-consumer platform. The company operates across India, APAC, Europe, and Latin America.
After COVID, AtliQ saw strong revenue growth, but leadership began to notice that profits were not increasing at the same pace. Some regions were selling more but earning less. At the same time, the company had ambitious 2022 targets, but there was no clear way to track whether those goals would be achieved. Reporting was mostly done in Excel, which made it difficult to understand where the business was really making or losing money.
This project was built to solve that problem by creating a centralized business intelligence system that shows sales, cost, profit, growth, and 2022 forecast vs target in one place.
This created a situation where leadership was making decisions without knowing:
◉ Where profits were being generated
◉ Where margins were collapsing
◉ Whether 2022 goals were at risk

## What I was asked to do
I was responsible for building a centralized analytics system that would:
Combine SQL and Excel data into a single source of truth
Track sales, cost, profit, and margins
Compare 2022 forecast vs 2021 actuals
Compare 2022 forecast vs targets
Highlight loss-making markets and low-margin channels
Give leadership a real-time, decision-ready view of the business

## Business Situation
◉ AtliQ was growing in revenue, but leadership was struggling to understand why profit was not growing at the same pace.
◉ Some regions, especially Latin America, were showing higher sales but falling profit.
◉ At the same time, the company had set 2022 sales and profit targets, but Excel-based reporting could not clearly show whether those targets would be met.
◉ There was no single, trusted view of actual vs last year vs forecast vs target.

## Tools & Data Integration
The full analytics pipeline was built using:
◉ MySQL to store daily transactional data
◉ Excel for targets, forecasts, and reference data
◉ SharePoint to store Excel files in the cloud
◉ Power BI Desktop to clean data, build the model, and create KPIs and dashboards
◉ Power BI Service to publish, share, and refresh dashboards
◉ Data Gateway to connect the SQL database to the cloud
◉ DAX Studio to optimize performance and reduce PBIX size
◉ Canva to design professional presentation slides

## How the System Works
◉ Sales data is recorded daily in MySQL
◉ Forecast and target data is maintained in Excel
◉ Excel files are uploaded to SharePoint
◉ Power BI connects to both SQL and SharePoint
◉ Data is modeled and analyzed in Power BI Desktop
◉ Dashboards are published to Power BI Service
◉ SQL and SharePoint sync automatically through the gateway
◉ Dashboards always show up-to-date data

## Key KPIs Used
◉ The dashboards track and analyze:
◉ Total Revenue
◉ Cost of Goods Sold
◉ Gross Profit
◉ Net Profit
◉ Profit Margin
◉ Year-over-Year Growth
◉ Market Performance
◉ Channel Performance
◉ Product Performance
◉ Customer Contribution
◉ 2022 Forecast
◉ 2022 Target
◉ Forecast vs Target Gap

## What the analysis revealed
The dashboards made it clear that AtliQ's growth:

◉ Finance View – Profit & Loss Control
The P&L dashboard showed that Latin America had ~12% sales growth but a ~5% decline in profit, making it the most financially unstable region.
Gross margin was significantly lower in marketplace sales compared to D2C, proving that higher revenue did not mean higher profitability.
Finance teams could track Net Profit, Margin %, and YoY change for every market, preventing hidden losses.

◉ Sales View – Growth Quality
Sales growth was driven mainly by E-commerce, which contributed nearly 50% of total revenue.
However, this channel delivered less than 30% of total profit, showing that heavy discounts were hurting the business.
The dashboard helped sales teams see that volume growth without margin control was dangerous.

◉ Marketing View – Channel Effectiveness
D2C had lower sales volume but delivered the highest profit per unit, making it the most valuable channel for long-term growth.
Marketing could compare conversion and revenue vs margin to decide where promotions should be focused.
Instead of pushing all channels equally, teams could now prioritize high-return channels.

◉ Supply Chain View – Cost & Forecast Risk
The dashboard showed where costs were increasing faster than sales, especially in Latin America.
Forecast vs actual helped identify regions where inventory and logistics costs were rising without profit support.
Supply chain could align inventory planning with real profit-generating demand instead of just sales volume.

◉ Executive View – Company Performance
The company was forecasted to grow revenue by ~18% in 2022, but profit was expected to grow only ~7%, highlighting a ~11% gap between sales growth and profit growth.
Forecast vs target showed AtliQ was at risk of missing its 2022 profit target by ~8–10%.
Leadership could immediately identify which regions and channels were driving profit and which were destroying it instead of relying on total revenue alone.


## Key Business Impact
◉ +18% Revenue Visibility
Enabled leadership to track the full 2022 revenue forecast (~18% growth) against last year and targets in one dashboard.
◉ +7% Profit Growth Reality
Revealed that although sales were rising, profit was growing only ~7%, exposing hidden margin pressure.
◉ 8–10% Profit Risk Identified
Forecast vs target analysis showed the company was likely to miss its 2022 profit goal by ~8–10% without corrective action.
◉ Latin America Risk Exposed
Detected ~12% sales growth but ~5% profit decline in Latin America, helping leadership focus on the highest-risk market early.
◉ Channel Profitability Clarity
Showed that e-commerce produced ~50% of revenue but <30% of profit, while D2C delivered the highest profit per unit.
◉ Faster, Data-Driven Decisions
Replaced Excel with real-time Power BI dashboards, enabling leadership to monitor P&L, forecast, and targets instantly instead of monthly.
◉ One Single Source of Truth
Unified SQL + Excel data into one automated system, eliminating inconsistent reports and manual reconciliation.

## What this project tracks
The analytics system is designed around how leadership actually runs the business. It tracks total revenue, cost of goods sold, gross profit, net profit, and profit margins. It also measures year-over-year growth so performance can be compared with the previous year, and it includes 2022 forecast and target values so future risk can be seen early.
These numbers are not shown only at a company level. They are broken down by market, sales channel, product, and customer, which allows management to see exactly where performance is strong and where it is weak.

## How to explore this project
This project is published as a live, interactive Power BI dashboard.
The GitHub repository contains the project explanation and supporting material, while the dashboard link lets you interact with the data directly.
Inside the dashboard, you can filter by year, market, channel, and product to see how sales, profit, and forecast numbers change — exactly how leadership would use it in real business reviews.
