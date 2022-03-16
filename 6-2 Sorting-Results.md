# Sorting Results

Six players have competed in a chess tournament and their scores have been tallied.
Here is the table of **Players**:

|firstname|lastname|losses|
|-|-|-|
|Hikaru|Nakamura|0|
|Magnus|Karlsen|2|
|Wesley|So|3|
|Levon|Aronian|3|
|Haik|Martirosian|1|
|Vladamir|Fedoseev|1|

**Sort** the players by losses to derive the leaderboard.

select * from Players order by losses;