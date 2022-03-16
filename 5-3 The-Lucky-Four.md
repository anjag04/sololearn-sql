# The LIMIT Keyword

8 people are registered for an online course, but only the first 4 of them are able to participate.
Here is the Participants table:

|firstname|lastname|
|-|-|
|Jack|Alonso|
|Bob|Welch|
|Nicolas|So|
|Jon|Reacher|
|Chool|Sun|
|Eva|Mendes|
|Joe|Biden|
|Brendan|Whittaker|

Select the first four participants from the given list.

SELECT firstname, lastname FROM Participants LIMIT 4;