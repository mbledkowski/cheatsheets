# SQL

## data types

**INT** - integers
**DECIMAL**(X,Y) - decimal numbers
(X - number of digits; Y - number of digits after decimal point)
**VARCHAR**(L) - string of text
(L - number of characters, length)
**BLOB** - Binary Large OBject, stores large objects like images, files etc.
**DATE** - 'YYYY-MM-DD'
**TIMESTAMP** - 'YYYY-MM-DD HH:MM:SS'

## instructions

CREATE DATABASE/TABLE - creates database/table

DESCRIBE - prints table

DROP DATABASE/TABLE - deletes database/table

## creating table

CREATE TABLE name_of_table (

​	user_id INT PRIMARY KEY,

​	name VARCHAR(20)

)

is the same as

CREATE TABLE name_of_table (

​	user_id INT,

​	name VARCHAR(20),

​	PRIMARY KEY(student_id)

)

## syntax

**<>** - not equal to

##### Source: https://youtu.be/HXV3zeQKqGY

