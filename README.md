# E-Commerce Power BI Analysis Project

## Project Overview

This project is the second part of my e-commerce data analysis portfolio.

The first project focused on creating this dataset and analyzing it using SQL and PostgreSQL. This project focuses on using Power BI and DAX to build an interactive dashboard and analyze the data through visualizations, business metrics, and a relational data model.

The project focuses on answering common business questions such as total business revenue, revenue by product category, product and supplier performance, profitability, customer behavior, monthly revenue trends, inventory levels, product ratings, and many more.

The dataset was created using Google Sheets with functions such as `RANDBETWEEN()` and `INDEX()` combined with randomization methods to generate realistic numbers and text values. A smaller dataset was intentionally used because increasing the size would not improve the learning exercise.

The final dataset covers the period from **January 1, 2023 to December 31, 2025** and contains:

- 300 Customers
- 50 Products
- 500 Orders
- 2,038 Units Sold

## Tools Used

- Power BI Desktop - data modeling, DAX calculations, data visualization, and dashboard development
- DAX - calculated measures and business metrics
- Google Sheets - dataset creation and random data generation
- CSV - data storage and import format

## Data Model

The Power BI model contains the following tables:

- Employees
- Customers
- Products
- Categories
- Suppliers
- Orders
- Order_Items

These tables are connected through primary and foreign key relationships to represent the structure of an e-commerce database.

A separate DAX Measures table was also created to keep the project's measures organized.

## Power BI Concepts Used

The project uses Power BI concepts such as:

- Data import
- Data modeling
- Table relationships
- DAX measures
- KPI cards
- Bar charts
- Column charts
- Pie and donut charts
- Treemaps
- Line charts
- Interactive filtering
- Data-driven color coding
- Dashboard formatting and layout

## DAX Measures

The project contains 18 DAX measures divided into the following areas:

### Basic Business Metrics

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value

### Sales and Profit Analysis

- Total Sales
- Total Cost
- Total Profit (Item Level)
- Profit Margin % (Item Level)
- Total Profit (Orders)
- Profit Margin % (Orders)

### Product Analysis

- Total Quantity Sold
- Average Unit Price
- Average Cost
- Total Products
- Category Color

### Customer Analysis

- Average Customer Age

### Supplier Analysis

- Total Suppliers

### Inventory Analysis

- Products Below Reorder

## Dashboard Pages

The Power BI report contains six pages:

### 1. Executive Overview

Provides a high-level overview of business performance through total revenue, total orders, total customers, average order value, monthly revenue trends, and revenue by product category.

### 2. Product Performance

Focuses on product and category performance through quantity sold, average unit price, product rankings, average cost, and category-level comparisons.

### 3. Profitability Analysis

Analyzes sales, costs, and profitability at both order and item levels, including total sales, total cost, total profit, profit margins, and profit by product category.

### 4. Customer Overview

Analyzes customer activity through revenue by city, revenue by customer type, customer type distribution, and average customer age.

### 5. Supplier Overview

Compares suppliers based on total sales and total profit to show differences in supplier performance.

### 6. Inventory Overview

Focuses on inventory and product information, including products below reorder level, total products, total quantity sold, stock quantities by category, and product ratings.

## Key Insights

The analysis produced several notable findings.

### Overall Business Performance

The dataset generated approximately **1.35 million** in total revenue from 500 orders, with an average order value of approximately **2.70K**.

Total cost was approximately **965K**, resulting in approximately **386K** in total item-level profit and an overall item-level profit margin of approximately **28.6%**.

### Sales Trends

Overall sales show a generally increasing trend throughout the three-year period.

**November 2025** recorded the highest monthly revenue in the dataset.

December showed a noticeable decline in sales across all three years. February also generally showed lower sales compared with surrounding months.

### Product Performance

Laptops generated the highest revenue at approximately **568K**, followed by:

- Smartphones - **355K**
- Tablets - **190K**
- Monitors - **172K**
- Smartwatches - **36K**
- Keyboards - **22K**
- Mice - **9K**

Laptops also generated the highest item-level profit at approximately **167K**, followed by Smartphones at **86K** and Tablets at **66K**.

Laptops had the highest quantity sold with **608 units**, followed by Smartphones with **386**, Tablets with **368**, and Monitors with **286**.

### Customer Analysis

Regular customers represented the largest customer group with **210 customers (70%)**, generating approximately **974K** in revenue.

New customers accounted for **66 customers (22%)** and generated approximately **130K** in revenue.

VIP customers represented **24 customers (8%)** and generated approximately **246K** in revenue.

The average customer age was approximately **31.8 years**.

Houston generated the highest revenue by city at approximately **96K**, followed by Philadelphia, Chicago, and Dallas at approximately **85K**, **84K**, and **83K** respectively.

New York generated the lowest city revenue at approximately **18K**, followed by Las Vegas at approximately **20K**.

### Supplier Analysis

Microsoft Hardware Partners generated the highest supplier sales at approximately **324K** and approximately **81K** in profit.

Logitech Authorized Distribution generated the lowest supplier sales at approximately **16K** and approximately **5K** in profit.

Xiaomi Global Distribution was the second-lowest supplier by sales, generating approximately **54K** in sales and approximately **15K** in profit.

### Inventory and Product Ratings

The dataset contains **50 products** and **2,038 units sold**.

No products were below their reorder level in the final dataset.

Keyboard inventory was the highest at **1,164 units**, while Smartwatch inventory was the lowest at **151 units**.

The average product rating was approximately **4.4** for Mice and **3.7** for Keyboards. Laptops and Smartwatches averaged approximately **4.3**, while the remaining product categories averaged approximately **4.2**.

## Project Structure

- `README.md`
- `data/`
  - `customers.csv`
  - `products.csv`
  - `categories.csv`
  - `suppliers.csv`
  - `employees.csv`
  - `orders.csv`
  - `order_items.csv`
- `PowerBI/`
  - `ecommerce_powerbi_analysis.pbix`
  - `ecommerce_dax_measures.dax`
- `screenshots/`
  - `executive_overview.png`
  - `product_performance.png`
  - `profitability_analysis.png`
  - `customer_overview.png`
  - `supplier_overview.png`
  - `inventory_overview.png`
  - `model_relationships.png`
  - `dataset_example.png`

## Future Improvements

Possible improvements for this project:

- Work with a larger or publicly available dataset
- Analyze an unfamiliar dataset without designing the data beforehand
- Add more advanced DAX calculations
- Expand the dashboard with additional analytical pages
- Improve dashboard interactivity and user experience

## Author

Davit Sandodze

Business Administration & Finance Student

Learning SQL and Data Analytics
