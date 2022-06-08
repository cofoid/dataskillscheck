# SQL Skill Check (PostgreSQL)
The following exercise should demonstrate your ability to manipulate data using SQL. Please be sure to comment code to indicate what question it answers and feel free to use comments to describe any part of your approach that you believe merits explanation. 

# PostgreSQL Install Instructions
## Windows
1. Download Postgresql:
* Installer for Windows: https://www.enterprisedb.com/downloads/postgresql
* Or if you're feeling Chocolatey: `choco install postgresql` https://community.chocolatey.org/packages/postgresql 
2. Run the Installation
* Uncheck the box for “Stack Builder” as you won’t need it.
* When it asks for a password enter something you will remember. You will need it.
* Don’t change the port for the server.
* It should continue to install. 
3. When installation is done run “pgAdmin” from your start menu
4. Enter that password from installation.
5. Double-click on Servers
6. Right-click on Databases and choose “Create – Database”
7. Name it "dvdrentals" on the Database field and hit save. 
8. Download the dvdrentals database backup here: https://github.com/cofoid/dataskillscheck/tree/main/data/dvdrental
9. Right click on the new "dvdrentals" database and choose Restore. 
10. Leave the first setting on "Custom or Tar"
11. On the file name choose the path to the file you saved (dvdrentals.tar)
* Make sure to choose “All Files” under the format section when searching for the file
* Choose the file from the directory where you downloaded dvdrentals.tar and hit "Select"
* You should now be able to access the dvdrentals schema.
## MacOS
1. Please follow the instructions here: https://www.postgresqltutorial.com/install-postgresql-macos/
2. Restore the dvdrentals.tar database.

# Instructions
After installing and setting up the dvdrentals database in postgresql, please open pgAdmin to complete the following questions. If you have any technical problems please contact the person who sent you this link.
All answers should saved into a txt file; please only submit the SQL code and not the output!
## Questions
1. What are the email addresses of the customers who live in California? 
2. Provide a list of all movies with the actor “Nick Wahlberg”. 
3. What customer has the highest customer ID number whose last name starts with an ‘E’ and has an address ID lower than 500. 
4. What is the average replacement cost for each film rating. Please round to only two decimal places. 
5. Provide a list of customers (first name and last name) who have rented a film in the ‘Horror’ category along with a count of films each customer rented in that category.
6. What films have not been rented? 

## Questions, too
7. Rank customers by sales, including the rank number and sales total for each customer.
8. Rank customers by total sales. For each customer, rank the customer's sales by category. Your final table should show "Total Sales Rank", "Customer Name", "Customer Sales Total", "Rank - Customer Sales in Category",  "Film Category", "Customer Sales in Category" in order.