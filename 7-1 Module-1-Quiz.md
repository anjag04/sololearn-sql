# Module 1 Quiz

A database consists of:

- [x] Tables
- [ ] Rows
- [ ] Columns

Drag and drop from the options below to list the table names.

<ins>SHOW</ins> TABLES;

`SELECT`    `VIEW`  `LIMIT` `SHOW`

Why use primary keys?

- [ ] Just for fun
- [ ] It's an SQL standard
- [x] TO guarantee the uniqueness of a row

Drag and drop from the options below to select distinct names from the ''students'' table, ordered by name.

SELECT <ins>DISTINCT</ins>

<ins>FROM</ins> students

<ins>ORDER BY</ins> name;

`BY`    `LIMIT`  `IN`

Cakes

A local bakery creates unique cake sets. Each cake set contains three different cakes.
Here is the cakes table:

|name|calories|
|-|-|
|Apple Cake|100|
|Banana Cake|200|
|Pound Cake|180|
|Sponge Cake|100|
|Genoise Cake|360|
|Chiffon Cake|250|
|Opera Cake|90|
|Cheese Cake|370|

Тoday a customer want a cake set that has minimal calories.
Write a query to sort the cakes by calorie count and select the first 3 cakes from the list to offer the customer.

select * from cakes order by calories limit 3;