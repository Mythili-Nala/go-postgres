# go-postgres

Simple CRUD application built in golang and using PostgreSQL as DB

# Postgres Setup

PostgreSQL is a powerful, open-source object-relational database system. It is known for reliability, feature robustness, and performance.

There are following methods to use a postgreSQL:

Local Setup
Cloud Based: ElephantSQL, Azure, AWS, GCP
Docker Image

ElephantSQL is a PostgreSQL database hosting service.

Go to the Browser tab in the ElephantSQL and paste the below create table query and execute it.

# Postgres table

    CREATE TABLE users (
    userid SERIAL PRIMARY KEY,
    name TEXT,
    age INT,
    location TEXT
    );
