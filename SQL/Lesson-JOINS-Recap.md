### Recap
You learned a key element for JOINing tables in a database has to do with primary and foreign keys. Choosing the set up of data in our database is very important, but not usually the job of a data analyst. This process is known as Database Normalization.

You learned how to combine data from multiple tables using JOINs. The three JOIN statements you are most likely to use are: JOIN, LEFT JOIN, RIGHT JOIN.

There are a few more advanced JOINs that we did not cover here, and they are used in very specific use cases. UNION and UNION ALL, CROSS JOIN, and the tricky SELF JOIN. These are more advanced than this course will cover, but it is useful to be aware that they exist, as they are useful in special cases.

You also learned that you can alias tables and columns using AS or not using it. This allows you to be more efficient in the number of characters you need to write, while at the same time you can assure that your column headings are informative of the data in your table.



### Key Definitions
- Foreign Key (FK)	is a column in one table that is a primary key in a different table
- JOIN	is an INNER JOIN that only pulls data that exists in both tables.
- LEFT JOIN	is a JOIN that pulls all the data that exists in both tables, as well as all of the rows from the table in the FROM even if they do not exist in the JOIN statement.
- Partition by	A subclause of the OVER clause. Similar to GROUP BY.
- Primary Key (PK)	is a unique column in a particular table
- RIGHT JOIN	is a JOIN pulls all the data that exists in both tables, as well as all of the rows from the table in the JOIN even if they do not exist in the FROM statement.
