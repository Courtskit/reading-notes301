# DATABASE NORMALIZATION
- a process used to organize your database into tables and columns
- each table should have a focus on a specific topic, which prevents issues with database modifications later on

**Pros to a database normalization**
- minimize duplicate data
- avoid data modifications
- prevents repetitive data
- simplify queries
- increases performance 
- allows extra storage
- easier to sort and search data

There are different ways to go about storing your database data
- first normal form
  - information is stored in a relational table with each column containing atomic values
  - no repeating groups of columns 
- second normal form
  - table is first normal form and the columns depend on the tables primary key
- third normal form
  - table is in second normal form and all columns aren't transitively reliable on the primary key