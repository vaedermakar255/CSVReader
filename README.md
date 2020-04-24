# CSVReader
CSVReader (Comma-Separated Values Reader)  
Reads files in .txt and .csv formats, outputting output to the console and calculating the values ​​in the cells, if necessary.
A comma is used as the default delimiter.

The cells of the CSV file can store either integers or expressions of the form  
= ARG1 OP ARG2  
where ARG1 and ARG2 are the addresses of cells in the format ColumnName Line_Number, and OP is the arithmetic operation from the list: +, -, *, /

- running the program from the command line interpreter, you can specify a parameter in the form of a file name to open;
- if the correct operator is not found inside the expression, the program exit by indicating the coordinates of the cell with the error;
- column names cannot contain numbers, and row names cannot contain letters;
