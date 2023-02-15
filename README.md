# Convert a Kaggle Dataset into a Postgres Database

In this notebook, I go over the [Goodreads-book Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) on Kaggle and store the data in a PostgresSQL Database. I go over the following:
1. Loading the dataset
2. Performing preliminary analysis to understand the dataset
3. Map out a Entity-Relationship Model to store the data in a database
4. Create database tables
5. Populate the database tables from the dataset using Python
6. Perform complex SQL queries to extract insights from the data

In order to use this notebook, please make sure that an instance of PostgreSQL server is running. You can find more information for downloading Postgres [here](https://www.postgresql.org/download/). Once installed, make sure your instance is listening on localhost at port 5432. You can also change the configuration file db_cred.json depending on how you set up your postgres server. This step is important orelse you won't be able to communicate with the database