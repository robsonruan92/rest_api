
# REST API with Flask

The idea is a laboratory where we will build a Rest API using the Flask framework.

- Build a REST API with three routes (endpoints):
  - ` /users to return all users (GET)`   
  - ` /user/<document_id> to return a specific user (GET) `
  - ` /user to register a new user (POST) `
-  Persist data in a database(`MongoDB`);
-  Configure the application to run inside a Docker container (`Dockerfile`);
-  Create a docker-compose to compose the API together with the database (development environment);
-  Write unit tests for the routes;
-  Use a Makefile to automate the most common steps;
-  Deploy the application on a PaaS platform (`Heroku`);
-  Create a CI/CD pipeline using an "as a service" tool (`GitHub Actions`);

Why use MongoDB?

- I used MongoDB because it's a document database, it doesn't have tables or schemas, and because it's not a relational database it was a good option.


#### Important to install

- Docker
- Python
- VSCode
- Postman or Insomnia
- Heroku CLI

#### Project Architecture

![Screenshot](/images/project_architecture.png)