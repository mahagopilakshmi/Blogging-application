# Blog

#### Requirements:

- docker

- docker-compose

---

#### Usage:

`docker-compose up blog-backend`

---

#### Architecture:

- This is a basic MVC app which does not have the view. The view could be built with react which is beyond the scope of this assignment.

- The schema of the data models can be found under src/models

- The controllers for each route can be found under src/controllers

- The middlewares authenticating can be found under src/midllewares

  - authenticateUser middleware is used to authenticate a user (by checking if he has sent a valid jwt) and also make sure a user is accessing his own resource and not others resource.

  - authenticateRequest is used only authenticate a user by checking if he has sent a valid jwt token.

- The services host the code that is commonly used in the controllers and can be found src/services

- Commonly used util functions can be found in src/utils
"# Blogging-application" 
