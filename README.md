# Hacker-Rank-SQL-Challenges
To improve my sql skills, I made challenges using the Hackerrank website and I am sharing them with you. The examples I made are about stops of a city and city tables. I solved with MySQL.

## Query 1
Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.
The STATION table is described as follows:

![image](https://user-images.githubusercontent.com/47644806/184417133-0b59e549-c41c-4d64-b8b5-2296eefe7fc2.png)

## Query 1
SELECT(COUNT(CITY) - COUNT(DISTINCT CITY)) FROM STATION 


## Query 2
Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.
The STATION table is described as follows

![image](https://user-images.githubusercontent.com/47644806/184414955-c1c2db2b-09fa-450b-b620-76b31e0aa1d4.png)

## Query 2
SELECT CITY, LENGTH(CITY) FROM STATION ORDER BY LENGTH(CITY), CITY LIMIT 1 ; 
SELECT CITY, LENGTH(CITY) FROM STATION ORDER BY LENGTH(CITY) DESC LIMIT 1 ;


