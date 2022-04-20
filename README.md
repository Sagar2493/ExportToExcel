# ExportToExcel
This project has made for to implement for exporting Sql table data into excel format

As this project is made by EF Code First approach. So to run in local create one local db in your machine. As I used (LocalDb)\\MSSQLLocalDB.
If you want to use any other instances of sqldb you can also you can change the Database name as well

So in your visual studio just run these command below : 
Step 1 : Add-Migration InitialMigration
Step 2 : Update-Database


Add some sample data quickly to your db:

 insert into [dbo].[customers] (first_name, last_name, phone, email, street, city, state, zip_code)
  values ('sagar','chowdhury','8145859159','test@gmail.com', 'bagnan','howrah','west bengal','711303')

  insert into [dbo].[customers] (first_name, last_name, phone, email, street, city, state, zip_code)
  values ('Tridib','Sardar','8145859159','test@gmail.com', 'Narendrapur','South 24 pgns','west bengal','600089')

  insert into [dbo].[customers] (first_name, last_name, phone, email, street, city, state, zip_code)
  values ('Monotosh','Dey','8145859159','test@gmail.com', 'New Town','North 24 pgns','west bengal','700056')
