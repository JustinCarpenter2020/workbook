# Day 49
__2/18/21__
## In a SQL table, what is the difference between information in a row and information in a column?
Information in the top row is the headers of the data, what the columns will be defined as. In general information in a single row all belongs together while columns are all the data of the same type for example an Id column. 

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE Characters (
  id INT NOT NULL AUTO_INCREMENT,
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255),
  description VARCHAR(255),
)


## What is the difference between the following statements:
### DELETE FROM table_name;
### DROP TABLE table_name;
Delete from table name will delete all the data within that collection. While Drop Table will delete that entire collection table.

daily project:
https://github.com/JustinCarpenter2020/burgerShack