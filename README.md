# SAIF Ecommerce Sales Dashboard

An interactive Power BI dashboard that analyses e-commerce sales data, covering revenue, profit, product categories, payment modes and state-wise performance.

## Dashboard Preview



![Dashboard](dashboard.png)



## Key Metrics

- Total Amount (Sales)
- Total Quantity Sold
- Average Order Value
- Profit by Month
- Profit by Sub-Category
- Quantity by Category and Payment Mode
- Sales by State and Customer

## Data

The dashboard uses two related tables:

- **Orders**: Order ID, Order Date, CustomerName, State, City
- **Details**: Order ID, Amount, Category, Sub-Category, PaymentMode, Profit, Quantity

Both tables are joined on **Order ID**.

## How to Use

1. Download `Saif salesbord.pbix`.
2. Open it in Power BI Desktop.
3. Use the State slicer at the top right to filter the dashboard by state.
4. Hover over charts to see detailed values.

## Tools Used

- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures and calculations)

## Author

Saif Ali
