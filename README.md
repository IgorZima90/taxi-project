taxi-project

This is elementary application, implements authentication, Logs some 
authentication information, presents CRUD operation.
This application is similar work taxi service, can register drivers and
managing relations between cars, drivers, manufacturers.

program has next functional :
- create a new driver:
- show all drivers:
- create a new car:
- show all cars:
- add a new manufacturer
- show all manufacturers
- add a driver to the car


____________________________________________________________

Architecture

- DAO
- Service
- Controller

______________________________________________________________

Technological

- JAVA 11
- MySQL
- Apache maven
- Apache TomCat ver. 9
- Apache Log4j2 ver. 2.17.1
- JDBC
- JSTL
- JSP
- HttpServlet
______________________________________________________________

How start application

- configuration TomCat
- Install MySQL data bases
- use init_db.sql for creating new schemas 
- Configure Connection from /util/ConnectionUtil with your params
