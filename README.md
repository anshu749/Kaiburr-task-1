# Kaiburr-task-1
Tasks-1
Created the project using Spring Framework and for the backend mongoDB is used. The endpoints for the project are

/add (Add the details to the database)
/getById (Retrive the data using ID)
/getByName ( Retrive the Data using name)
/deleteById (Delete from the Database using ID)
The Restfull API's which are beign called were tested using postman. And these are:

/addServer
/findByName
/findByID
/deleteByID
Controller: /Server/src/main/java/com/spring/test/controller

Task 3
To Run in docker.
Open terminal
Go to Server/target
And run docker build . -t server
This will create a image of the JAR file.
Now run the docker-compose.yml using docker-compose up.
Now using web Browser at localhost:8086 we can use the endpoints.
