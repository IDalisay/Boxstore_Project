# Boxstore_Project
A course project creating an example box store business for practicing various tools.

# Boxstore Normalization Process
I was given a set of business rules and an objective to normalize the original databse from 1NF to 3NF. Transformations were first conceptualized in Excel for a clean and clear view of changes. Each page represents a step in the normalization process, from 1NF (ensuring atomic values), 2NF (no partial dependencies on PK), and 3NF (no transitive dependencies, address anomalies). 

The first set of normalization steps was my first attempt. The second set (indicated by (2)) was my second cleaner attempt.
Greyed-out columns represent columns that were moved to other tables. Bright orange highlights indicate anomalies that need to be analyzed in a business context (same items with different prices).

# Boxstore ERD
I created and updated an entity relationship diagram of the database according to new changes. This ERD includes primary keys, foreign keys, and specific SQL data types for every attribute. The relationships between tables are described with cardinalities to further improve readability.

# SQL Script
This was the SQL script used to transform the database according to the changes made during the normalization process. It also includes various simple and complex JOIN practices and VIEWS required by the assignment.
