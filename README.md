# Power BI Sales & ABC Analysis Dashboard
This project is a Power BI homework case focused on sales analysis, warehouse performance and ABC product classification.

## Dataset
The report was built using a CSV dataset containing **301,355 transaction rows** and **5 fields**:
* Date
* Warehouse
* Customer
* Product
* Quantity

The analyzed period covers sales from **04 January 2018 to 31 August 2018**, including **205 unique sales days**, **5 warehouses**, **211 customers** and **24 products**.

## Key Metrics
The dashboard includes the following KPI indicators:
* Total Sales Quantity: **889,467 units**
* Number of Products: **24**
* Number of Customers: **211**
* Unique Sales Days: **205**

## Report Pages
### 1. Warehouse Sales Report
This page provides an overview of sales performance by warehouse. It includes slicers by date, product, customer and warehouse, KPI cards, a warehouse ranking table and a bar chart comparing sales quantity and transaction volume.
The top-performing warehouse is **Warehouse 2**, with **205,567 units sold** and **74,389 transactions**.

### 2. ABC Analysis
This page classifies products into A, B and C groups based on their contribution to total sales.
ABC results:
* Group A: **618,926 units**, **69.58%** of total sales
* Group B: **223,912 units**, **25.17%** of total sales
* Group C: **46,629 units**, **5.24%** of total sales

## Power BI Features Used
* Data import from CSV
* Data modeling
* DAX measures
* KPI cards
* Slicers
* Tables and matrix visuals
* Bar charts
* Donut chart
* Bookmarks
* Navigation buttons
* ABC classification logic
* Interactive filtering

## Business Value
The dashboard helps identify key warehouses, high-performing products and low-contribution product groups. It supports better inventory control, warehouse performance analysis and prioritization of products with the highest sales impact.
