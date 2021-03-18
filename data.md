## Most used Data commands

Command     | Action |
------------|--------|
INSERT INTO `table_name` (`col_name`) VALUE (`value`) | Insert values for coloumns provided into given table |
SELECT * FROM `table_name` | Show data onside given table |
\i `'PATH/TO/myfile.sql'` | Import data from a file (mockaroo.com) |
SELECT `query1`, `query2` from `table_name` | Displays all the value in the coloumn name as asked in the query
SELECT `query1`, `query2` from `table_name` ORDER BY `query` | Displays all the value in the coloumn sorted by query coloumn
SELECT `query1`, `query2` from `table_name` ORDER BY `query` DESC | Displays all the value in the coloumn sorted by query coloumn in descending order
SELECT DISTINCT `query` from `table_name` | Gives out only distinct result
SELECT `query1, query2` from `table_name` WHERE `query1` = `'value1'` | Gives out data where values of qeury1 matches value1
SELECT `query1, query2` from `table_name` WHERE `query1` = `'value1'` OR `query1` = `'value2'` | Gives out data where values of qeury1 matches value1 or value2 and so on
SELECT * FROM `table_name` LIMIT `x` | Show data with row limit to 'x'
SELECT * FROM `table_name` WHERE `query1` < `'value1'` LIMIT `x` | Show conditioned data with row limit to 'x'
SELECT * FROM `table_name` OFFSET `x` | Show result skipping 'x' number of rows
SELECT * from `table_name` WHERE `query1` IN (`'value1', 'value2', 'value3'`) | Show values where value1 or 2 or 3 exist in quer1 coloumn
SELECT * FROM `table_name` WHERE `query1` BETWEEN `'value1'` AND `'value2'` | Gives rows where value of coloumn lays in between value1 and value2
SELECT * FROM `table_name` WHERE `query1` LIKE `'string_part'` | Gives rows where value of coloumn have string part in them 
SELECT * FROM `table_name` WHERE `query1` ILIKE `'string_part'` | Gives rows where value of coloumn have string part in them case insenstive 
SELECT * FROM `table_name` WHERE `query1` LIKE '%`string_part`' | Gives rows where value of coloumn ends with string_part
SELECT * FROM `table_name` WHERE `query1` LIKE '`string_part`%' | Gives rows where value of coloumn starts with string_part
SELECT `query1`, COUNT(*) FROM `table_name` GROUP BY `query1` | Gives count of rows in query1 with same value