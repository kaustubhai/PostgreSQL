## Most used database commands

Command     | Action |
------------|--------|
CREATE DATABASE "`dbName`"; | Create a database with provided name |
DROP DATABASE `dbName`; | Delete the database with provided name |
CREATE TABLE `table_name` (`coloum_name data_type constraints`);  | Create table within selected database with defined coloumns and properties |
CREATE TABLE `table_name` (`coloum_name data_type constraints`, `coloumn_name data_type` references `table2_name(table2_name.primary_key)`);  | Create table within selected database with defined coloumns and properties and a foreign key |
DROP TABLE `table_name`; | Drop table |
CREATE USER `username` WITH PASSWORD `'password'`; | Creates a user in the database
ALTER TABLE `table_name` ADD PRIMARY KEY (`query`); | Adds Primary key constraint(not coloumn) on query coloumn
ALTER TABLE `table_name` DROP CONSTRAINT `table_name`_pkey; | Delete Primary key constraint(not coloumn) from table
ALTER TABLE `table_name` ADD CHECK (`query` == `value1` OR/AND `query` = `value2`); | Adds check constraint to satisfy the condition before inserting value in table
