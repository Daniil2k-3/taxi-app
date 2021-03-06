# Taxi Service
    Neat little program to manage a small transportation business. 
    Inspired by all quarantine Uber, Bolt and Uklon rides. 
In this app you can create and store cars you will use in your business. Each car has it's own list of drivers (as well as model and manufacturer). 
You can log in as a driver to see list of cars that you were using, add or delete a car from your list.
Additionally you can create and store manufacturers for your cars, so you can divide cars in categories in the future.

## With this app you can do:
- Registration and authentication through driver's credentials
- Display list of all present drivers
- Delete of a certain driver from list of drivers
- Create a car
- Display list of all cars
- Delete a certain car from list of all cars
- Display list of cars used by current driver
- Add a certain driver to a certain car
- Create a manufacturer

## Project structure:
3-level architecture 
- DAO level
- Service level
- Controller level

## Technologies used:
- Maven
- JDBC
- Servlet API
- JSP
- Apache Tomcat
- MySQL

## Setup:
- Clone project to your IDE
- Prepare your database by executing init_db.sql
- Configure /main/java/taxi/util/ConnectionUtil for your database
- Configure local Tomcat server
- Run
