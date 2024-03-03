worldcup.sql contains the pg_dump of database, you can rebuild the databse by entering command in terminal from the folder where the .sql file is located:
psql -U postgres < worldcup.sql
insert_data.sh is the file that automates entering the data in database from .csv file
queries.sh has some queries that can be used on database
make sure the files are executable, to make them executable use command : chmod + x filename (bash)
