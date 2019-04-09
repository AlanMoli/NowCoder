## 获取employees中的行数据，且这些行也存在于emp_v中
```SQL
SELECT *
FROM emp_v
WHERE emp_no IN (SELECT emp_no
                 FROM employees)
```