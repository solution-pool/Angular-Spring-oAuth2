# Angular + Spring Boot Single Page Application
Example project of a Single Page Application developed using- AngularJS (UI) + String Boot (Backend) + OAuth2 (Authentication)

# Modules
This project has 3 modules:

**ui**

	- User interface developed using Angular + Bootstrap + Jquery
	
	- Url: http://localhost:8001/
	
**services**

	- REST Backend developed using Spring Boot
	
	- Url: http://localhost:8002/services
	
**auth**

	- OAuth2 login portal developed using Spring Boot
	
	- Url: http://localhost:8003/auth
	
# What do you need?
- JDK 8
- Maven	
- PostgreSQL (or other SQL database)

# Steps
1 - Create the database using the **create_database.sql** file

2 - Start the modules using the command **mvn spring-boot:run** inside each directory 

3 - Type **http://localhost:8001/** into your browser

