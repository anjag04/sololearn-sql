# The DISTINCT Keyword

At the conclusion of a bank transaction, 6 checks are printed -- 3 originals for the bank, and 3 copies for the customer.
Here is the list of all the checks named **Operation**

|id|checks|
|--|------|
|1|Check1|
|2|Check2|
|3|Check3|
|4|Check1|
|5|Check2|
|6|Check3|

Write a query to show only the **unique checks** that are given to the customer.

SELECT DISTINCT checks FROM Operation;