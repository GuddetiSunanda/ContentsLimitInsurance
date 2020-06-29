# ContentsLimitInsurance
Dev assignment
Steps to run the project 
1. Update your sql server name in appsettings.json file 
2. This is a code first approach, so please run the following commands to create the database and required tables once the project is build.
    a. Add-Migration "InitialCreate"
    b. Update-Database
3. Insert the follwing data into the reference table "Category"

  USE [CLIDB]
  GO

INSERT INTO [dbo].[Categories]
           ([CategoryName])
     VALUES
           ('Automobile'),
		   ('Furniture'),
		   ('Ornaments'),
		   ('Electronics'),
		   ('Perishable'),
		   ('Stationary')

GO
4.Run the application and insert the data based on the catetory you wish to.. 
