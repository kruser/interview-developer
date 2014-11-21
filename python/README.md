#Python/SQL Coding Exercise
============================

For this exercise you will be writing Python code to parse HTML and insert it into a PostgreSQL database that you will create.

Upon completion you will deliver the following
* Python code that does the following:
 * downloads the [Leaderboard HTML](https://raw.githubusercontent.com/kruser/interview-developer/master/python/leaderboard.html) found in this repository
 * parses all stats for players and inserts it into a database table or tables

* SQL statements to:
 * Create the table or tables that your Python code needs
 * A query that ranks these same players according to their 2014 [wOBA](http://www.fangraphs.com/library/offense/woba/)

### Notes

* Your Python code can assume the tables it uses have already been created. That is, it doesn't need to 
automatically create the tables.
* Feel free to use any modules available via a ```pip install```. Include a ```requirements.txt``` file that
lists the dependencies.