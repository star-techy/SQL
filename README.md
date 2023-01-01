# SQL
SQL Portfolio
List all the products sold in Los Angeles in February, and include how many of each were sold
SELECT Product, SUM(quantity) 
FROM FebSales
WHERE location like '%Los Angeles%'
Group By Product
