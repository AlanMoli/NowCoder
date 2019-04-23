## 查找字符串'10,A,B' 中逗号','出现的次数cnt
```SQL
SELECT (LENGTH('10,A,B') - LENGTH(REPLACE('10,A,B', ',', ''))) AS cnt
```