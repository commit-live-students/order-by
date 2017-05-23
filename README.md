![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# ORDER BY Clause

The SQL ORDER BY clause is used to sort the data in ascending or descending order, based on one or more columns. Some databases sort the query results in an ascending order by default.

### Syntax

The basic syntax of the ORDER BY clause is as follows −

        SELECT column-list
        FROM table_name
        [WHERE condition]
        [ORDER BY column1, column2, .. columnN] [ASC | DESC];

You can use more than one column in the ORDER BY clause. Make sure whatever column you are using to sort that column should be in the column-list.

### Example

The following code block has an example, which would sort the result in an ascending order by the CustomerName.

        SELECT * FROM greyatom.Customers ORDER BY CustomerName ASC;

The following code block has an example, which would sort the result in the descending order by CustomerName.

        SELECT * FROM greyatom.Customers ORDER BY CustomerName DESC;
