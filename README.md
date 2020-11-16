# go-postgres

Simple CRUD application built in golang and using PostgreSQL as DB

# Postgres table

    CREATE TABLE users (
    userid SERIAL PRIMARY KEY,
    name TEXT,
    age INT,
    location TEXT
    );
