# SQL functions
## SQL FUNCTIONS
**SELECT** - Picks a specific column name
**FROM** - Selects file and table name
**WHERE** - Condition of files to display

**AS** - Displays results from a selected column in a new column (only in a results query).
example: SELECT 'helloNewUser' AS 'Hi', displays results from column 'helloNewUser' under 'Hi'.

**TRIM()** - Deletes all spaces.
example: TRIM() = 'What', transforms 'Whatever' and '  What  ' into 'What'.

**LENGTH()** - Calculates number of characters in a string.
example: WHERE LENGTH(column) > 2, displays only strings longer than 2 characters

**DISTINCT** - Displays only one unique value.
example: SELECT DISTINCT cars, displays string 'car' and 'car' only as a one 'car' in a query.

**MIN/MAX()** - Displays smallest and largest value in a column.
example: SELECT   MIN(length), FROM cars displays a number of letter of a car with the shortest name.

**UPDATE** - Is used to modify the existing records in a table.

**ORDER BY**example:. ORDER BY price DESC, displays price of the item from the highest to the lowest

**SUBSTR()** - function extracts a substring from a string (starting at any position)
SUBSTR(string or column, start, length).
example: SUBSTR(cars, 3, 6) displays a string named 'Lamborghini' as 'mborgh' 

**CAST()** - converts a value (of any type) into the specified datatype. CAST(value AS datatype)
example: CAST(date AS date), converts '2020-12-02' STRING into a  '2020-12-02' DATE format

**UPPER()** - converts a string to upper-case.

**CONCAT()** -  Adds two or more expressions together. CONCAT(expression1, expression2, expression3,...)
example: SELECT CONCAT(name, surname), displays 'John Bohnam'.

**COALESCE()** - Returns the first non-null value in a list. COALESCE(val1, val2, ..., val_n)



[[SQL]][[📊data analysis]]