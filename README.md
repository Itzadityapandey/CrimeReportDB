# CrimeReportDB

In this guided project from Dataquest's Data Engineering track, I developed a PostgreSQL database to store information about crimes in Boston. The dataset used for this project was **boston.csv**, provided by Dataquest. My objectives for the project included:

- Creating a PostgreSQL database called `crime_db` with a table named `boston_crimes`
- Designing the table with appropriate data types to store the contents of `boston.csv`
- Organizing the table under a schema named `crimes`
- Establishing two user groups, `readonly` and `readwrite`, with distinct access privileges
- Creating two user accounts, `data_analyst` and `data_scientist`, and assigning them to the `readonly` and `readwrite` groups, respectively
- Ensuring the user groups had the correct permissions

To achieve these objectives, I followed a structured approach:

1. Installed PostgreSQL and the `psycopg2` module.
2. Created the necessary database and schema.
3. Examined the `boston.csv` file to understand the column structure and determine the appropriate data types for each field.
4. Defined the `boston_crimes` table using the correct data types.
5. Loaded the crime data from the CSV file into the PostgreSQL table.
6. Created the `readonly` user group, granting it privileges to connect to the database, access the schema, and select data from all tables.
7. Created the `readwrite` user group, which has the same permissions as `readonly` but with added rights to insert, delete, and update data.
8. Set up user accounts `data_analyst` and `data_scientist`, assigning them to the `readonly` and `readwrite` groups, respectively.
9. Tested the database to verify that the objects were correctly created and that user groups had the appropriate access levels.

By the end of the project, I successfully built a PostgreSQL database to manage Boston crime data, complete with appropriate user groups, privileges, and security settings.
