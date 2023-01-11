# Data-Modeling-with-Postgres
In this project, I am building an ETL pipeline using Python by applying Data modeling with Postgres concepts. I define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL 

The project is for a startup called Sparkify that wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. Particularly interested in understanding what songs users are listening to. Currently, the project aims to provide an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

The project includes six files:

test.ipynb - displays the first few rows of each table to let you check your database.

create_tables.py - drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts.

etl.ipynb - reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.

etl.py - reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook.

sql_queries.py - contains all your sql queries, and is imported into the last three files above.
