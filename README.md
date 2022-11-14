<img src="ext\images.png" align="left" />
<h1>Taxi-Service</h1>
Service for managing the company's taxi fleet.

<hr>

<h2>Introduction</h2>

☼ This web application allows you to organize and manage data about cars and drivers 
who currently drive cars in your fleet. This application manages a local or remote SQL 
database into which you enter data through a web interface.
To use this service follow the link:
<h4>taxiservise2.us-west-2.elasticbeanstalk.com</h4>

<hr>

<h2>Project structure</h2>
☼ When the user tries to login to the site. The built-in filter is triggered,
which redirects it to the login page. On this page, you need to authenticate or register
and then authenticate.

☼ After authentication, the user is taken to the start page, where they can start adding
new cars to the fleet.

☼ You can also add new drivers and create a connection with previously created vehicles.
It is also possible to view which cars are registered on the current user
by clicking on the appropriate link on the main page.

☼ Below is a diagram of how the application works

<img src="ext\Structure.jpg" />

<hr>

<h1>Used technologies</h1>
List of technology used in project<hr>
-Git<hr>
-Apache Maven<hr>
-Java 8 WEB<hr>
-Java JDBC<hr>
-SQL

<hr>

<h1>Steps to run the program</h1>
☼ Download zip file from repository
Unzip the archive with the project to the IDEA working directory

☼ In IDEA: File -> New -> Project from existing sources - select the project root folder

☼ In next window: Import project from external model (Maven) then "Create".

☼ Download MySQL Workbench or another SQL editor. Create your SQL DataBase, using init_db.sql script in project.

☼ Set up a connection to your database in a file util/ConnectionUtil
Enter your URL, Username, Password and JDBC Driver.

☼ If you don't have Tomcat framework installed, download it.

☼ After you can start your project.

<hr>

<h1>Instruction for using</h1>
☼ Before using the application, you need to register in the database.

☼ After registration, you can create sample manufacturer, car, and another driver,
using the main menu for this.

☼ Link the driver to the car or remove the connection, use the appropriate section 
in the menu.




 
