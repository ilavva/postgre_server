open postgre shell

- psql
- \conninfo

see databases

- \l

create database

- CREATE DATABASE students;
- \l

connect to database

- \c students

clear window

- \! cls

create table

- CREATE TABLE students (
  ID SERIAL PRIMARY KEY,
  name VARCHAR(255),
  email VARCHAR(255),
  age INT,
  dob DATE);

- CREATE TABLE

display tables:

- \dt
- INSERT INTO student (name, email, age, dob)
  VALUES ('Joe','joe@gmail.com',48,'1973-04-04'),('Anna','anna@gmail.com',23,'2000-01-01');

## References

- https://youtu.be/DihOP19LQdg?si=9vdCWDPjfGwmj_ie
- https://github.com/softwareNuggets/Postgresql-JSON/blob/main/setof.sql
