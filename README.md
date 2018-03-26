# FinalExamBPapp
This repository is to support Bence's final exam at Green Fox Academy.

# Foundation requirements ------------------------

## Accomplishments

 -  [Multiple daily commits on the latest week](http://s2.quickmeme.com/img/cf/cf538c211f84e60777be2e390691dde58737d3378b3f16d18557ba09deeb9275.jpg)  
   
     
[My repo](https://github.com/expertneo)  
[Checkout project repo](https://github.com/greenfox-academy/daily-checkout/)

## Skills

The student, on their own, is able to:

 -  Use the command line:
     -  Traversing directories (cd c:/Bence/Lol; cd ..)
     -  Moving, copying, creating, deleting files (mv root/bence.txt root/gfacademy/; cp to copy; rm to detele, touch to create)
     -  Passing command line arguments to commands (???)
 -  Use git:
     -  Commit, add, push, pull (OK, check [checkout repo](https://github.com/greenfox-academy/daily-checkout/))
     -  Review other's code (OK, check [checkout repo](https://github.com/greenfox-academy/daily-checkout/))
 -  Follow indentation and coding styleguides in their code (check any code, I followed google styleguide)
 -  [Create variables and methods on a given specification](http://s2.quickmeme.com/img/cf/cf538c211f84e60777be2e390691dde58737d3378b3f16d18557ba09deeb9275.jpg)
 -  [Use conditions and loops:](https://github.com/expertneo/corsac-basic-exam/blob/master/Exercise2/test.java)
     -  Filtering
     -  Finding elements or index
     -  Generating lists
     -  Checking multiple values and counting
     -  [Maping values](https://stackoverflow.com/questions/23213891/how-to-map-values-in-a-map-in-java-8)
 -  Use object orientation:
     -  Create and inherit classes including fields and methods on a given specification [link](https://github.com/greenfox-academy/expertneo/tree/master/week-04/day-2/gardenApplication/src)
     -  Understanding the difference between classes and objects(Once class can be called several times creating several objects..)
     -  Instantiating and using objects [link](https://github.com/greenfox-academy/expertneo/blob/master/week-08/day1/Todo/src/main/java/com/greenfox/todoapplication/models/ToDo.java)
     -  Understanding "this" keyword (this is an alias or a name for the current instance inside the instance)
 -  Handle errors and exceptions [link](https://github.com/greenfox-academy/daily-checkout/blob/developement-jacobs/src/main/java/com/greenfox/checkout/controllers/SlackController.java)
 -  Determine the output of expressions (can do it in real time if you want)
 -  Explain their own code
 -  Write unit tests for functions and methods [link for integration test](https://github.com/expertneo/corsac-orientation-exam/blob/master/spacetransporter/src/test/java/com/greenfox/spacetransporter/SpacetransporterApplicationTests.java)  
 [link for unit test](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/test/java/com/greenfox/checkout/services/DateUtilTest.java)
 
 
 # Backend Orientation Exam Competencies ------------------------

## Interfaces and abstract classes

- usage of interfaces and abstract classes [link for abstract usage](https://github.com/greenfox-academy/expertneo/tree/master/week-06/day-2/Instruments/src/main/java/music)  [link or interface usage](https://github.com/greenfox-academy/expertneo/tree/master/week-06/day-2/Printable/src)
- understanding the difference between interfaces and abstract classes [external link](https://i.stack.imgur.com/pghvG.jpg)
- understand when to use interface and when to use super class [Diamond problem nice explanation](https://www.journaldev.com/1775/multiple-inheritance-in-java)

## Queries

- usage of language integrated quaries e.g. LINQ/StreamApi (Have never heard of this during GreenFox)
- understanding the syntax (=.=)
- able to write simple custom quaries [link for some of my queries](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/java/com/greenfox/checkout/repositories/CheckoutRepo.java)

## Build tool

- use build tools to build and run your applications e.g. gradle/.Net CLI (gradle build -x test :D)
- dependency definition [link for description](https://docs.gradle.org/current/userguide/introduction_dependency_management.html)
- able to restore 3rd party library dependencies [JSLACK](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/java/com/greenfox/checkout/services/SlackService.java)  [Lombok](https://github.com/greenfox-academy/expertneo/blob/master/week-11/ExamPractice/src/main/java/com/greenfox/spaceshippractice/models/Planet.java)

## 3rd party libraries

- able to add and use libraries [link for injecting dependencies](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/build.gradle)
- find documentation and usage examples [link for documentation](https://github.com/seratch/jslack)

## Backend Framework

- creating a Web Application with the given backend framework e.g. Spring/ASP.Net Core (can check any code in my repo)
- understanding the used components (yes, i understand the components)
- find documentation and usage examples (i am able to do it)
- understanding the framework and the application as web backend (Frameworks are large bodies (usually many classes) of prewritten code to which you add your own code to solve a problem in a specific domain.)
- able to create examples for competencies of web backend (not sure what the question is)
- using a templating system e.g. Thymeleaf/Razor Pages [controller link](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/java/com/greenfox/checkout/controllers/mentor/MainController.java)  [thymeleaf link](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/resources/templates/mentor/aggregateSummaryView.html)
- able to use the framework's special Dependency Injection system (autowire, refer to the checkout code)
- usage of the framework's IoC container[link](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/test/java/com/greenfox/checkout/configurations/TestConfig.java)  [link for Inversion of Control](https://docs.spring.io/spring/docs/3.2.x/spring-framework-reference/html/beans.html)
- able to alter basic configurations (have never touched bean configuration file)
- understanding the flow of HTTP [link for external description](https://stackify.com/spring-mvc/)

## Data persistance

- understanding and usage of basic SQL commands [link to external source](https://www.w3schools.com/sql/default.asp)
  - `select` (SELECT * FROM table_name;)
  - `insert` (INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);)
  - `update` (UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;)
  - `delete` (DELETE FROM table_name
WHERE condition;)
- connecting database to backend application [link to application properties](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/resources/application.properties)
  - database framework configuration
- understanding Object Relational Mapping [link to visually represent ORM](https://i.stack.imgur.com/seqRv.jpg)
  - with using library: JPA/EF Core [JPA explanation for noobs](https://www.quora.com/What-is-Spring-Data-JPA-in-simple-words)
- connection between:
  - tables and classes
  - records and objects
  - columns and fields/properties

Hibernate: (Hibernate ORM is an object-relational mapping tool for the Java programming language. It provides a framework for mapping an object-oriented domain model to a relational database. Hibernate is an ORM framework - you describe how your objects are represented in your database, and hibernate handles the conversion)   
[link for representing hybernate](https://www.javatpoint.com/images/hibernate/architecture.jpg)   
[simple explanation](https://www.quora.com/What-does-Hibernate-do-in-Java-in-simple-language)

JPA: (The Java Persistence API (JPA) is a Java application programming interface specification that describes the management of relational data in applications. JPA gives us CrudRepository extension for example.)   
[link to represent JPA usage](http://javasampleapproach.com/wp-content/uploads/2017/08/angular-4-spring-jpa-mysql-spring-boot-architecture.png)   
[JPA explanation for noobs](https://www.quora.com/What-is-Spring-Data-JPA-in-simple-words)

JDBC: (Java Database Connectivity is an application programming interface for the programming language Java, which defines how a client may access a database. JDBC is the API for database access, and it works "in a relational way" - you query tables and get rows and columns back. Hibernate uses JDBC under the hood to fetch the data and later convert it to objects.)   
[link for making it clear what the JDBC is](https://www.tutorialspoint.com/jdbc/images/jdbc-architecture.jpg)   

ORM: (Object Relational Mapping; ORM allows you to use java objects as representation of a relational database. It maps the two concepts (object-oriented and relational))  
[link to visually represent ORM](https://i.stack.imgur.com/seqRv.jpg)

## Web backend

- domain (Domain names are used to identify one or more IP addresses. For example, the domain name microsoft.com represents about a dozen IP addresses. Domain names are used in URLs to identify particular Web pages.)
- parts of the URL (protocol such as http; domain name such as www.google.com; directory such as /bence/; filename and extension such as bence.html) [link](http://sagargola.com/wp-content/uploads/2017/02/Understanding-URL-Elements-of-URL-Secure-URL.png)
- endpoint (Communication endpoint, the entity on one end of a transport layer connection)
- HTTP (Hypertext Transfer Protocol; HTTP works as a request-response protocol between a client and server.)
  - Requests
  - Response
  - methods (get, post (head, put, delete, options, connect)) [link](https://www.w3schools.com/tags/ref_httpmethods.asp)
- headers
- body (let's say body in JSON format)
- templates
  
Whenever your web browser fetches a file (a page, a picture, etc) from a web server, it does so using HTTP - that's "Hypertext Transfer Protocol".  HTTP is a request/response protocol, which means your computer sends a request for some file (e.g. "Get me the file 'home.html'"), and the web server sends back a response ("Here's the file", followed by the file itself)

### REST Web backend

- understand what is an API and can use it (if you give me a specification, then i can do it :))
- use JSON objects [link for my own postman](https://ibb.co/c1kEpn)
- understand the concept of serialization (didn't even learn during Green Fox)
- able to use Postman (yes, i can show it as well)

Serilization: (Java provides a mechanism, called object serialization where an object can be represented as a sequence of bytes that includes the object's data as well as information about the object's type and the types of data stored in the object. After a serialized object has been written into a file, it can be read from the file and deserialized that is, the type information and bytes that represent the object and its data can be used to recreate the object in memory.)  
[link](https://www.tutorialspoint.com/java/java_serialization.htm)

## Endpoint tests

- able to make difference between unit test and integration test (yes, i will explain it)
- create endpoint test with the help of a mock server [link](https://github.com/expertneo/corsac-orientation-exam/blob/master/spacetransporter/src/test/java/com/greenfox/spacetransporter/SpacetransporterApplicationTests.java)
     
Unit test: (A unit test is a test written by the programmer to verify that a relatively small piece of code is doing what it is intended to do.)   

Integration test: (An integration test is done to demonstrate that different pieces of the system work together. Integration tests cover whole applications, and they require much more effort to put together. They usually require resources like database instances and hardware to be allocated for them.)
  
  # Final exam requirements ------------------------

## Accomplishments

 -  Significant contribution to the team project (you can judge on that :))
 -  High understanding of project structure (I believe I do understand the project structure)

## Skills

### Common

The student, on their own, is able to:
 -  Use git:
     -  Resolving a simple merge conflict (I resolved the JSLACK implementation conflicts)
     -  Creating a pull request [link to pull requests](https://github.com/greenfox-academy/daily-checkout/pulls)
 -  Understand API documentation (Slack API used and understood more or less) [link to api documentation](https://api.slack.com/)
 -  Understand token based authorization (I am the master of tokens!) [link to the tokens](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/java/com/greenfox/checkout/controllers/SlackController.java)
 -  Refactor code: [link to one of my refactor commit](https://github.com/greenfox-academy/daily-checkout/commit/b397657c182539f8614208cf279f81471e44e5a1)
     -  Create meaningful names for methods, classes and variables (Árnika always made us change varaible names :D)
     -  Split bigger functions to smaller ones (also split functions into smaller ones during the project.)
     -  Separate functionalities to different files (for example, DateUtil service has only datum based functions, CheckoutService has only checkout related functions)
     -  Point out code smells (unused variables, not closed resources, bat patterns)
 -  Understand base concept of hosting [link for my heroku](https://greenfoxcheckoutdev.herokuapp.com/)
 -  Deployment and continuous integration (jenkins + AWS; VSTS + Azure; Heroku)
 -  Using design patterns (for example MVC design Pattern; I am always using it)
 -  Integration testing [link for the tests during project phase](https://github.com/greenfox-academy/daily-checkout/tree/BPappTests/src/test/java/com/greenfox/checkout)
 -  Differentiate between backend and frontend (client) functionality (Please explain this question)


**Choose one from below:**

### Backend ----------- This is what I choose

 -  Use async structures: (I have never heard of this during Green Fox Academy)
     -  Writing functions that are taking and calling callbacks
     -  Determining the calling order in nested callbacks
 -  Authentication: (Google authentication + token based authentication in checkout application)
     -  Handle authentication [google auth](https://github.com/greenfox-academy/daily-checkout/blob/BPappTests/src/main/java/com/greenfox/checkout/configurations/SecurityConfig.java)
     -  Handle token based authorization (Slack uses token based authorization)
 -  Database
     - Using complex data structures (Have two tables, CheckoutTable & TeamCheckoutTable)
     - Understanding and using table connections (no connection in between those tables)
     - Understanding migration (never used migration during the project phase, but as far as I know, filling up the DB during the orientation exam was considered as migration)

Relational database: (A relational database is a collection of data items organized as a set of formally-described tables from which data can be accessed or reassembled in many different ways without having to reorganize the database tables.)

### Fullstack

 -  Use async structures:
     -  Writing functions that are taking and calling callbacks
     -  Determining the calling order in nested callbacks
 -  Understanding and using rich web application framework:
     -  Components, configuration, dependencies, extensions
     -  Handle Authentication

### Mobile

 -  Use async structures:
     -  Writing functions that are taking and calling callbacks
 -  Understanding and using mobile framework:
     -  Components, configuration, dependencies, extensions
 -  Designing multiple screens
 -  Handling authorized communication with backend

### DevOps

 -  Understanding the purpose of Docker containers
 -  Understanding the purpose and mechanism of monitoring tools
 -  AWS
     -  Difference between EC2 and EBS
     -  Purpose of S3

### Frontend

 -  Understanding frontend framework:
     -  Components, configuration, dependencies, extensions, routing
     -  Reusable components and screen parts
 -  Rich DOM manipulation
 -  Handle Authentication
