# *TAXI-SERVICE*
![](src/main/resources/solutions-taxi-park.jpg)

## This taxi service was created to account for cars and drivers of the fleet, as well as the distribution of which taxi driver can drive.
### When creating the project, a three-level architecture was used, in particular:
 - a DAO layer(Data Access Object); 
 - a service layer(implements business logic);
 - and a controller layer were implemented.
### Tools used:
 - IntelliJ IDEA Ultimate IDEA;
 - ApacheTomcat Tomcat (v9.0.50);
 - MySQL and MySQL Workbench MySQL.

### Technologies used:
- MySQL;
- JDBC;
- HTML;
- Maven Checkstyle Plugin;
- Apache Maven;

## To start the project, you need:
 - [install the necessary tools](#Tools used:);
 - make a fork of the project on GitHub to your repository;
 - then, using the link, clone the project to your device;
 - then create a database using the scheme specified in the file;
 - then run Tomcat with the created database;
 - then you can run the project in any browser by entering localhost: the port specified during creation (default 8080) and then "/" endpoint request;
 - when you go to the page, you will be prompted to enter your account by entering your login and password, or create a new one if you have not been registered yet;
 - after entering the main page you will see the menu;
 you can follow the link you need;
![](src/main/resources/img.png)
## Using the links on the main page you can:
 1. Display All Drivers - display all taxi drivers;
 2. Display All Cars - display all cars of the taxi fleet;
 3. Display All Manufacturers - display all car manufacturers located in the taxi depot;
 4. Create new Driver - add a new taxi driver;
 5. Create new Car - add a new car to the taxi fleet;
 6. Create new Manufacturer - add a new car manufacturer;
 7. Add Driver to Car - add information about which driver can drive which car;

