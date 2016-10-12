# SQL-Query-Practice

This exercise used the Chinook SQLITE Database.  
[Here](https://github.com/nashville-software-school/node-milestones/blob/master/03-database-driven-application/exercises/0*-Relational-Databases-SQL.md) are the questions.

1. ``` SELECT * From Customer
WHERE Customer.Country <> "USA"```
1. ```SELECT * From Customer
WHERE Customer.Country = "Brazil" ```
1. ```SELECT Customer.FirstName ||" "|| Customer.LastName AS Name, Invoice.CustomerID, Invoice.InvoiceDate, Invoice.BillingCountry FROM Invoice
JOIN Customer ON Invoice.CustomerId = Customer.CustomerId
WHERE Invoice.BillingCountry = "Brazil"```
1. ```SELECT  FirstName ||" " || LastName AS Name, Title FROM Employee
WHERE Employee.Title = "Sales Support Agent"```
1. ```
