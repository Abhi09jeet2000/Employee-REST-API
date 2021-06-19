# Employee-REST-API
Exposing REST API using Spring Boot

# Employee REST API 
Exposing Rest Api with help of Spring Boot (Java Framework) , Hibernate and MySQL.
This Api is will used Postman as its client.
This Api can perform CRUD Operations.

Here,                                                                                                 
 CREATE  will use # POST method.                                                                                                
 READ will use # GET method.                                                                        
 UPDATE will use # PUT method.                                                                                             
 DELETE will use # DELETE method.                                                                                  
 
-- For reading all employees : http://localhost:8088/api/employees  (GET METHOD)
--                                                                                   
-- For reading only one employee : http://localhost:8088/api/employees/{id} (GET METHOD)             
--                                                                                       
-- For creating new employee : http://localhost:8088/api/employees (POST METHOD) and    
--
-- send json { "firstName": "Jam", "lastName": "Garner", "email": "Jame@code.com" } into the body.
--
-- For updating : http://localhost:8088/api/employees (PUT METHOD) and                 
--
-- send json { "id": {id}, firstName": "Jam", "lastName": "Garner", "email": "Jam@coding.com" } into the body.
--
-- For Deleting existing employee: http://localhost:8088/api/employees/{id} (DELETE METHOD)
