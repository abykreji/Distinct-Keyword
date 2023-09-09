## Exercise:

#### Question: 
##### What unique titles do we have?


```python
SELECT DISTINCT title FROM titles;
```



#### Question: 
#####How many unique birth dates are there?


```python
SELECT COUNT(DISTINCT birth_date)
from employees;
```


####Question:
##### Can I get a list of distinct life expectancy ages
##### Make sure there are no nulls


```python
SELECT DISTINCT lifeexpectancy FROM country
WHERE lifeexpectancy IS NOT NULL
ORDER BY lifeexpectancy;
```