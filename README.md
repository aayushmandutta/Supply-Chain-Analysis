# Supply-Chain-Analysis
# Supply Chain Analysis & Power BI Dashboard

## Project Overview

This project analyzes the supply chain operations of **GlowCare Pvt Ltd**, a cosmetics and personal care company, using **Power BI and DAX**.

The objective of the project is to evaluate supply chain performance across **revenue generation, supplier performance, transportation costs, manufacturing efficiency, inventory levels, product quality, customer demographics, and logistics operations**.

An interactive Power BI dashboard was developed to transform raw supply chain data into meaningful business insights and support data-driven operational decision-making.

## Business Objectives

* Evaluate overall supply chain performance.
* Analyze revenue contribution across product categories and locations.
* Compare supplier lead times and defect rates.
* Identify transportation modes and routes with high operational costs.
* Analyze manufacturing costs against production volumes.
* Identify inventory and sales mismatches.
* Evaluate product quality through inspection results and defect rates.
* Understand customer demographic contribution to revenue.
* Provide recommendations for improving supply chain efficiency.

## Dataset

The dataset contains information related to:

* Product Type
* SKU
* Price
* Availability
* Number of Products Sold
* Revenue Generated
* Customer Demographics
* Stock Levels
* Lead Times
* Order Quantities
* Shipping Times
* Shipping Carriers
* Shipping Costs
* Supplier Name
* Supplier Location
* Manufacturing Lead Time
* Production Volumes
* Manufacturing Costs
* Inspection Results
* Defect Rates
* Transportation Modes
* Routes
* Transportation Costs

## Data Cleaning & Preparation

The dataset was prepared before dashboard development by:

* Removing unnecessary rows.
* Promoting the correct row as the column header.
* Converting columns to appropriate data types.
* Removing duplicate and blank values.
* Improving dataset consistency and accuracy.
* Preparing data for Power BI analysis.
* Creating DAX measures for KPI calculations.

## Tools & Technologies

* **Power BI**
* **DAX**
* **Data Cleaning & Transformation**
* **Data Visualization**
* **Business Intelligence**
* **CSV Dataset**

## Dashboard KPIs

The executive dashboard includes key performance indicators such as:

* Total Revenue
* Average Defect Rate
* Pass Rate Percentage

These KPIs provide a high-level view of business performance and product quality.

## Key Dashboard Analyses

### 1. Revenue by Order Quantity

Order quantity bands were analyzed to understand how order size affects revenue.

The analysis showed that smaller and medium-sized orders contributed significantly to total revenue, while revenue decreased across the larger order bands.

**Insight:** Efficient fulfillment of smaller and medium-sized orders is important because these segments form a major portion of order revenue.

### 2. Manufacturing Cost vs Production Volume

Manufacturing costs were compared with production volumes to evaluate cost behavior and potential economies of scale.

The analysis showed relatively stable average costs across production volumes, with some high-cost outliers, particularly in skincare production.

**Insight:** High-cost production points can be investigated to identify setup costs, process inefficiencies, or opportunities for manufacturing optimization.

### 3. Transportation Cost Analysis

Transportation costs were compared across air, road, rail, and sea.

* Air transportation had the highest average cost.
* Road and rail showed similar cost levels.
* Sea transportation was the lowest-cost transportation mode.

**Insight:** Sea transportation can be considered for non-urgent bulk shipments where longer delivery times are acceptable.

### 4. Revenue by Customer Demographics

Revenue was analyzed across customer demographic categories.

The dashboard identified a significant contribution from the unknown demographic category, while female customers also contributed substantially to revenue.

**Insight:** Improving customer data collection and CRM systems can provide better customer profiling and support more accurate demand planning.

### 5. Route & Transportation Cost Analysis

Transportation expenditure was compared across routes and transportation modes.

**Key findings:**

* Route B recorded the highest transportation expenditure.
* Route C showed comparatively lower operational costs.
* Air and road transportation contributed significantly to logistics expenses.

**Insight:** Route optimization and transportation-mode selection can help reduce logistics costs.

### 6. Supplier Lead Time Analysis

Supplier lead times were compared to evaluate supplier performance and planning reliability.

The analysis identified differences in lead times between suppliers, with Suppliers 3 and 4 showing comparatively shorter lead times.

**Insight:** Suppliers with reliable and shorter lead times can be prioritized for time-sensitive orders, while suppliers with higher lead times may require SLA review and performance improvement.

### 7. Revenue by Product Category

Revenue was analyzed across skincare, haircare, and cosmetics.

**Key findings:**

* Skincare generated the highest revenue contribution.
* Haircare and cosmetics also represented significant portions of total revenue.
* Skincare is therefore a strategically important product category.

**Insight:** High-revenue categories should receive greater attention in inventory planning, supplier management, and risk management.

### 8. Defect Rate by Supplier

Average defect rates were compared across suppliers.

Supplier 5 showed the highest defect rate, while Supplier 1 demonstrated comparatively better quality performance.

**Insight:** High-defect suppliers should be monitored through supplier quality programs, corrective action plans, and regular performance reviews.

### 9. Inspection Results Analysis

Inspection results were categorized into:

* Pass
* Fail
* Pending

Only 41% of inspections passed, while 36% failed and 23% remained pending.

**Insight:** The high proportion of failed and pending inspections indicates opportunities to improve quality control processes and reduce inspection bottlenecks.

### 10. Revenue by Location

Revenue was compared across major locations.

Mumbai generated the highest revenue, followed by Kolkata and Chennai, while Delhi recorded comparatively lower revenue.

**Insight:** Regional revenue analysis can support inventory positioning, distribution planning, and targeted marketing strategies.

### 11. Stock Levels vs Sales Volume

Inventory levels were compared with sales volume to identify potential overstocking and demand patterns.

The analysis showed differences in stock-to-sales behavior across product categories.

**Insight:** Data-driven inventory planning and demand forecasting can help reduce excess inventory while maintaining sufficient stock for high-demand products.

## Strategic Recommendations

Based on the dashboard analysis, the following recommendations were identified:

1. Improve supplier performance monitoring.
2. Reduce dependency on high-defect suppliers.
3. Increase the use of cost-effective transportation modes such as sea and rail where appropriate.
4. Optimize high-cost transportation routes.
5. Strengthen quality inspection procedures.
6. Improve customer demographic data collection.
7. Improve inventory planning using demand and sales patterns.
8. Standardize manufacturing operations.
9. Prioritize high-revenue product categories such as skincare.
10. Use Power BI dashboards for continuous supply chain performance monitoring.

## Business Intelligence Benefits

The dashboard provides:

* Improved operational visibility.
* Better reporting accuracy and transparency.
* Identification of operational bottlenecks.
* Faster data-driven decision-making.
* Improved logistics and supply chain efficiency.
* Better supplier and quality management.

## Dashboard Preview

*Add your main Power BI dashboard screenshot here.*

```text
![Supply Chain Dashboard](Dashboard/executive_dashboard.png)
```

## Project Deliverables

* Power BI Dashboard
* Cleaned Dataset
* Dashboard Screenshots
* Project Presentation
* Business Insights
* Strategic Recommendations

## Author

**Ayushman Dutta**

MCA Graduate | Data Analyst

**Skills demonstrated:** Power BI, DAX, Data Cleaning, Data Analysis, Data Visualization, Business Intelligence, Supply Chain Analytics
