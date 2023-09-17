# Crowdfunding_ETL

For the ETL mini project our group of four students (Group Number 3) was assigned to practise building an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform the data. After transforming the data, we created four CSV files and used the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.

We created a new repository, named `Crowdfunding_ETL` and renamed the `ETL_Mini_Project_Starter_Code.ipynb` to 
`ETL_Mini_Project_group_3.ipynb`.

## Instructions

* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database

### Create the Category and Subcategory DataFrames

1. Extract and transform the `crowdfunding.xlsx` Excel data to create a category DataFrame that has the following columns:

<img src="https://static.bc-edx.com/data/dla-1-2/m13/lms/img/category_DataFrame.png" alt="category DataFrame" tabindex="0">

2. Export the category DataFrame as `category.csv` and save it to the GitHub repository.

3. Extract and transform the `crowdfunding.xlsx` Excel data to create a subcategory DataFrame that has the following columns:

<img src="https://static.bc-edx.com/data/dla-1-2/m13/lms/img/subcategory_DataFrame.png" alt="subcategory DataFrame" tabindex="0">

4. Export the subcategory DataFrame as `subcategory.csv` and save it to the GitHub repository.

### Create the Campaign DataFrame

1. Extract and transform the `crowdfunding.xlsx` Excel data to create a campaign DataFrame that has the following columns:

<img src="https://static.bc-edx.com/data/dla-1-2/m13/lms/img/campaign_DataFrame.png" alt="campaign DataFrame" tabindex="0">

2. Export the campaign DataFrame as `campaign.csv` and save it to the GitHub repository.

### Create the Contacts DataFrame

1. Extract and transform the `contacts.xlsx` Excel data to create a campaign DataFrame that has the following columns:

<img src="https://static.bc-edx.com/data/dla-1-2/m13/lms/img/contact_DataFrame_final.png" alt="final contact DataFrame" tabindex="0">

2. Clean and then export the DataFrame as `contacts.csv` and save it to the GitHub repository.


### Create the Crowdfunding Database
1. Inspect the four CSV files, sketch an ERD of the tables by using __QuickDBD__ http://www.quickdatabasediagrams.com/

2. Use the information from the ERD to create a table schema for each CSV file specifying the data types, primary keys, foreign keys and other constraints.

3. Save the database schema as a Postgres file named `crowdfunding_db_schema.sql` and save it to the GitHub repository.

4. Create a new Postgres database, named `crowdfunding_db`.

5. Using the database schema, create the tables in the correct order to handle the foreign keys.

6. Verify the table creation by running a `SELECT` statement for each table.

7. Import each CSV file into its corresponding SQL table.

8. Verify that each table has the correct data by running   a  `SELECT` statement for each.