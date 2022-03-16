# The WHERE Statement

You are given the following table of **cars** with details:

|id|company|model|year|
|-|-|-|-|
|1|Tesla|Model 3| 2020|
|2| BMW | i8 | 2019|
|3| Mercedes-Benz|S class|2020|
|4|Lamborghini|Huracan|2020|
|5|Audi|A6|2018|

Write a query to output the brand and model years of the cars produced in 2020, sorted by the 'company' column.

SELECT company, year 
FROM cars
WHERE year = '2020'
ORDER BY company;