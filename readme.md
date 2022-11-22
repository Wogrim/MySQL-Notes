# Getting Started (Windows)



# Big Picture

- **schema** contains a bunch of related *tables*
- **table** contains a bunch of *entries* of the same type of thing, which have the same *attributes*
- **entry** is a row in a table
- **attribute** is a column in a table
- **primary key** is a unique identifier for an entry in the table, usually an integer
- **relationship** is how different tables (*A* and *B*) are related to each other
  - **one-to-many** is when each A can be related to many Bs but each B only has one A
    - a person can own many cars, but a car can only have one owner
  - **many-to-many** is when each A can be related to many Bs, and B can be related to many As
    - a YouTube channel can have many subscribers (users), and a user can subscribe to many YouTube channels
- **foreign key** is a column that references an entry in another table
  - in a one-to-many relationship, the many table has the foreign key column
  - in a many-to-many relationship, a separate table is made with 2 foreign key columns
    - a subscription has
