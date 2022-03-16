Fill in the blanks to select all values from the ''students'' table in which the field ''university'' equals ''MIT''.

SELECT * FROM <ins>students</ins>

WHERE <ins>university</ins> = 'MIT';

Rearrange the code to select students from MIT and Stanford, and order the results by the ''university'' column.

`SELECT name, university`

`FROM students WHERE university`

`IN ('Stanford', 'MIT')`

`ORDER BY university;`

Which keyword is the correct one for custom columns?

- [ ] SIMILAR
- [ ] LIKE
- [x] AS

What is the name of the aggregate function for calculating the sum?

- [ ] AVG
- [x] SUM
- [ ] AGGR
- [ ] SQRT

Drag and drop from the options below to select name and age from ''students'', where age is greater than the average of all ages. Use a subquery to calculate the average value of age.

<ins>SELECT</ins> name, age 

FROM students

<ins>WHERE</ins> age >

(SELECT <ins>AVG</ins> (age)

FROM students)

`ORDER BY`  `VALUE`

# Apartments

You want to rent an apartment and have the following table named **Apartments**:

|id|city|address|price|status|
|-|-|-|-|-|-|
|1|Las Vegas|732 Hall Street| 1000|Not rented|
|2|Marlboro|985 Huntz Lane| 800 | Not rented|
|3|Moretown| 3757 Wines Lane|700|Not rented|
|4|Owalonna|314 Pritchard Court|500|Rented|
|5|Grayslake|3234 Cunningham Court|600|Rented|
|6|Great Neck|1927 Romines Mill Road|900|Not rented|

Write a query to output the apartments whose prices are greater than the average and are also not rented, sorted by the 'Price' column.

SELECT *
FROM Apartments
WHERE price > 
(SELECT AVG (price)
FROM Apartments)
AND "status" = 'Not rented'
ORDER BY Price ASC;