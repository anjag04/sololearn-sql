# Logical Operators

Drag and drop from the options below to select customers who live in Hollywood, CA.

SELECT * FROM customers 


WHERE state = 'CA'

<ins>AND</ins> city = 'Hollywood'

`,` `+` `OR`

# OR

Drag and drop from the options below to select customers who live either in CA or in Boston.

SELECT name, state, city 

FROM customers

<ins>WHERE</ins> state = 'CA' 

<ins>OR</ins> city = 'Boston';

`BETWEEN`   `AND`   `DISTINCT`

# Combining AND & OR

Drag and drop from the options below to select customers whose ids are either 1 or 2, and whose city is ''Boston''.

SELECT * FROM customers

WHERE (id = 1 <ins>OR</ins> id = 2)

<ins>AND</ins> city = 'Boston'

`BETWEEN`   `DISTINCT`  `WHERE`