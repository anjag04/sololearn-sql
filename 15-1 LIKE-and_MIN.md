# The Like Operator

Drag and drop from the options below to search ''boxes'' in the ''name'' column of the ''items'' table.

SELECT seller_id FROM items

WHERE name <ins>LIKE</ins> '%boxes'

`IN`    `COMPARE`   `SEARCH`

# The MIN Function

Drag and drop from the options below to complete the statement, which selects ''name'' and minimum of the "cost'' from ''items'', filtering by name and seller id.

SELECT name, <ins>MIN</ins> (cost) 

FROM items WHERE name 

<ins>LIKE</ins> '%boxes of frogs' AND 

seller_id <ins>IN</ins> (68, 6, 18)

`NOT`   `AVG`   `BETWEEN`