# SendDataFrom-R-Python-to-SQL-PSQL-Mongo



There are common situations where you would like to interface with different platforms and send data directly. For this short project I will use `R` and `Python` where we will create data for sending to to different databases with function calls.

`Python to Psql`: `psycopg2`

`Python to MongoDB`: `pymongo`

`R to MySQl,PSQL`:  `RPostgreSQL` | `generator` | `randomNames` | `RMysql`

`----------------------------------------`

**`--------MySQL related-----------`**

`Python to Mysql, MongoDB,PostgreSQL`: `psycopg2` | `pyMongo` | `mysql-connect`

`Python_to_mysql_configFiles.ipynb`: create config and ini files to hide your user credentials for login.

**`--------PSQL related-----------`**

`PSQL_JSON.ipynb`: send nested JSON to psql from python and make queries

`Dict_Hstore_Psql.ipynb`: Using HStore in postgresql featuring (psycog2), has the JSON like functionality we need to parse data. 

`HOW TO SEND DATA from Python to PSQL.ipynb`: this will cover using cofig files, using psycopg2 to connect to psogresql, query and send .csv and dataframe, using a memory profiler

`PSQL_video03.ipynb`: using Extract function, plotting with seaborn and creating tables without using Excel

`PSQPL_to_Python_user_def_Func.ipynb`: create a table to store our information, create a user defined function `Trigger`, explain what is a trigger

`Psql_patternMatching.ipynb`: find schema, mogrify, Ilike/Like, trigram, fuzzy match, phoenetic spelling, regex, Levenshtein distance, convert string representation.

`Psycopg2_Views.ipynb`: Create a view, explain purpose of using them and some bonus: date-time queries 

`Psycopg_Join.ipynb`: Inner Join, date-time queries and hurdles with joins

`Python_Psql_injection.ipynb`: describe how to improve query formatting to avoid sql injection attacks and some considerations when using psql with python


**`--------R-studio related-----------`**

`HOWTO Generate Fake Data with R and sending to MYSQL.ipynb`: Using Python faker, to create a fake dataset

`Mongolite_basics.ipynb`: going over basics that will help someone getting started with mongodb using r-studio

`Mongolite_02_Nested.ipynb`: using R-studio, we will interface with mongoDB using `mongolite`. You will see queries, aggregates, map-reduce


**`--------MongoDB related-----------`**

`Mapreduce_PythonMongo.ipynb`: using `pymongo` and using Map-Reduce

`Pymongo Nested docs.ipynb`: Map-Reduce, aggregate, use cases using `pymongo`

