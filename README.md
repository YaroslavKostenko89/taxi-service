# taxi-service
Simple taxi service, which  keep information about drivers, cars and manufacturers.

Application has functions:
- add car, driver or manufacturer;
- delete car, driver or manufacturer;
- update information about car, driver or manufacturer;
- Show information about car, driver or manufacturer;

Structure of application include:
Java classes:
 - controllers, which execute the function of receiving, processing and transmitting requests from web pages;
 - DAO classes, which execute the function of get, insert, delete and update information in data base;
 - models, which receive information about records in the database;
 - services, which execute the function data processing;

The application uses:
- DB MySQL;
- JDK version 11;
- TomCat version 9;

Before launching the application:
- run script from the resources/init_db.sql file in the Workbench, to create a schema and the necessary tables in the database;
- Configure the server TomCat (if necessary, install it);
- In class ConnectionUtil set you're parameters for connection to DB.
