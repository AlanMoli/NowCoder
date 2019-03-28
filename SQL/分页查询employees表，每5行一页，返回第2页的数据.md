## 分页查询employees表，每5行一页，返回第2页的数据
```SQL
SELECT *
FROM employees
LIMIT 5 OFFSET 5
```