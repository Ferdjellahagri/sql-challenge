# sql-challenge


In this repository for the SQL challenge homework holds the results of the SQL queries and the Bonus exercise.
Inside the EmployeeSQL folder, you will find the following subfolders and contents:
1. 01_Data. This folder contains 6 CSVs containing the raw data that wwas analyzed.
2. 02_ERD Diagram. This folder contains the Entity Relationship Diagram in .PNG format, showing how the .CSV data was mapped and linked together. It also contains the set of code that was used in Quickdatabasediagrams.com to generate the png.
3. 03_SQL Code. This folder contins 2 .SQL files. DB_Creation.sql is the code output from Quickdatabasediagrams.com, formatted for PostgreSQL; when imported into PostgreSQL, this will generate the Tables used to hold the data in the EmployeeSQL database. DB_Query.sql is the code to generate 8 queries on the data in the EmployeeSQL database.
4. 04_Bonus. This folder contains a Jupyter Notebook labeled "Exploratory Analysis.ipynb", which imports the data from the EmployeeSQL database via SQLAlchemy and analyzes key salary trends. The Observations.md explains the common trends. The Images folder contains images that were generated in the Jupyter Notebook and were used in the Observations file.

