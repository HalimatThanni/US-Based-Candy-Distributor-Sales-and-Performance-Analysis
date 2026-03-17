# Candywood Sales, Profitability & Target Performance Analysis
### Transforming Raw Sales Data into Business-Critical Insights (Using Excel Only)
![images](https://github.com/user-attachments/assets/e8338740-55c1-41d3-8976-1a85039d4687)


## Project Overview
Data is only valuable when it tells a story, and more importantly, when that story drives decisions.

Candywood, a U.S.-based candy distributor, operates across multiple states, supplying products from different factories and divisions. Despite having consistent sales activity, the business lacked a centralized, data-driven system to evaluate performance across key areas.

This project was built to transform fragmented operational data into a structured analytical model and an interactive dashboard that provides clear visibility into:
* Revenue performance over time
* Profitability across products, states, and divisions
* Operational efficiency in order fulfillment
* Sales performance against predefined targets
The end result is a decision-support dashboard that empowers stakeholders to move from assumptions to actionable insights.

## Business Problem
As Candywood expanded, management faced increasing difficulty answering critical questions such as:
* Which products and divisions are truly driving revenue?
* Are we meeting our sales targets consistently?
* Where are we losing profit despite strong sales?
* How efficient is our delivery process?
* Which regions require strategic attention?
Without a unified analytical view, decision-making remained reactive, limiting growth opportunities and operational efficiency.

## Tools & Technologies
* Microsoft Excel
    * Power Query (Data Cleaning & Transformation)
    * Power Pivot (Data Modeling)
    * DAX (Measures & KPIs)
* Data Modeling Technique: Star Schema
* Visualization: Interactive Excel Dashboard


## Dataset Description
The dataset consists of four core tables:

  #### Sales (Fact Table)
Transactional data including:
* Order ID
* Order Date & Ship Date
* Product Name
* State
* Ship Mode
* Units Sold
* Revenue
* Cost
* Gross Profit

#### Products (Dimension Table)
* Product Name
* Division
* Factory
* Unit Price
* Unit Cost

#### Factories (Dimension Table)
*Factory Name
Geographic Coordinates (Latitude & Longitude)

#### Targets (Dimension Table)
* Division-level sales targets:
    * Chocolate: 27,000
    * Sugar: 15,000
    * Other: 3,000

#### Date Table (Created)
Custom calendar table to support time-based analysis



## Data Preparation & Modeling

### Data Cleaning (Power Query)

* Converted date fields using locale (United Kingdom) to ensure accuracy
* Standardized numeric fields (Revenue, Cost, Profit, Units)
* Validated consistency across all tables

### Data Modeling (Power Pivot)
* Designed a Star Schema Model:
    * Central Sales Fact Table
    * Connected to Products, Factories, Targets, and Date tables
* Established relationships for accurate aggregation and filtering

### Feature Engineering
* Created Shipping Duration (Days):
    * Calculated as the difference between Order Date and Ship Date
    * Enabled operational efficiency analysis

### Key Metrics (DAX Measures)
The following KPIs were developed to evaluate business performance:
* Total Revenue
* Total Profit
* Total Cost
* Total Units Sold
* Profit Margin (%)
* Revenue Last Year
* Year-over-Year Growth (%)
* Average Shipping Duration
* Target Sales
* Target Achievement (%)

These measures form the backbone of the dashboard, enabling both high-level and granular analysis.


## Dashboard Overview
The project features a 2-page interactive dashboard:

### Page 1: Executive Sales & Target Overview
Designed for quick decision-making by stakeholders:
* KPI Cards (Revenue, Profit, Target Achievement)
* Revenue Trend (Monthly)
* Actual vs Target Performance
* Revenue by State
* Profit Margin by Division

<img width="524" height="307" alt="Halimat&#39;s Dasboard 1b" src="https://github.com/user-attachments/assets/fb8b5e16-28d7-4bea-9bc3-b553887df3f7" />


### Page 2: Operational Efficiency & Product Deep Dive
Focused on detailed performance insights:
* Top 10 Products by Revenue
* Revenue by Factory
* Average Shipping Duration by Ship Mode
* Top 10 States by Profit

<img width="533" height="305" alt="Halimat&#39;s Dasboard 2b" src="https://github.com/user-attachments/assets/86845333-1e63-416b-897e-40ad55981ec4" />


### Interactivity
* Slicers for Year, Region, and Country
* Enables dynamic exploration of the data

## Key Insights & Business Findings
#### Revenue Trends & Seasonality
Revenue patterns revealed clear fluctuations across months, suggesting seasonal demand cycles. This presents an opportunity for better forecasting and campaign timing.

#### Target Performance Gaps
While some divisions performed strongly, others consistently underachieved. This indicates uneven performance across product categories, requiring targeted interventions.

#### Product Concentration
A small number of products generated the majority of revenue, highlighting a Pareto (80/20) effect. Business success is heavily reliant on a limited product set.

#### Factory Performance Variance
Factories contributed unevenly to total revenue, suggesting differences in production efficiency, demand alignment, or distribution effectiveness.

#### Shipping Efficiency Challenges
Delivery times varied significantly by shipping mode, pointing to potential inefficiencies that may affect customer satisfaction and retention.

#### Regional Profitability Issues
Some states delivered strong revenue but low profit margins, indicating cost inefficiencies or suboptimal pricing strategies in those regions.


## Strategic Recommendations
### Optimize Product Strategy
* Prioritize high-performing products
* Ensure consistent supply and promotion

### Address Underperforming Divisions
* Reevaluate pricing and marketing strategies
* Align offerings with customer demand

### Improve Logistics & Delivery
* Optimize shipping modes to reduce delivery time
* Enhance operational efficiency

### Refine Regional Strategy
* Investigate low-profit regions
* Adjust pricing or reduce operational costs

### Leverage Data for Forecasting
* Use historical trends for demand planning
* Align inventory and campaigns with peak periods


## What This Project Demonstrates
This project highlights my ability to:
* Design and implement end-to-end data analysis solutions
* Build scalable data models using a star schema
* Develop business-relevant KPIs using DAX
* Translate complex data into clear, actionable insights
* Create dashboards that support strategic decision-making
* Communicate findings through data storytelling


## Conclusion
This project goes beyond visualization, it delivers a business intelligence solution that enables Candywood to:
* Monitor performance in real-time
* Identify growth opportunities
* Improve operational efficiency
* Make informed, data-driven decisions


## Let’s Connect
If you found this project insightful or would like to collaborate, feel free to connect with me on LinkedIn at Halimat Thanni or explore more of my work here.
