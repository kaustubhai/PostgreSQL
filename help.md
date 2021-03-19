## Most used help commands

Command     | Action |
------------|--------|
\l          | List all the databases |
\q          | Exit psql command line |
\c `database` `user` `host` `PORT`         | Coonect database to perform query |
\d          | list all the tables in the database |
\d `table_name` | describe the table in the database |
\i `'PATH/TO/myfile.sql'` | Import data from a file (mockaroo.com) |
\x | Toggle expanded display |
\copy (`query`) TO `location` DELIMETER ',' CSV HEADER| Toggle expanded display |
SELECT * FROM pg_available_extensions; | Show list of available extensions to add
CREATE EXTENSION IF NOT EXISTS "`extension_name`"; | Add given extension
\df | Shows a list of functions