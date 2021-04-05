SQL -  Structured Query Language

SQL is Structured Query Language, which is a computer language for storing, manipulating and retrieving data stored in a relational database.
SQL is the standard language for Relational Database System. All the Relational Database Management Systems (RDMS) like MySQL, MS Access, Oracle, Sybase, Informix, Postgres and SQL Server use SQL as their standard database language. 
![overview](https://www.tutorialspoint.com/sql/images/sql-architecture.jpg)

## How will I use SQL in my ML career
Before starting any ML/DS project, getting the data is a step that can't be skipped. Some of these data reside in different database and you will need to find ways to communicate with them to get the data. SQL is the language of DB and you can easily use SQL to get the data you want.

After completing a DS/ML project, there might be a need to keep collecting data or store the cleaned data into a DB, SQL gives you the easy access to store such data as well. It also allow you to perform some analysis directly from the DB and derive insights that can impact the business.

## Why is it important to understand SQL
Understanding SQL is crucial if you want to communicate with DB, get your data from the Warehouse as well as store your data in a DB. It also gives you an edge in the marketplace during job search. It allow you understand where the data is coming from, how it stored, the kind of values that should be in each column and how different tables relate to each other.

## Key Topics
1. Database: A database is an organized collection of structured information, or data, typically stored electronically in a computer system. A database is usually controlled by a database management system (DBMS). Together, the data and the DBMS, along with the applications that are associated with them, are referred to as a database system, often shortened to just database.Data within the most common types of databases in operation today is typically modeled in rows and columns in a series of tables to make processing and data querying efficient. The data can then be easily accessed, managed, modified, updated, controlled, and organized. Most databases use structured query language (SQL) for writing and querying data. [Read More here](https://www.oracle.com/in/database/what-is-database/)
2. Tables: Tables are database objects that contain all the data in a database. In tables, data is logically organized in a row-and-column format similar to a spreadsheet. Each row represents a unique record, and each column represents a field in the record. [Read More here](https://docs.microsoft.com/en-us/sql/relational-databases/tables/tables?view=sql-server-ver15#:~:text=Tables%20are%20database%20objects%20that,a%20field%20in%20the%20record.)
3. Relationship: It specifies how tables are associated in a DB. Without relationship, there will be no relational DB. [This link](https://www.techrepublic.com/article/relational-databases-defining-relationships-between-database-tables/#:~:text=Database%20relationships%20are%20very%20similar,record%20in%20the%20related%20table.) explains how relationships are formed within a database. For a more indepth explanation [click here](https://condor.depaul.edu/gandrus/240IT/accesspages/relationships.htm). 

![db relationship](https://tr1.cbsistatic.com/hub/i/2015/06/03/7c59d88d-098e-11e5-940f-14feb5cc3d2a/u00320030430ssh01_A.gif)

4. Queries: A query is a way of requesting information from the database, a query is a question. A database query is a request to access data from a database to manipulate it or retrieve it. [click here to learn more](https://www.educative.io/blog/what-is-database-query-sql-nosql)

![query](https://1.bp.blogspot.com/-nfPd26cIiR0/WHc3RFxi6zI/AAAAAAAAHsk/eoSJf-mJxVgSVG9Mb5WRWnBqYiLpYjCiwCLcB/s400/Complex%2BSQL%2BQuery.PNG)

## Learn how to use SQL

1. [SQL Basics for Beginners](https://www.youtube.com/watch?v=zbMHLJ0dY4w): a 27 minute Youtube Video by Edureka on 'SQL Basics for Beginners' which will help you understand the basics of SQL and also sql queries which are very popular and essential.. 
2. Learn and practice SQL with mode: [introduction to intermediate sql](https://mode.com/sql-tutorial/intro-to-intermediate-sql/)
3.Advance SQL Course Kaggle: with the Kaggle SQL course you will master how to use. The link [Kaggle Advanced SQL](https://www.kaggle.com/learn/advanced-sql)
         1. Join and Union
         2. Analytic Functions
         3. Nested and Repeated Data
         4. Writing Efficient Queries

4. SQL for DataScience: a good course that is extremely rich and free, what you'll learn include <br>

Learn and apply foundational knowledge of the SQL language<br>
How to create a database in the cloud<br>
How to use string patterns and ranges to query data<br>
How to sort and group data in result sets and by data type<br>
How to analyze data using Python
[Visit the Website](https://www.edx.org/course/sql-for-data-science?index=product&queryID=42e15053a99ff47b84694f319f1bb15b&position=6)

5. Practice with [SQL Interview Questions](https://learnsql.com/blog/advanced-sql-interview-questions-with-answers/)

### Code TutPlus DB relationships
When creating a database, common sense dictates that we use separate tables for different types of entities. Some examples are: customers, orders, items, messages etc... But we also need to have relationships between these tables. For instance, customers make orders, and orders contain items. These relationships need to be represented in the database. Also, when fetching data with SQL, we need to use certain types of JOIN queries to get what we need.

There are several types of database relationships, examples include:
a. One to One Relationships
b. One to Many and Many to One Relationships
c. Many to Many Relationships
d. Self Referencing Relationships

Here is the link to practice [Database Relationships](https://code.tutsplus.com/articles/sql-for-beginners-part-3-database-relationships--net-8561)

6. Types of Relationship in SQL
One of the most important things in databases is to understand the types of relations in the databases. 
That stands for both – a process of designing a database model as well as when you’re analyzing your data.
Understanding these relations is somehow natural and not so complex but is still essential in the database theory (and practice).
[Read More](https://www.sqlshack.com/learn-sql-types-of-relations/)

