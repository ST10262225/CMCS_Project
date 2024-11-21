Database connection guidelines 

Open the Command Prompt on your computer. 

Enter the command: sqllocaldb create "claim_system" 

Press Enter to create a new SQL LocalDB instance named "claim_system." The command will display the SQL Server Management version and the name of the created instance. 

Open SQL Server Management Studio (SSMS) and, in the Server Name field, type: (localDB)\claim_system 

Click Connect to establish a connection to the local database instance. 

In SSMS, open a New Query window. 

Create a new database by executing the following command:  

CREATE DATABASE claiming_system; 

USE [claiming_system]; 

Copy the table creation queries from the provided text file into the query window. Highlight all the queries and execute them to set up the required tables in the database. 
