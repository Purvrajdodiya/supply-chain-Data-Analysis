# 🚚 A-Mart Delivery Performance Analysis

## Table of Contents
- [Project Overview](#-project-overview)
- [Data Sources](#-data-sources)
- [Tools Utilized](#️-tools-utilized)
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [Visualizations and Dashboards](#-visualizations-and-dashboards)
- [Primary Insights](#-primary-insights)
- [Strategic Recommendations](#-strategic-recommendations)

## 🔎 Project Overview
This project presents a formal analysis of the supply chain performance for A-Mart, a prominent Fast-Moving Consumer Goods (FMCG) corporation. The principal objective is to conduct a thorough evaluation of the company's delivery operations by systematically tracking key metrics, including On-Time Delivery (OT), In-Full Delivery (IF), and On-Time In-Full (OTIF). This analysis is designed to identify specific areas requiring operational improvement, to develop a comprehensive understanding of performance variations across different cities and customers, and to formulate actionable recommendations intended to enhance the overall reliability and efficiency of A-Mart's supply chain.

## 💾 Data Sources
The subsequent analysis is predicated on a relational dataset which is composed of the following integral files:

*   `dim_customers.csv`: Contains detailed customer information, which includes unique identifiers, names, and city locations.
*   `dim_products.csv`: Provides comprehensive product details, such as product names and their corresponding categories.
*   `dim_date.csv`: Consists of date dimensions that are essential for conducting time-series analysis.
*   `fact_orders_aggregate.csv`: Comprises aggregated order data that has been flagged for On-Time, In-Full, and OTIF statuses.
*   `transformed_fact_order_lines.csv`: Includes granular data for each individual line item contained within customer orders.

## 🛠️ Tools Utilized
*   **Tableau:** Employed for the creation of interactive dashboards and the visualization of complex Key Performance Indicator data.
*   **Python/SQL:** Utilized for the preliminary stages of data cleaning, transformation, and preparation prior to the analytical phase.

## 🎯 Key Performance Indicators (KPIs)
The central focus of this analysis involves the measurement of supply chain reliability from the perspective of the customer. The key metrics that have been systematically tracked are as follows:

*   **On-Time Delivery (OT %):** This metric represents the percentage of orders that were successfully delivered by the mutually agreed-upon date.
*   **In-Full Delivery (IF %):** This is the percentage of orders that were delivered containing the complete quantity of all items as originally requested by the customer.
*   **On-Time In-Full (OTIF %):** This critical metric calculates the percentage of orders that were delivered both on-time and in-full, serving as a comprehensive measure of overall service quality.
*   **Line Fill Rate (LIFR %):** Refers to the percentage of individual order lines that were shipped in their entirety, irrespective of the delivery timing.
*   **Volume Fill Rate (VOFR %):** This is the percentage of the total quantity of items shipped in comparison to the total quantity of items that were ordered.

## 📈 Visualizations and Dashboards
An interactive and dynamic dashboard was developed utilizing Tableau to provide a holistic and comprehensive overview of A-Mart's delivery performance. The dashboard is structured to include the following components:

*   **Top-Level KPIs:** Features high-level summary cards that display the overall OTIF, OT, and IF percentages in direct comparison to their established targets.
*   **Performance by City & Customer:** Offers detailed and granular breakdowns of all KPIs for each city and major customer, which allows for the straightforward identification of both high- and low-performing segments.
*   **Trend Analysis:** Incorporates line charts that illustrate how each KPI has performed over a specified period, thereby assisting in the identification of trends and the assessment of the impact of any operational modifications.

## 💡 Primary Insights
*(This section is intended to be populated with specific, data-driven findings subsequent to the completion of the analysis.)*

**Illustrative Example:**

*   Although the overall On-Time (OT) rate is notably high at 90%, the In-Full (IF) rate is considerably lower at 70%, which consequently reduces the critical OTIF metric to 65%.
*   The city of Surat consistently demonstrates underperformance in the OTIF metric, an issue that appears to be primarily driven by challenges associated with incomplete deliveries (low IF %).
*   The "Coolblue" customer account exhibits the highest OTIF rate, which may suggest the implementation of a highly efficient and optimized process for fulfilling their orders.

## ✅ Strategic Recommendations
*(This section will provide actionable and strategic advice that is directly informed by the insights derived from the analysis.)*

**Illustrative Example:**

*   It is recommended that a thorough investigation be conducted into the root causes of the low In-Full (IF) rates, with a particular focus on deliveries destined for Surat. This investigation should include a comprehensive review of current inventory management and supply planning processes.
*   An analysis of the successful delivery patterns associated with the "Coolblue" customer account should be undertaken to identify best practices that could potentially be standardized and applied to other customer accounts.
