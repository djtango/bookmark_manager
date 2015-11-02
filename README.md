# Makers Academy: Bookmark Manager
## User Stories:
```
As a user
So that I can keep track of a list of websites
The product should show me a list of links
```

```
As a user
So that I can add to a list of websites
I would like to be able to store additional links by title
```

```
As a user
So that I can add to a list of websites
I would like to be able to store additional links by url
```

```
As a user
So that I can easily find links later that I am interested in
I would like to be able to tag links
```

```
As a user
So that I can easily retrieve links
I would like to be able to filter by tag
```

## Relative merits of Relational databases vs NoSQL databases or flat files
In a relational database, data is typically constructed in a table-row-column format. Tables are typically used to represent an "entity type", i.e. a Class. Rows are typically used to represent instances of the entity type, i.e. an instance of a Class, and Columns are used to represent properties of the instance, i.e. instance variables. A relational database employs the use of a unique key within each row of the table, so that entries can easily be located and retrieved.

By comparison, NoSQL (Non-Relational Structured Query Language) is not restricted to the relational model of data storage. Some types of NoSQL databases include:
- Column
- Document
- Key-Value
- Graph
- Multi-model

These models introduce some flexibility into data storage and compensate for some of the short-comings of the Relational Database Model. Some advantages include improved horizontal scaling and simpler designs, which may prove problematic to implement in a Relational Database (e.g. a hierarchy).
