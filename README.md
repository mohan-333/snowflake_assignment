# Snowflake Assignment

This repository contains solutions to the Snowflake assignment questions. Below is a brief overview of each question and its corresponding solution.

## Question 1: Creating Roles

Roles such as admin, PII, and Developer are created in Snowflake. These roles are granted specific privileges and access to warehouses and databases.

## Question 2: Creating Warehouse

A Snowflake warehouse named assignment_wh is created with a medium size and standard type. This warehouse will be used for executing queries.

## Question 3: Switching Roles

The admin role is switched to perform administrative tasks.

## Question 4: Creating Database

A database named assignment_db is created within which tables will be stored.

## Question 5: Creating Schema

A schema named my_schema is created within the assignment_db database to organize tables logically.

## Question 6: Creating Tables

Internal and external tables are created to store employee data. These tables define the structure of the data to be stored.

## Question 7: Creating Variant Table

A variant table is created to store semi-structured data using the VARIANT data type.

## Question 8: Loading Data into Stages

Stages are created to hold data files before loading them into tables. External data files are uploaded to a stage using PUT command.

## Question 9: Loading Data into Tables

Data from the staging area is copied into the internal and external tables using the COPY INTO command.

## Question 10: Uploading Parquet File and Inferring Schema

A Parquet file is uploaded to a stage and a schema is inferred without loading it into a Snowflake table.

## Question 11: Querying Staged Parquet File

Select queries are run directly on the staged Parquet file without loading it into a Snowflake table.

## Question 12: Adding Masking Policies

Masking policies are created to mask sensitive data (like email and phone numbers) for users with the Developer role while allowing visibility to users with the PII role.

These solutions demonstrate various questions related to managing data and access permissions within Snowflake.
