# Crowdfunding_ETL
ETL mini project
This project is an example of ETL (Extract, Transform, Load) pipeline utilizing Python, Pandas, and PostgreSQL. The main objective is to effectively handle crowdfunding data extracted from Excel files, transforming that data into a structured format and subsequently loading it into a relational database system.

Background
The venture provided a practical setting to develop skills in constructing an ETL pipeline focused on crowdfunding initiatives. The process involved:

Extraction of pertinent information from source Excel files.
Data transformation and cleansing to facilitate database storage.
Creation of intermediary CSV files to transition from raw data to a format suitable for database insertion.
Designing an Entity Relationship Diagram (ERD) to visually map out the database schema.
Developing the table schema corresponding to the ERD for the PostgreSQL database.
Loading the refined data into a newly created PostgreSQL database, forming the basis for data analysis and reporting.
Features
Extraction and transformation of comprehensive data related to crowdfunding and associated contacts from source Excel files.
Generation and export of processed data into CSV files across four distinct categories: Category, Subcategory, Campaign, and Contacts.
Design and implementation of a database schema through an ERD to ensure data integrity and relationships.
Creation of a PostgreSQL database, along with the population of tables with the processed data.
Installation
Obtain the project files by cloning the repository.
Install the necessary Python packages: pandas, openpyxl, and psycopg2.
Configure a PostgreSQL server and initialize a new database titled crowdfunding_db.
Usage
Execute the Jupyter Notebook to carry out the ETL process, which will extract, transform, and export the data into CSV files.
Utilize the crowdfunding_db_schema.sql script to construct the required tables within the PostgreSQL database.
Import the data from the CSV files into the respective tables in the PostgreSQL database.
Conduct queries on the database to ensure the integrity and accuracy of the loaded data.
Built With
Python: The primary programming language used for scripting the ETL process.
Pandas: A powerful data manipulation library in Python used for processing and transforming the data.
PostgreSQL: The relational database system where the transformed data is stored and queried.
Jupyter Notebook: An interactive computing environment that facilitates live code execution, which was used to document and run the ETL pipeline.
Excel: The source from which the raw crowdfunding data was extracted.
License
The Crowdfunding ETL Project falls under the MIT License, promoting open-source usage and distribution.
