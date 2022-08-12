# Hacker-Rank-SQL-Challenges
To improve my sql skills, I made challenges using the Hackerrank website and I am sharing them with you. The examples I made are about stops of a city and city tables.

# Query 1
Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.
The STATION table is described as follows
![image](https://user-images.githubusercontent.com/47644806/184414955-c1c2db2b-09fa-450b-b620-76b31e0aa1d4.png)

# Query 1
SELECT CITY, LENGTH(CITY) FROM STATION ORDER BY LENGTH(CITY), CITY LIMIT 1 ; 
SELECT CITY, LENGTH(CITY) FROM STATION ORDER BY LENGTH(CITY) DESC LIMIT 1 ;
