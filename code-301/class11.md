## MongoDB and Mongoose

### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

#### List five differences between SQL and NoSQL databases:

> Data Model - SQL databases follow a structured data model based on tables with predefined schemas, where data is organized in rows and columns while NoSQL databases employ a flexible, schema-less data model.

> Scalability - SQL databases typically scale vertically, which means they handle increased workload by adding more resources to a single server (e.g., upgrading hardware). NoSQL databases are designed to scale horizontally, distributing data across multiple servers or nodes.

> Query Language - SQL databases use Structured Query Language (SQL) as the standard language for defining and manipulating data and provides a standardized way to interact with relational databases. NoSQL databases employ a variety of query languages specific to their data model.

> Data Integrity and Consistency - SQL databases emphasize strong data integrity and consistency. They enforce predefined schemas. NoSQL databases may prioritize scalability and availability over strong consistency.

> Use Cases - SQL databases are often preferred for applications that require complex transactions, structured data, and strict data integrity, such as financial systems, enterprise resource planning (ERP) systems, or traditional relational applications. NoSQL databases are well-suited for handling unstructured or semi-structured data, high-volume writes, real-time analytics, and applications where flexibility and scalability are crucial.

#### What kind of data is a good fit for an SQL database?

> SQL databases are a good fit for managing structured data that can be organized in a tabular format, and can be ideal for applications that require strong consistency, such as financial systems, e-commerce platforms, booking systems, or any application where maintaining data accuracy and reliability is crucial.

#### What kind of data is a good fit a NoSQL database?

> NoSQL databases are suitable for managing various types of data that may not fit well into a traditional tabular, relational model and can be ideal for handling unstructured or semi-structured data, such as JSON documents, XML data, log files, social media feeds, or sensor data. They allow flexibility in storing and retrieving data without imposing a rigid schema.

#### Which type of database is best for hierarchical data storage?

>  SQL databases can handle hierarchical data with certain modeling techniques.
#### Which type of database is best for scalability?

> NoSQL databases are generally considered the best choice

### [nosql vs sql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

#### What does SQL stand for?

> SQL stands for Structured Query Language.

#### What is a relational database?

> A relational database is a type of database that organizes and stores data in a structured manner based on the relational model. It consists of tables that contain rows and columns, where each row represents a record or an instance of data, and each column represents a specific attribute or field of that data.

#### What type of structure does a relational database work with?

> Relational database works with a tabular structure. The data in a relational database is organized into tables, with each table consisting of rows and columns

#### What is a ‘schema’?

> A schema refers to the logical structure or blueprint that defines the organization, design, and relationships of the database objects, such as tables, views, indexes, and constraints. It provides a framework for organizing and representing the data stored in a database.

#### What is a NoSQL database?

> A NoSQL (Not Only SQL) database is a type of database that provides a flexible and non-relational approach to data storage and management.

#### How does it work?

> NoSQL databases are designed to handle large volumes of unstructured, semi-structured, and structured data in a more scalable and flexible manner. The exact working mechanisms may vary depending on the specific type of NoSQL database

#### What is inside of a MongoDB database?

> Inside a MongoDB database, the data is organized into collections. A collection in MongoDB is analogous to a table in a relational database. It is a group of documents that share a similar structure and purpose.

#### Which is more flexible - SQL or MongoDB? and why.

> MongoDB, being a NoSQL database, generally provides more flexibility compared to traditional SQL database due to schema flexibility, no constraints on data types, and easier horizontal scalability.

#### What is the disadvantage of a NoSQL database?

> NoSQL databases have disadvantages such as limited querying capabilities, lack of standardization, weaker data consistency, limited transactional capabilities, less mature ecosystem, and increased redundancy due to denormalization and flexible data models.

*Source*

- [mongoose api](https://mongoosejs.com/docs/api.html#Model)

-[React Router](https://reactrouter.com/web/api/BrowserRouter)
