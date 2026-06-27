# Revising the Select Query I

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Query all columns for all American cities in the **CITY** table with populations larger than `100000`. The **CountryCode** for America is `USA`. 

The **CITY** table is described as follows:  

![CITY.jpg](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

**Input Format**

 

**Constraints**

 

**Output Format**

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-06-27T12:42:02.820Z  

```cpp
SELECT * FROM CITY WHERE POPULATION >100000 AND COUNTRYCODE ='USA';

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/revising-the-select-query/problem)