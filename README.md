Create customers table

[Syntax:id INT
        first name VARCHAR(45)
        last name VARCHAR(45)
        email VARCHAR(45)]

SHOW DATABASES;

CREATE DATABASE cinema_system;

USE cinema_system;

CREATE TABLE customers(
      id INT PRIMARY KEY AUTO_INCREMENT,
      first name VARCHAR(45), 
      last name VARCHAR(45) NOT NULL,
      email VARCHAR(45) NOT NULL UNIQUE,
)
SHOW TABLES;

DESCRIBE customers;
