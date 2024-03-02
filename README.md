Projects Course Enrollment Microservices, Spring Cloud, Spring Boot, React, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **microservice-user-management** - Microservice implemented using Spring boot. 
- **microservice-course-management** - Microservice implemented using Spring boot. 
- **eureka-discovery-service** - Microservice implemented using Spring eureka. 
- **zuul-gateway-service** - Microservice implemented using Spring zuul. 
- **client-side** - A NodeJs application implemented using React. This consumes services hosted by server side. 

### Build

#### 1) Build Spring Boot microservices
   
```
$ cd microservice path
$ gradlew bootJar
$ gradlew bootRun
```

#### 2) Build and run client side application

```
$ cd client-side
$ npm install
$ npm start
```

### Access application using following URL

```
http://localhost:3000
```
