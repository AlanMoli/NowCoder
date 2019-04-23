## 获取Employees中的first_name，查询按照first_name最后两个字母升序进行排列
```SQL
SELECT first_name
FROM Employees
ORDER BY SUBSTR(first_name, LENGTH(first_name) - 1, 2)
```