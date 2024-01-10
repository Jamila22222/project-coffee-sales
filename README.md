# project-coffee-sales
this is a visualization in excel of coffee sales

This MS Excel project is about coffee sales in three countries:

United Kingdom
Ireland
United States
Original dataset consist of three worksheets, orders_data, customers_data, and products_data.

orders_data has a total of 1,000 rows of entries

customers_data has a total of 1,000 rows of entries

products_data has a total of 48 rows of entries.

In the orders_data, the XLOOKUP function was used to retrieve data for columns "Customer Name", "Email", and "Country" referencing from customers_data.

Using INDEX MATCH to get data for "Coffee Type", "Roast Type", "Size", and "Unit Price", matching from products_data.

The IF function is used to retreive data for "Coffee Type Name" and "Roast Type Name".

Checked for duplicate values in the OrderID column and remove any duplicate values.

There are 3 PivotTables created in the worksheet,

Total Coffee Sales (Years, Order Date, Coffee Type and Grand Total)
Sales in Country (Sum of Sales in the three countries)
Top 5 Customers and their sales
Created three different charts/graphs for the dashboard.

A dashboard that allow users to retrieve the information they want:

Roast Name (Dark, Light, and Medium)
Loyalty Card (Yes or No)
Size (0.2kg, 0.5kg, 1kg, 2.5kg)
Year (2019-2022)
