this is github repo:
https://github.com/SaqerAli/simplilearnGrocerystore.git


steps to run asp.net program for the grocery store:

1-download Online Grocery Shop folder

2-Run sql managment studio (my version is sql server 2019)

3-Attach the GroceryDB database that is in Online Grocery Shop\App_Data folder to your sql server

4-open the project folder in visual studio as a website (chose the whole (Online Grocery Shop) folder)

5-Connect the database to the project you just opend by (chosing Tools/Connect to Database... in visual studio) then put your sql server name and choose the
GroceryDB database and press ok.

6-Replace the connection string in Web.Config file. and you do that by first geeting your connection string from your database connection in visual studio
and you do that by open the server explorer in visual studio and right click your database connection which is (your server name).GROCERYDB.dbo and choosing
properties and copying your connection string then you have to open Web.config and change the connection string with the one you just coped.

7- after all steps are done run Home.aspx with your chrome browser.



Admin user name is: admin

Admin password is: admin