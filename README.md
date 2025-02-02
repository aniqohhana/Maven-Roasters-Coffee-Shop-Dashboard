# Maven Roasters Dashboard
Maven Roasters is a fictitious coffee shop operating in a NYC locations. The [dataset](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&page=6&pageSize=5) includes the transaction id, transaction date, transaction timestamp, transaction quantity, store id, store location, product id, unit price, product category, product type, and product detail. 

This dashboard shows the sales performance of Maven Roasters across 3 locations for the months of January to June 2023.

For this project, I create 3 new columns, namely 'day', 'week_number', and 'sale'. 
- The 'day' column is a column of day names (Sunday, Monday, etc.) extracted from the 'transaction_date' column.
- The 'week_number' column groups 'transaction_date' into weeks within the month. For example, dates 1-7 will be in week 1, dates 8-14 will be in week 2, and so on. 
- The 'sale' column is the result of multiplying 'unit_price' by 'transaction_qty'.
