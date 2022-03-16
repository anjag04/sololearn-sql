# The IN Operator

Drag and drop from the options below to select users from NY and CA:

SELECT * <ins>FROM</ins> users

<ins>WHERE</ins> state = 'NY'

<ins>OR</ins> state = 'CA'

# The IN Operator

Select customers from NY, CA, or NC, using the IN statement.

SELECT name, state 

<ins>FROM</ins> customers 

WHERE state IN <ins>('CA', 'NY', 'NC')</ins>;

`SELECT`    `AND`   `OR`

# The NOT IN Operator

Drag and drop from the options below to exclude customers from the states CA, NY.

SELECT name, state 

FROM customers

WHERE state <ins></ins> ('CA', 'NY');

`BETWEEN`   `IN`    `EXCLUDE`