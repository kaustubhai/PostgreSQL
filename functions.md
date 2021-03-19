## Most used Pre-Built Functions

Function     | Action |
------------|--------|
`value`::`data_type` | Typecasting of value as given data type
COUNT(`*`) | Count numbers of unique value
MIN(`query`) | Shows minimum value in the query coloumn
MAX(`query`) | Shows maximum value in the query coloumn
AVG(`query`) | Shows average value in the query coloumn
SUM(`query`) | Shows sum of all the value in the query coloumn
COALESCE(`query`, `msg`) | Replace null value in query by msg
NULLIF(`value1`, `value2`) | Return NULL if value1 == value2 else value1
NOW() | Display current date and time
NOW::DATE() | Display date of today
NOW::TIME() | Display current time
AGE(NOW() - `date_of_birth`::DATE) | Returns time went from date_of_birth to now
