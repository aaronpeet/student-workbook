# DAY 045

## What is the difference between a primary key and a foreign key

PRIMARY KEY is usually the Id on a table. Something unique that can be used to identify an object. The foreign key is also a unique identifier but its within a table used to create a relationship from another table.

## What is an Alias?

Alias' are used to create a temporary database where two tables can be combined and theyre inner elements won't get confused with the others. 

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

"SELECT
d.*,
p.*
FROM patients p
JOIN doctors d ON d.id = p.doctorId;
"

https://github.com/aaronpeet/Manager.git