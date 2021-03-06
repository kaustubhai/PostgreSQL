## Most used Data commands

Command     | Action |
------------|--------|
INSERT INTO `table_name` (`col_name`) VALUE (`value`); | Insert values for column provided into given table |
DELETE FROM `table_name` WHERE `query` = `value`; | Delete rows where value exist in the query column
SELECT * FROM `table_name`; | Show data onside given table |
\i `'PATH/TO/myfile.sql'` | Import data from a file (mockaroo.com) |
SELECT `query1`, `query2` from `table_name`; | Displays all the value in the column name as asked in the query
SELECT `query1`, `query2` from `table_name` ORDER BY `query`; | Displays all the value in the column sorted by query column
SELECT `query1`, `query2` from `table_name` ORDER BY `query` DESC; | Displays all the value in the column sorted by query column in descending order
SELECT DISTINCT `query` from `table_name`; | Gives out only distinct result
SELECT `query1, query2` from `table_name` WHERE `query1` = `'value1'`; | Gives out data where values of qeury1 matches value1
SELECT `query1, query2` from `table_name` WHERE `query1` = `'value1'` OR `query1` = `'value2'`; | Gives out data where values of qeury1 matches value1 or value2 and so on
SELECT * FROM `table_name` LIMIT `x`; | Show data with row limit to 'x'
SELECT * FROM `table_name` WHERE `query1` < `'value1'` LIMIT `x`; | Show conditioned data with row limit to 'x'
SELECT * FROM `table_name` OFFSET `x`; | Show result skipping 'x' number of rows
SELECT * from `table_name` WHERE `query1` IN (`'value1', 'value2', 'value3'`); | Show values where value1 or 2 or 3 exist in quer1 column
SELECT * FROM `table_name` WHERE `query1` BETWEEN `'value1'` AND `'value2'`; | Gives rows where value of column lays in between value1 and value2
SELECT * FROM `table_name` WHERE `query1` LIKE `'string_part'`; | Gives rows where value of column have string part in them 
SELECT * FROM `table_name` WHERE `query1` ILIKE `'string_part'`; | Gives rows where value of column have string part in them case insenstive 
SELECT * FROM `table_name` WHERE `query1` LIKE '%`string_part`'; | Gives rows where value of column ends with string_part
SELECT * FROM `table_name` WHERE `query1` LIKE '`string_part`%'; | Gives rows where value of column starts with string_part
SELECT `query1`, COUNT(*) FROM `table_name` GROUP BY `query1`; | Gives count of rows in query1 with same value
SELECT `query`, COUNT(*) FROM `table_name` GROUP BY `query` HAVING `query` = `'value'`; | Gives count of rows in query only where value exist in query
SELECT MIN/MAX/AVG/SUM(`query`) from `table_name`; | Shows minimum, maximum, average or sum value in query column
SELECT `query` AS `alias_name` from `table_name`; | Show alias as the coulomn name for the query
SELECT COALESCE(`query`, `'Error Message'`) from `table_name`; | Show values of the query couloumn and replace null values with the error message
UPDATE `table_name` SET `query` = `value` WHERE `query1` = `value1`; | Updates query's value to the value passwd in every row where the condition satisfies 
SELECT * FROM `table_name1` JOIN `table_name2` ON `table_name1.reference_key` = `table_name2.primary_key`; | Displays join of two correlated table 
SELECT * FROM `table_name1` LEFT JOIN `table_name2` ON `table_name1.reference_key` = `table_name2.primary_key`; | Displays complete table 1 and join of two correlated table
