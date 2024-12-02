State and Explain the components of a DBMS(Database Management System)
A Database Management System (DBMS) is a software system that manages databases and provides the functionality to store, modify, and retrieve data efficiently. The main components of a DBMS are:

Database Engine: The core part of the DBMS that manages data storage, retrieval, and updates. It provides the interface between the database and the applications or users accessing the data.

Database Schema: Defines the structure of the database, including tables, views, indexes, relationships, and constraints. It acts as a blueprint that defines how data is organized and manipulated.

Query Processor: Handles SQL queries (or other query languages), interprets them, and sends the appropriate commands to the database engine for execution. It optimizes queries for better performance.

Database Manager: Manages user access control, ensuring that only authorized users can access or modify data. It handles transaction management, concurrency control, and recovery.

Data Dictionary: Contains metadata about the database, including details like table names, column types, and relationships between tables. It helps the DBMS understand the structure of the database.
What is a relational database? Give 4 examples.
is a type of database that stores data in a structured format using rows and columns. Each table (or relation) represents an entity, and the columns represent attributes of that entity. Data is stored in tables, and relationships between tables are defined through keys (primary and foreign keys).

Examples of relational databases include:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server

State and Explain three classifications of SQL?
Data Query Language (DQL): Used to query and retrieve data from the database.
Example: SELECT
Data Definition Language (DDL): Used to define, modify, and delete database objects (like tables, indexes, and schemas).
Example: CREATE, ALTER, DROP
Data Manipulation Language (DML): Used to manipulate and modify the data within the database (insert, update, delete).
Example: INSERT, UPDATE, DELETE
What is the difference between a Primary Key and a Foreign Key?
Primary Key: A primary key is a unique identifier for each record in a table. It ensures that no two records have the same value for the primary key column(s) and cannot have NULL values.

Example: In a Customers table, the CustomerID might be the primary key.

Foreign Key: A foreign key is a column (or combination of columns) that refers to the primary key of another table. It establishes a relationship between two tables.

Example: In an Orders table, CustomerID might be a foreign key that references the CustomerID in the Customers table.
What is an Entity-Relationship Diagram?
(ERD) is a visual representation of the entities in a database and the relationships between them. It helps in designing the database structure and understanding how different tables are connected.

Entities: Represent objects or things within the database (e.g., Customer, Order).
What are the advantages of relational databases?
Data Integrity: Ensures accuracy and consistency of data through constraints (e.g., primary keys, foreign keys).
Flexibility: Supports various types of queries (complex joins, aggregations) to retrieve data.
Scalability: Can handle large amounts of data efficiently and scale with increased storage needs.
Normalization: Helps organize data in such a way that reduces redundancy and improves data integrity.
Data Security: Provides mechanisms to control access and ensure only authorized users can perform specific operations.
ACID Properties: Ensures reliable transaction processing (Atomicity, Consistency, Isolation, Durability).
State four types of data type used to store data in tables?

What is the purpose of a database management system (DBMS)?
