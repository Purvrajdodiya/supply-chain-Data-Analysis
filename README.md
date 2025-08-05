A-Mart Delivery Performance Analysis
This project provides a comprehensive analysis of A-Mart's delivery performance, visualized through an interactive Tableau dashboard. The dashboard tracks key delivery metrics against set targets, allowing for a detailed view of operational efficiency.

Data Sources
The analysis is built upon a set of CSV files that form a star schema, separating transactional data from descriptive attributes.

Fact Tables: These tables contain the core transactional data of the orders.

fact_order_lines.csv: Detailed data for each line item within an order.

fact_orders_aggregate.csv: Aggregated data for each order.

Dimension Tables: These tables provide descriptive information for the data in the fact tables.

dim_customers.csv: Information about each customer.

dim_date.csv: Date dimensions for time-based analysis.

dim_products.csv: Details about the products.

dim_targets_orders.csv: Delivery targets for each customer.

Tableau Dashboard
The primary output of this project is the Tableau workbook:

A- Mart Delivary Data.twbx: This packaged workbook contains the complete analysis, including all data sources, worksheets, and the final interactive dashboard.

Key Analyses
The dashboard allows users to explore various aspects of delivery performance, including:

On-Time, In-Full (OTIF) Performance: Track the primary metric of delivery success.

Performance vs. Targets: Compare actual delivery metrics against the targets set for each customer.

Customer-Level Analysis: Drill down into the delivery performance for individual customers.

Product Category Insights: Analyze performance based on different product categories to identify any specific challenges.

Time Series Analysis: Observe trends in delivery performance over time to identify patterns and seasonal impacts.

How to Use
To explore the analysis, open the A- Mart Delivary Data.twbx file using Tableau Desktop or Tableau Reader. The dashboard is interactive, allowing you to filter data and drill down into specific areas of interest.
