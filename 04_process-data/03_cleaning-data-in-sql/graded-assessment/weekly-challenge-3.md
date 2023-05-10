## Weekly challenge 3

Latest Submission Grade: 100%

&nbsp;

### Question 1

Data analysts choose SQL for which of the following reasons? Select all that apply. 

* SQL is a programming language that can also create web apps 
* SQL is a powerful software program
* **SQL is a well-known standard in the professional community**
* **SQL can handle huge amounts of data**

> Data analysts choose SQL because it can handle huge amounts of data. SQL is also a well-known standard in the professional community. 

&nbsp;

### Question 2

In which of the following situations would a data analyst use spreadsheets instead of SQL? Select all that apply. 

* **When visually inspecting data**
* When working with a dataset with more than 1,000,000 rows
* **When working with a small dataset**
* When using a language to interact with multiple database programs

> An analyst would choose to use spreadsheets instead of SQL when visually inspecting data or working with a small dataset. 

&nbsp;

### Question 3

A data analyst creates many new tables in their company’s database. When the project is complete, the analyst wants to remove the tables so they don’t clutter the database. What SQL commands can they use to delete the tables? 

* INSERT INTO 
* CREATE TABLE IF NOT EXISTS 
* UPDATE 
* **DROP TABLE IF EXISTS**

> The analyst can use the DROP TABLE IF EXISTS query to delete the tables so they don’t clutter the database. 

&nbsp;

### Question 4

A data analyst is cleaning customer data for an online retail company. They are working with the following section of a database:

![table](table.jpg)

The analyst wants to find out if the state data is consistent and if any text strings contain more than two characters. What is the correct SQL clause to use to find any text strings containing more than two characters?

* WHERE(state) > 2
* DISTINCT(state) > 2
* SUBSTR(state) > 2
* **LENGTH(state) > 2**

> The correct LENGTH statement is LENGTH(state) > 2. 

&nbsp;

### Question 5

Fill in the blank: The _____ function counts the number of characters a string contains.

* SUBSTR
* CAST
* **LENGTH**
* TRIM

> The LENGTH function counts the number of characters the string contains.

&nbsp;

### Question 6

In SQL databases, what data type refers to a number that contains a decimal? 

* Integer 
* String 
* Boolean
* **Float**

> In SQL databases, the float data type refers to a number that contains a decimal. 

&nbsp;

### Question 7

Fill in the blank: In SQL databases, the _____ function can be used to convert data from one datatype to another. 

* TRIM
* LENGTH
* SUBSTR
* **CAST**

> The CAST function can be used to convert data from one datatype to another. 

&nbsp;

### Question 8

Fill in the blank: The _____ function can be used to return non-null values in a list.

* CONCAT
* TRIM 
* **COALESCE**
* CAST

> The COALESCE function can be used to return non-null values in a list.




-------------+------------+-------------+--------------------------------------------------+--------------------------------------+---------------------+-------+----------------+-------------+--------------------+--------------------+-------------------------------+----------------+













Congratulations! You passed!
Grade received 100%
Latest Submission Grade 100%
To pass 80% or higher
1.
Question 1
Why do data analysts choose to work with SQL? Select all that apply. 

1 / 1 point

SQL is a programming language that can also create web apps. 


[x] SQL is a well-known standard in the professional community.

Correct

[x] SQL can handle huge amounts of data. 

Correct

SQL is a powerful software program.

2.
Question 2
In which of the following situations would a data analyst use spreadsheets instead of SQL? Select all that apply. 

1 / 1 point

When working with a dataset with more than 1,000,000 rows


[x] When visually inspecting data 

Correct

[x] When working with a small dataset

Correct

When using a language to interact with multiple database programs

3.
Question 3
A data analyst is managing a database of customer information for a retail store. What SQL command can the analyst use to add a new customer to the database? 

1 / 1 point

DROP TABLE IF EXISTS


UPDATE 


[x] INSERT INTO


CREATE TABLE IF NOT EXISTS

Correct
4.
Question 4
You are working with a database table that contains invoice data. The table includes columns for invoice_id and invoice_date. You want to remove duplicate entries for invoice_date. 

You write the SQL query below. Add a DISTINCT clause that will remove duplicate entries from the invoice_date column. 

NOTE: The three dots (...) indicate where to add the clause.

123
SELECT distinct invoice_date
FROM
invoice
Reset

(Output limit exceeded, 25 of 354 total rows shown)
What invoice_date is in row 17 of your query result?

NOTE: The query index starts at 1 not 0.

1 / 1 point

2009-03-05


2009-04-06


[x] 2009-03-14


2009-01-03

Correct
The clause DISTINCT invoice_date will remove duplicate entries from the billing_state column. The complete query is SELECT DISTINCT invoice_date FROM invoice. 

5.
Question 5
You are working with a database table that contains customer data. The table includes columns about customer location such as city, state, country, and postal_code. The state names are abbreviated. You want to check for city names that are greater than 5 characters long.

You write the SQL query below. Add a LENGTH function that will return any city names that are greater than 5 characters long.

123456
SELECT
*
FROM
customer
WHERE LENGTH(city) > 5


What is the the last name of the customer in row 1 of your query result?

NOTE: The query index starts at 1 not 0.

1 / 1 point

Tremblay


[x] Gonçalves


Almeida


Philips

Correct
The function LENGTH(city) > 5 will return any state names that are greater than 2 characters long. The complete query is SELECT * FROM customer WHERE LENGTH(city) > 5. The LENGTH function counts the number of characters a string contains. The country Ireland is in row 1 of your query result.

6.
Question 6
In SQL databases, True/False values refers to what data type?

1 / 1 point

Float


String 


[x] Boolean


Integer 

Correct
7.
Question 7
A data analyst notices their Boolean column is incorrectly storing True/False values as strings. What function can the analyst use to convert the data type from a string to Boolean? 

1 / 1 point

TRIM


[x] CAST


LENGTH


SUBSTR

Correct
8.
Question 8
What SQL function lets you add strings together to create new text strings that can be used as unique keys? 

1 / 1 point

COALESCE


[x] CONCAT


LENGTH


CAST

Correct
9.
Question 9
You are working with a database table that contains employee data. The table includes columns about employee location such as city, state, country, and postal_code. You use the SUBSTR function to retrieve the first 5 characters of each country, and use the AS command to store the result in a new column called new_country.

You write the SQL query below. Add a statement to your SQL query that will retrieve the first 5 characters of each country and store the result in a new column as new_country. 

NOTE: The three dots (...) indicate where to add the statement.

NOTE: SUBSTR takes in three arguments being column, starting_index, ending_index

1234567
SELECT
last_name,
country
FROM
employee
ORDER BY
employee_id
Reset
+-----------+---------+
| last_name | country |
+-----------+---------+
| Adams     | Canada  |
| Edwards   | Canada  |
| Peacock   | Canada  |
| Park      | Canada  |
| Johnson   | Canada  |
| Mitchell  | Canada  |
| King      | Canada  |
| Callahan  | Canada  |
+-----------+---------+
What employee last name is located in row 5?

NOTE: The query index starts at 1 not 0.

1 / 1 point

Callhan


Adams


[x] Johnson


Mitchell

Correct
The statement SUBSTR(country, 1, 5) AS new_country will retrieve the first 3 characters of each postal code and store the result in a new column as new_postal_code. The complete query is SELECT employee_id, SUBSTR(country, 1, 5) AS new_country FROM employee ORDER BY employee_id. The SUBSTR function extracts a substring from a string. This function instructs the database to return 5 characters of each postal code, starting with the first character.
