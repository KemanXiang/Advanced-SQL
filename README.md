# Advanced-SQL
Views, Stored Procedures, ACID Transactions, and JOIN Statements

## ACID Transactions
See file ACID_Transactions_BankAccounts-ShoeShop_Database_Script.sql \
A transaction is simply a sequence of operations performed using one or more SQL statements as a single logical unit of work. A database transaction must be ACID (Atomic, Consistent, Isolated and Durable). The effects of all the SQL statements in a transaction can either be applied to the database using the COMMIT command or undone from the database using the ROLLBACK command. 

In this project, we will utilize some commonly used TCL (Transaction Control Language) commands of SQL through the creation of a stored procedure routine. We will use COMMIT statement, which is used to permanently save the changes done in the transactions in a table, and ROLLBACK statement, which is used to undo the transactions that have not been saved in a table. ROLLBACK can only be used to undo the changes in the current unit of work.
