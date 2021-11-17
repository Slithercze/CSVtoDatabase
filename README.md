# CSVtoDatabase
java app that imports csv into database 

Test: Create a simple Java application which imports data from files to DB.

The file contains data about companies and their employees.

Required functionality:

The files come to directory on filesystem – format and structure is up to you (CSV).
The application loads the file and imports data to relational database. After that the application moves the file from the input directory to the directory of processed files.
The user is being informed about the status of the import and when the import is finished, he can see the statistics (inserted, updated, duplicated rows etc.).
Entry data – file structure:

Company identification number (unique), company name, company address, employee e-mail (unique), employee name, employee surname, date of last update
