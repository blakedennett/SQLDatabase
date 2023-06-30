|Key Word|Function|
|---|---|
|SELECT|Selects data from DB|
|*|Indicates all columns are selected|
|DISTINCT|Will exclude duplicates|
|WHERE|Takes condition, ends with semicolon|
|DROP TABLE|Deletes table from DB|
|ORDER BY|Takes column name with semicolon|
|INSERT INTO|takes table name, then columns in tuple*|
|(continued)|then takes in VALUES with tuple|
|IS (NOT) NULL|can be placed in where statement|
|UDATE (tablename) SET (column = value)|updates a table|
|MIN(column name)|also has max*|
|HAVING|takes condition*|
|SELECT column INTO tablename FROM tablename|copies data from one table to another|
|ALTER TABLE|for creating/dropping columns|
|SET column =|filling in new column with values (follows UPDATE)|
||   |
|   |   |



|Function|Notes|
|---|---|
|INSERT INTO|if all columns are being filled, then listing the columns isn't neccesary|
|MIN|also there is AVG, COUNT, and SUM that work the same|
|HAVING|works the same as WHERE but it can use agg functions like count and sum|
