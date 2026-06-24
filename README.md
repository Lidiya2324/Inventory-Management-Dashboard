# Inventory Management Dashboard

## Table of Contents

- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Dataset Description](#dataset-description)
- [Data Preparation](#data-preparation)
- [Key KPIs](#key-kpis)
- [Visualizations](#visualizations)
- [Insights](#insights)
- [Recommendations](#recommendations)

## Project Overview

This project involves developing an interactive Inventory Management Dashboard using Power BI to monitor stock movement, product availability, shelf locations, and re-order requirements.

The dashboard focuses on:

- Monitoring total items received and dispatched
- Tracking available stock quantities
- Identifying products with low stock levels
- Comparing available quantity with re-order levels
- Monitoring stock availability trends over time
- Supporting inventory planning and replenishment decisions

## Tools Used

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX

## Dataset Description

The dataset contains inventory-related information, including Product ID, Product Name, Shelf Location, Quantity Received, Quantity Dispatched, Quantity Available, and Re-Order Level.

The data was used to analyze product movement, stock availability, low-stock items, and inventory replenishment needs.

## Data Preparation

Main data preparation steps performed in the project:

- Cleaned and standardized product names and shelf locations
- Checked for missing or duplicate records
- Created calculated columns and measures for inventory analysis
- Calculated Total Received Quantity
- Calculated Total Dispatched Quantity
- Calculated Quantity Available
- Created stock availability percentage measures
- Identified products with low quantities compared to re-order levels
- Created product and shelf filters for interactive analysis

## Key KPIs

- **Total Received:** 2,827 items
- **Total Dispatched:** 1,713 items
- **Quantity Available:** 4,540 units
- **Stock Availability:** 37.73%
- Products are distributed across multiple shelf locations.
- Several products have available quantities below their re-order levels.

## Visualizations
https://github.com/Lidiya2324/Inventory-Management-Dashboard/blob/dbcc0b6198ca028f9ed3d2ba3c5883b84a520ba9/Inventory%20Management%20Dashboard.jpg

### 6. Stock Availability Percentage

A donut chart showing the percentage of stock currently available.

### 7. Shelf Selector

Allows users to filter inventory information by shelf location.

### 8. Product Selector

Allows users to filter dashboard results by product name.

## Insights

- The dashboard shows that inventory movement is active, with items being received and dispatched regularly.
- Stock availability is 37.73%, indicating that a significant portion of inventory has already been dispatched or requires replenishment.
- Several products have quantities below their re-order levels, which may lead to stock shortages if not addressed.
- The Bottom 10 Stock Quantity table helps identify priority products that require immediate monitoring.
- Shelf and product filters make it easier to analyze stock availability by location and product category.
- The stock trend chart supports monitoring changes in inventory levels over time.

## Recommendations

- Replenish products that are below their re-order levels.
- Monitor the Bottom 10 Stock Quantity list regularly to avoid stock-outs.
- Set automatic alerts for products that reach or fall below the re-order level.
- Review monthly stock availability trends to improve purchasing and distribution planning.
- Use shelf-level analysis to improve product storage and warehouse organization.
- Maintain accurate records of received and dispatched products to support reliable inventory reporting.
