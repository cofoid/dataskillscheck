# SQL Skill Check (PostgreSQL)
The following exercise should demonstrate your ability to manipulate data using SQL. Please be sure to comment code to indicate what question it answers and feel free to use comments to describe any part of your approach that you believe merits explanation. 

# PostgreSQL Install Instructions
These directions are specific to Windows. If you already have PostgreSQL installed you may skip to the database import section. If you are using another OS, please install PostgreSQL appropriately there and skip to the database import section.
1. Download Postgresql here (for Windows): https://www.enterprisedb.com/downloads/postgrespostgresql-downloads
2. Run the Installation
* Uncheck the box for “Stack Builder” as you won’t need it.
* When it asks for a password enter something you will remember. You will need it.
* Don’t change the port for the server.
* It should continue to install. 
3. When installation is done run “pgAdmin” from your start menu
4. Enter that password from installation.
5. Double-click on Servers
6. Right-click on Databases and choose “Create – Database”
7. Name it “dvdrentals” on the Database field and hit save. 
8. Right click on the new “dvdrentals” database and choose Restore. 
9. Leave the first setting on “Custom or Tar” 
10. On the file name choose the path to the file you saved (dvdrentals.tar)
* Make sure to choose “All Files” under the format section when searching for the file
* Choose the file from the directory where you downloaded dvdrentals.tar and hit "Select"
* You should now be able to access the dvdrentals schema.

# Instructions
After installing and setting up the dvdrentals database in postgresql, please open pgAdmin to completely the following questions. If you have any technical problems please contact the person who sent you this link.
All answers should saved into a txt file; please only submit the SQL vode and not the output!
## Questions
1. What are the email addresses of the customers who live in California? 
2. Provide a list of all movies with the actor “Nick Wahlberg”. 
3. What customer has the highest customer ID number whose name starts with an ‘E’ and has an address ID lower than 500. 
4. What is the average replacement cost for each MPAA rating. Please round to only two decimal places. 
5. Provide a list of customers (first name and last name) who have rented a film in the ‘Horror’ category along with a count of films each customer rented in that category.