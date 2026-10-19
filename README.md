
# Universe Database 🌌

This project was created as part of the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-database/).

## About the Project

The Universe Database is a PostgreSQL project that models the relationships between galaxies, stars, planets, moons, and planet types.

## Database Tables

The database contains five tables:

- `galaxy` — stores information about galaxies.
- `star` — stores information about stars and their galaxies.
- `planet` — stores information about planets and their stars.
- `moon` — stores information about moons and their planets.
- `planet_type` — stores different types of planets.

## Technologies

- PostgreSQL
- SQL
- Relational database modeling

## Features

- Primary keys with automatic increment.
- Foreign key relationships.
- `UNIQUE` and `NOT NULL` constraints.
- Data types such as `VARCHAR`, `INT`, `NUMERIC`, `TEXT`, and `BOOLEAN`.
- Relationships between tables using foreign keys.

## Database Backup

The `universe.sql` file contains the SQL dump used to recreate the database structure and its data.

## Learning Outcomes

- Creating relational database tables.
- Defining primary and foreign keys.
- Using SQL data types and constraints.
- Inserting and querying data.
- Understanding relationships between database tables.

## Author

Created as part of the freeCodeCamp Relational Database Certification.
