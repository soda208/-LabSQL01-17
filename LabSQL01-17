SELECT * FROM Employees
SELECT EmployeeID,FirstName,LastName FROM Employees

SELECT * FROM Employees WHERE city = 'london'

SELECT EmployeeID,FirstName,LastName,City FROM Employees WHERE City = 'london'

SELECT DISTINCT City,Country FROM Customers
SELECT City,Country FROM Customers

SELECT * FROM Products WHERE UnitPrice < 5

SELECT * FROM Products WHERE UnitPrice > 200

SELECT * FROM Customers WHERE City = 'london' OR City = 'Vancouver'

SELECT * FROM Customers WHERE Country = 'USA' OR City = 'Vancouver'

SELECT * FROM Products WHERE UnitPrice >= 50 AND UnitsInStock < 20

SELECT * FROM Products WHERE UnitPrice >= 50 AND UnitPrice <= 100

SELECT * FROM Products WHERE UnitPrice BETWEEN 0 AND 10

SELECT * FROM Customers WHERE Country = 'Brazil' or Country = 'Agentina' or Country = 'Mexico'

SELECT * FROM Customers WHERE Country IN ('Brazil','Agentina','Mexico' )

SELECT * FROM Customers WHERE Fax is null

SELECT * FROM Customers WHERE not Fax is null

SELECT * FROM Customers WHERE Fax is not null or Region is not null

SELECT * FROM Customers WHERE not (City = 'london' OR City = 'Vancouver')

SELECT * FROM Employees WHERE FirstName LIKE 'N%'

SELECT * FROM Customers WHERE Country LIKE '%land'

SELECT * FROM Customers WHERE CompanyName LIKE '%nese%' 

SELECT * FROM Customers WHERE CompanyName LIKE '%ny%' OR ContactName LIKE '%ss%'

SELECT * FROM Employees WHERE FirstName LIKE '_____'

SELECT * FROM Employees WHERE FirstName LIKE '_a%t'


SELECT * FROM Employees WHERE FirstName LIKE '[ars]%'


SELECT * FROM Employees WHERE FirstName LIKE '[a-m]%'

SELECT ProductID,ProductName,UnitPrice FROM Products ORDER BY UnitPrice DESC

SELECT ProductID,ProductName,UnitPrice FROM Products ORDER BY UnitPrice ASC

SELECT CompanyName,ContactName FROM Customers ORDER BY ContactName ASC 

SELECT CategoryID,ProductName,UnitPrice FROM Products ORDER By CategoryID ASC , UnitPrice DESC
