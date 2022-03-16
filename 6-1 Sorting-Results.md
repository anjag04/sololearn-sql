# Fully Qualified Names

Fill in the blanks to select the ''address'' from ''customers'', using the fully qualified name for the ''address'' column.

SELECT `customers`.`address`

FROM customers;

# Order By

Build a query to select ''name'' and ''city'' from the ''people'' table, and order by the ''id''.

SELECT name, <ins>city</ins>

FROM <ins>people</ins> <ins>ORDER BY</ins> id;

`SELECT`    `LIMIT` `BY`

# Sorting Multiple Columns

Fill in the blanks to order the query results by ''name'', and then by ''state''.

SELECT name, state, address

FROM customers 

ORDER BY  `name` , `state`;