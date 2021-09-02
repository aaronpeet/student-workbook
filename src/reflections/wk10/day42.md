# DAY 042

## In a SQL table, what is the difference between information in a row and information in a column?

A column holds the name and a row holds the value connected with that name. Columns are used to "get" and rows are used to "set" value.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters(
  id int NOT NULL primary key AUTO_INCREMENT comment 'primary key',
  name varchar(255) NOT NULL comment 'character name',
  age int comment 'character age',
  description varchar(255) NOT NULL comment 'character description'
) default charset utf8;

## What is the difference between the following statements:

DELETE FROM tableName- this will delete all the values in each row but the table will still exist with empty values in each row.

DROP TABLE tableName- this deletes the entire table and all values held within it.

https://github.com/aaronpeet/kingdom.git