DATA MODELLING AND ETL IN POSTGRESQL USING PYTHON

This project involves developing a STAR schema to load the Million song dataset which is available in a JSON format 
into 5 different tables (songplays, artists, songs, users, time) using Python 

libraries used: psycopg2, pandas, json, blob, os, datetime

files:

test.ipynb - test functions to check creation and insertion scripts (Jupyter Notebooks)

create_tables.py - this file contains functions to drop and create the database, and drop and create respective tables in the database. This script helps you to automate and test the overall progress through the project everytime you complete a piece of project. 

etl.ipynb - The entire ETL process and functions built step-by-step to load the data, select the repective columns from the data needed for the tables (from log data and songs data)

etl.py - The complete ETL script that fetches the files in the directories, loads it into pandas and execute necessary SQL statements from sql_queries.py and complete the ETL process into Sparkify Database.

sql_queries.py - all the necessary SQL Statements to create the table, drop the tables, insert records into tables and select data from tables.



ETL process:

1)download all the files into your workspace and directory.

2)Open a new jupyter notebook and run the following code:

import create tables

create_tables.main()

import etl

etl.main()

3)ETL should now be complete.

4)Test the ETL process using the test.ipynb file to check if the data is staged into the respective tables in the appropriate model.







