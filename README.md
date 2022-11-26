# SQL-Assignment
SQL Assignment
Write a statement to create a table countries set a constraint NULL


CREATE TABLE countries (

  id INTEGER PRIMARY KEY,

  name TEXT,

  population INTEGER,

  area INTEGER,

  continent TEXT

);


Write a query to display the names (first_name, last_name) using alias name “First Name", "Last Name"
Data --> https://docs.google.com/spreadsheets/d/1DYR8te29A9D7aMZm2juFAVjN_qUh_OHaN-xRzAoB7UQ/edit?usp=sharing

SELECT first_name AS "First Name", last_name AS "Last Name" FROM employee;
