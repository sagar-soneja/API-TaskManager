# CLI Commands REST API (Task Manager)
API Link :- https://task-manager-ssoneja.herokuapp.com (if it's down it means I unfortunately ran out of my Free Credits)
#### It is Task-Manager-API which is used to create "User" and its "Tasks" using CRUD operations. Each task is dependent or created by specified user and no other user can delete or create the task of other user. ### The purpose of this project is to learn and practice concepts related to:
> - Building a REST API
> - NodeJS
> - Express
> - JWT
> - Testing (JEST)

#### More specifically, I used the following:
> - NodeJS and Express for creating end points
> - MongoDB Server For Database 
> - RESTful API guidelines
> - HTTP (GET, POST, PUT, PATCH, DELETE, status codes)
> - JWT Authentication 
> - Testing API Endpoints (Postman)
> - Heroku (Deployment)
> - Jest and SuperTest (Testing)
> - Version control with Git

### How to use :-
> - Install Postman( https://www.postman.com/ )
> - In Postman :- 
> - - Create collection name as Task App (or as u want), then go in edit :-

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env1.png)

- Then in Authorization change Type as Bearer Token and Token as {{authToken}}

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env2.png)

- Then Before making every Request change its Test to :-

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env3.png)

- and its Authorization to :- 

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env4.png)

- go to environments 

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env5.png)

- and make global variable and current value as :- 

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/env6.png)

- All of the above setting will save you from putting user id for authentication again and again during Requesting API, Now you good to go to use the API

### User Model :-

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/usermodel.png)

### Task Model :-

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/taskmodel.png)

### API Endpoints (CRUD):-

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/head.png)

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/user.png)

![image](https://github.com/sagar-soneja/API-TaskManager/blob/main/Pics/task.png)

