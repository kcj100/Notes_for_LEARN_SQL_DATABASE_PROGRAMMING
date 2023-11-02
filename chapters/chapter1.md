# Chapter 1

## Elements of SQL (Page 10-11)
* SQL elements consists of quieres, clauses, predicates, expressions, statements, and white space.
* Queries that retrieve data based on specific criteria.
* Clauses that are components of statements or queries.
* Predicates that are logical conditions that evaluate to true or false. These help you to narrow down the results of your queries.
* Expressions that produce either scalar values or tables of columns and rows. Expressions are a part of predicates.
* Statements that are queries run against a database, comprised of clauses and, optionally, expressions and predicates.
* White space that is generally ignored in SQL statements and queries, making it easier to format for readability because you don't have to worry so much about particular spacing for the SQL to run correctly.
* Clauses use SQL keywords.

## Understanding databases (Page 11)
* Databases are stored in a relational database management system (RDMS)

## Tables (Page 12)
* In RDMS, objects called tables store data.
* Tables are a collection of related data stored in columns and rows.

## Fields (Page 12)
* A field is an intersection of a row and a column.

## Understanding data integrity (Page 13)
* Data integrity refers to the consistency and accuracy of the data.
* In RDMS, keys enforce data integrity. A key is user-defined and forces values in a table to conform to a specified standard.

## Types of integrity (Page 14)
* Data integrity refers to the consistency and accuracy of data and table relationships. The following table lists the types of integrity you can use are Entity integrity, Referential integrity, Domain integrity.

### Entity integrity (Page 14)
* If you want each row in a table to be identifiably unique, entity integrity will need to be used.

#### Unique constraints (Page 14-15)
* Unique constraints ensure that all values in a column or columns are different from each other, hence duplicate data will be avoided.

#### Not null constraints (Page 16)
* A not null constraint is used to ensure all values in a column are not null.
They will be forced to contain a value.

#### The primary key
* 

