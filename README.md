# **Build a CRUD Demo using Spring REST**

An example in which I show the usage of Spring REST and Hibernate

It's a simple web customer tracker in which I do CRUD operations in a mysql Database using REST.

The Spring Configuration is done in pure Java (no XML)

* GET customers: http://localhost:8080/spring-crm-rest/api/customers
* GET single customer: http://localhost:8080/spring-crm-rest/api/customers/{customerId}
* POST customer: http://localhost:8080/spring-crm-rest/api/customers

Example in Postman: POST, Body: raw and JSON

{
	"firstName" : "Maria",
	"lastName" : "Pérez",
	"email" : "mperez@neimerc.com"
}
* PUT customer: http://localhost:8080/spring-crm-rest/api/customers

Example in Postman: POST, Body: raw and JSON

{
    "id" : 1,
	"firstName" : "Maria",
	"lastName" : "Rodríguez",
	"email" : "mrodriguez@neimerc.com"
}

Note: There is a sql-script folder to create the schemas and the tables.