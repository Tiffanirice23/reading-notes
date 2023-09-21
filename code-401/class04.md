# Data Modeling

## Reading

### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

#### What type of database is the best fit for the complex query intensive environment?

> SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries.

#### What type of database is the best fit for hierarchical data storage?

> NoSQL database is better suited for hierarchical data storage because it follows the key-value pair method or graph method.

#### Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

> SQL databases are like a formal dinner party with a fixed structure, while NoSQL databases are like a flexible picnic where you can adapt and add space as needed. NoSQL databases are often better at handling lots of data and growing to accommodate more, but SQL databases are great for situations where everything needs to be organized and structured in a specific way, like a formal dinner. The choice depends on what kind of "party" (or database) you're hosting!

### [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

#### Among data tables, what is a one-to-many relationship and how do we “relate” them?

> You relate tables in a one-to-many relationship by using primary keys in the "one" table and foreign keys in the "many" table, which connect the two tables based on common values.

> A one-to-many relationship in data tables is a type of association where one record in one table can be linked to multiple records in another table, while each record in the second table is associated with just one record in the first table. This is commonly used in relational databases. To relate them, you establish a connection using a foreign key in the second table, referencing a unique identifier (primary key) in the first table. This allows you to organize and retrieve data efficiently, such as associating books with their respective authors in a library database.

#### Prior to designing your relational database, it might be useful to ______ of the database tables and their relationships.

> create diagrams

#### Explain the difference between a primary and foreign key.

> A primary key is a unique identifier in a table that ensures each row has a distinct identity within that table. It helps enforce data integrity and is used for indexing and quick data retrieval. In contrast, a foreign key is a column in a table that establishes a link between data in two tables, enforcing referential integrity and allowing for relationships between tables. Multiple foreign keys can exist in a table, each referencing a different table, while a table can have only one primary key.

## Data Modeling Videos

### [sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

#### How do we treat keywords and parameters differently in SQL syntax?

> Keywords are fundamental components of SQL queries that define the structure and operation of the query, while parameters are placeholders for values that make queries dynamic and secure. The separation of keywords and parameters is crucial for writing flexible SQL queries
 
#### Define normalization within the context of schemas and data.

> Normalization is a crucial aspect of database design that involves structuring data to minimize redundancy and improve data integrity by adhering to specific rules and normal forms. It helps ensure that data is stored efficiently and accurately in relational databases.

#### Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- One-to-One is like having a unique match for each item.

- One-to-Many is like a parent with multiple children, but each child has only one parent.

- Many-to-Many is like a web of connections where many items are related to many others, like in social networks or student-class relationships.

## Bookmark and Review

[sequelize api](https://sequelize.org/master)

## Reflection

What are your learning goals after reading and reviewing the [class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-04/)?

> Gain more muscle memory when coding a sequelize or collections interface in the backend.

## Things I want to know more about
