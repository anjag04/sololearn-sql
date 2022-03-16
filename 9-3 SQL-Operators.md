# SQL Operators

You are given the following table of **students** with details:

|id|firstname|lastname|grade|
|-|-|-|-|
|1|John|Smith|100|
|2|David|Gibson|88|
|3|Lisa|Anderson|45|
|4|Seth|Gray|100|
|5|Nelson|Gross|95|

Write a query to output the first names and grades of students whose grades are greater than or equal to 88.

SELECT firstname, grade
FROM students
WHERE grade >=88;