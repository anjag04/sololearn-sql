# Selecting Multiple Columns

When buying food, it is important to make sure it is fresh and not expired.
You are given the following 'Products' list:

| productname | price | productiondate | expirationdate |
|-------------|-------|----------------|----------------|
|    Yogurt   |$200.00|   2020-11-19   |   2021-01-19   |
|    Juice    |$380.00|   2020-10-10   |   2022-10-10   |
|    Milk     |$520.00|   2020-08-19   |   2020-08-23   |

Write a query to select the ProductName, ProductionDate and ExpirationDate.

SELECT productname, productiondate, expirationdate FROM Products;