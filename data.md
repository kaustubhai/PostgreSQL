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
SELECT `query1, query2` from `table_name` WHERE `query1` = `'value1'` AND `query2` = `'value2'`  | Gives out data where values of qeury1 matches value1 and query2 with value2 and so on
