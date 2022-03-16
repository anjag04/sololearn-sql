#Subqueries

Drag and drop from the options below to select all items from the ''items'' table for which cost is greater than 463. Order the result by cost in descending order.

SELECT * FROM items 

<ins>WHERE</ins> cost > 463 

<ins>ORDER BY</ins> cost <ins>DESC</ins>

`AS`    `NOT`   `ASC`

# Subqueries

Drag and drop from the options below to select all items from the ''items'' table for which the cost is greater than the average of costs. Use a subquery to calculate the average cost.

SELECT * FROM items

<ins>WHERE</ins> cost > 

(SELECT <ins>AVG</ins> (cost) 

FROM <ins>items</ins>)