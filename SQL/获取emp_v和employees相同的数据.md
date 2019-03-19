## 获取emp_v和employees相同的数据
```SQL
SELECT employees.* 
FROM emp_v, employees
WHERE emp_v.emp_no = employees.emp_no
```