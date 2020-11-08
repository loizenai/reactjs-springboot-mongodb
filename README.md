# React + SpringBoot + MongoDB – SpringBoot React.js CRUD Example

Tutorial Link: [SpringBoot + React + MongoDB tutorial](https://loizenai.com/springboot-reactjs-mongodb-crud/)

![springboot reactjs mongodb](https://loizenai.com/wp-content/uploads/2020/10/Reactjs-SpringBoot-MongoDB-CRUD-Example.png)

In the tutorial, I introduce how to build an “SpringBoot React.js CRUD MongoDB Example” project with the help of SpringData JPA for POST/GET/PUT/DELETE requests with step by step coding examples:

– SpringBoot project produces CRUD RestAPIs with MongoDB database using the supporting of Spring Data JPA.
– React.js project will consume the SpringBoot CRUD RestAPIs by Ajax then show up on Reactjs component’s views.

To do List:

– I draw a fullstack overview Diagram Architecture from React.js Frontend to MongoDB database through SpringBoot RestAPI backend.
– Develop SpringBoot CRUD RestAPIs with the supporting of SpringWeb Framework.
– Implement Reactjs CRUD application with Ajax fetching APIs to do CRUD request (Post/Get/Put/Delete) to SpringBoot Backend APIs.
– I create a testsuite with a number of integrative testcases with CRUD RestAPI requests from Reactjs to do CRUD requests to SpringBoot RestAPIs Server and save/retrieve data to MongoDB database.

## Overall Architecture System: Reactjs + SpringBoot + MongoDB

![Overall Architecture System: Reactjs + SpringBoot + MongoDB](https://loizenai.com/wp-content/uploads/2020/10/Reactjs-MongoDB-SpringBoot-Fullstack-Diagram.png)

- We build a backend: SpringBoot CRUD Application with MongoDB that provides RestAPIs for POST/GET/PUT/DELETE data entities and store them in MongoDB database.
- We implement React.js CRUD Application that use Ajax to interact (call/receive requests) with SpringBoot CRUD application and display corresponding data in Reactjs Component.

## SpringBoot MongoDB CRUD Design Application

![Springboot Mongodb CRUD Design Application](https://loizenai.com/wp-content/uploads/2020/10/Mongo-SpringBoot-CRUD-Full-stack-diagram-architecture.png)

I build a SpringBoot project that handle all Post/Get/Put/Delete requests from RestClient and do CRUD operations to MongoDB database to save/retrieve/update and delete entity from MongoDB and returns back to Restclient the corresponding messages.

We build a SpringBoot project with 2 layers:
– SpringJPA Repository is used to interact with MongoDB database by a set of CRUD operations.
– RestController layer is a web layer for SpringBoot project, it will directly handle all incomming requests and do the corressponding responses to the calling client.

## Reactjs CRUD Application Design

![Reactjs CRUD application design](https://loizenai.com/wp-content/uploads/2020/10/Reactjs-CRUD-RestAPI-Application-Frontend-Architecture-Diagram-4.png)

– Reactjs CRUD Application is designed with 2 main layers:

React.js components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
Ajax is used by Reactjs component to fetch (post/put/get/delete) data from remote restapi by http request

Reactjs CRUD Application defines 5 components:

- Home.js is used serve as the landing page for your app.
- AppNavbar.js is used to establish a common UI feature between components.
- CustomerList.js is used to show all customers in the web-page
- CustomerEdit.js is used to modify the existed customer
- App.js uses React Router to navigate between components.

## Integrative Project Goal

![Integrative Project Goal](https://loizenai.com/wp-content/uploads/2020/10/Project-Goal-List-Customer-after-Delete-successfully-4.png)

Tutorial Link: [Tutorial: SpringBoot + React + MongoDB – SpringBoot React.js CRUD Example](https://loizenai.com/springboot-reactjs-mongodb-crud/)

Reactjs SpringBoot serial tutorials:
- [How to Integrate Reactjs with SpringBoot Tutorial](https://loizenai.com/integrate-reactjs-springboot/)
- [SpringBoot + React + MySQL: SpringBoot React.js CRUD Example](https://loizenai.com/springboot-react-mysql-crud-example/)
- [SpringBoot + React + PostgreSQL: SpringBoot React.js CRUD Example](https://loizenai.com/reactjs-springboot-crud-postgresql/)

Related posts:

- [Angular 10 + Nodejs JWT Token Based Authentication with MongoDB Example – Express RestAPIs + JWT + BCryptjs + Sequelize](https://loizenai.com/angular-10-nodejs-jwt-authentication-MongoDB-examples-tutorials/)
- [SpringBoot + Angular 9 + PostgreSQL CRUD Example – Architecture Diagram](https://loizenai.com/springboot-angular-9-postgresql-crud-example-architecture-diagram/)
