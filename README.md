# CIS 3050-05 Project 2: MS SQL Database Management System

## Introduction

This repository contains a project that I designed, developed, and demonstrated the functionality of a database based on a set of business specifications. I created logical and physical data models using Microsoft SQL Server 2019, MS SQL Server Management Tool.

## Project Description

The project was designed to introduce the various aspects of the SQL SELECT statement and the methods of retrieving data from the database tables. The database system was designed to perform general information management tasks such as systematic collection, update, and retrieval of information for a small organization. 

The aim of the project was to utilize a set of tables that are represented by the ERD and are created and populated by the script file. A customers, artists, items, employees, orders, and order_details tables were created. Information provided by the supplier(instructor) was inserted into the various tables previously mentioned. 

The important data fields are the names of the customers, artists, items, employees - the Id’s of orders, and order_details. In addition to these important requirements for tables, I was provided with several business rules. These rules ranged from different entity types, and if its null or not.

## Steps Involved

1. Designing the database: This involved creating logical and physical data models using Microsoft SQL Server 2019, MS SQL Server Management Tool, and the class textbook.

2. Developing the database: This involved creating tables such as customers, artists, items, employees, orders, and order_details. The tables were updated, deleted, and populated using script files.

3. Demonstrating the functionality: This involved executing various SQL queries to retrieve data from the database tables. Each query had a specific purpose, and it was intended to give certain results for the producer.

## Challenges and Lessons Learned

While working on the tables and fields, I found the need to correctly format my SQL code to make it more readable. Each query had a specific purpose, and it was intended to give certain results for the producer. A lot of the queries were in the customers table and orders table.

I learned that certain operators that were not correct for MS SQL. For example, the DAYNAME operator is used for MySQL and not MS SQL, so I had to work around this and use a different operator called DATENAME. This operator was almost the same, it just needs one more variable, 'weekday'. 

Another problem I ran into was when I went to insert my own name and details for the customer table. There was already a person who was using the specific customer ID the documentation wanted me to use. I had two options, delete the person’s records that were already there or just use a different customer ID and I chose to do the latter. 

## Conclusion

The goal of this project was to create a detailed and correct database management system and I believe I achieved that with all the queries required of me. I hope this repository can be a useful reference for anyone learning about SQL and database management systems. Feel free to explore the code and reach out if you have any questions or suggestions. 

## Deliverables

The completed pdf is the main deliverable of this project. It contains all the queries and visualizations created during the project.

## Acknowledgements

I would like to thank my instructors for their guidance and support throughout this project. I would also like to thank my peers for their valuable feedback and suggestions.

## Contact Information

If you have any questions or suggestions about this project, feel free to reach out to me.
