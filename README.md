# sql-challenge

The SQL-Challenge repo includes the following files and directories:
1. .gitignore - ignores access.py file which stores the password for accessing Postgres11 (used in Jupyter notebook to query SQL) and a query developed for the bonus (code can be seen at the bottom of query.sql file) as it is very long
2. Bonus.ipynb - Jupyter notebook querying the EmployeeSQL database in Postgres and used to perform plots on the data. 
3. EmployeeSQL directory:
   - data directory containing the CSV files used
   - ERD Image.png - image of the Entity Relationship Diagram sketched (created using quickdatabasediagrams.com) 
   - Schemata.sql - schemata in SQL format to create the tables and relationships in th EmployeeSQL database. The schemata was generated using the ERD sketched
   - Queries.sql - queries used to solve the 7 data analysis questions posed and the information needed to solve the bonus

To review work, create a database in PostgreSQL/PGAdmin and run Schemata.sql. Import the csv to the like-named table created. Then query the database using Queries.sql. Finally, the last analysis can be viewed in the Jupyter notebook file.

