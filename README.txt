Data Warehousing report:

Introduction:
The topic of the assignment was to generate a data warehouse and create it using dimensional modelling. Furthermore, we had to create ETL pipelines to perform analysis on the same.
The company chosen to perform the calculation was Amazon. However, since information like this is not realistically available, the python library Faker was used to generate the data synthetically.
The three databases chosen to create the warehouse with are the Customers database, Products database and Transaction Database.
The Tech Stack used to create data Warehouse and perform pertinent calculations is the Community edition of Databricks.
To store the data we have used the Databricks file storage system or DBFS for short.

Procedure:
I have used Pyspark to create dataframes out of the existing tables so as to be able to perform Pyspark queries from them.
I have created staging tables or tempViews of the dataframes to perform SQL queries on them.
Since the standard table will be normalized for OLTP architecture I have created dimensions out of the views to be able to perform accurate analyses on them.
Once the dimensions have been created I have completed the ETL pipelining using pandas.
Using SQL and pyspark I have also performed the required querying to provide the following results.

Conclusion:
The Choice Tool was the best selling product by revenue.
Only 30% of the customers are prime members.
The highest revenue earned was in the month of October of 2024.

