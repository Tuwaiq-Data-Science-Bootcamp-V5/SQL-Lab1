# SQL-Lab1
- Create a table "BooksAuthors" containing two fields (AuthorId, BookId)

```sql 
CREATE TABLE BooksAuthors(
  AuthorId INT NOT NULL,
  BookId INT NOT NULL);
   ```
![](<Screenshot 2023-10-27 014713.png>)

- Insert at least 5 records into the BooksAuthors table.

```sql 
INSERT INTO BooksAuthors (bookid, authorid) 
	VALUES (1 ,3), (4,7), (3,6), (2,1), (5,5);
   ```
![Alt text](<Screenshot 2023-10-27 020450.png>)

- Write a statement that will select the Country column from the Authors table.

![Alt text](<Screenshot 2023-10-27 021332.png>)

- Select all the different values from the Country column in the Authors table.

![Alt text](<Screenshot 2023-10-27 021451.png>)

- Write an SQL query to return only Authors whose name begins with S.

![Alt text](<Screenshot 2023-10-27 021712.png>)

- List the number of Authors in each country.

![Alt text](<Screenshot 2023-10-27 021820.png>)

- Select all records from the Authors table, and sort the result alphabetically by the column's name.

![Alt text](<Screenshot 2023-10-27 021919.png>)

- Select all records from the Authors table, and sort the result reversed alphabetically by the column name.

![Alt text](<Screenshot 2023-10-27 022008.png>)

- Select all records where the Title column has the value ‘Great ' from the Books table.

![Alt text](<Screenshot 2023-10-27 022057.png>)

- Use the NOT keyword to select all records where the country is NOT "USA".

![Alt text](<Screenshot 2023-10-27 022144.png>)

- Select all records where the country column has the value 'USA' or ‘India' from the “Authors” table

![Alt text](<Screenshot 2023-10-27 022223.png>)

- Select all records where the age column has the value BETWEEN 50 - 60 in the “Authors” table.

![Alt text](<Screenshot 2023-10-27 022315.png>)

- Use the MIN function to select the record with the smallest value of the Age column from the “Authors” table.

![Alt text](<Screenshot 2023-10-27 022335.png>)

- Choose the correct `JOIN` clause to view all books and their authors.

![Alt text](<Screenshot 2023-10-27 022359.png>)
