# Excel2SQL

This code uses the openpyxl package for playing around with excel using Python code
to convert complete excel workbook (all sheets) to an SQLite database
The code assumes that the first row of every sheet is the column name
Every sheet is stored in a separate table
The sheet name is assigned as the table name for every sheet
