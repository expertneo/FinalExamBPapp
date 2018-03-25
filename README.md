# FinalExamBPapp
This repository is to support Bence's final exam at Green Fox Academy.

# Foundation requirements

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
 
 
 # Backend Orientation Exam Competencies

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

- understanding and usage of basic SQL commands
  - `select`, `insert`, `update`, `delete`
- connecting database to backend application
  - database framework configuration
- understanding Object Relational Mapping
  - with using library: JPA/EF Core
- connection between:
  - tables and classes
  - records and objects
  - columns and fields/properties

## Web backend

- domain
- parts of the URL
- endpoint
- HTTP
  - Requests
  - Response
  - methods
- headers
- body
- templates

### REST Web backend

- understand what is an API and can use it
- use JSON objects
- understand the concept of serialization
- able to use Postman

## Endpoint tests

- able to make difference between unit test and integration test
- create endpoint test
  - with the help of a mock server
  
  
  # Final exam requirements

## Accomplishments

 -  Significant contribution to the team project
 -  High understanding of project structure

## Skills

### Common

The student, on their own, is able to:
 -  Use git:
     -  Resolving a simple merge conflict
     -  Creating a pull request
 -  Understand API documentation
 -  Understand token based authorization
 -  Refactor code:
     -  Create meaningful names for methods, classes and variables
     -  Split bigger functions to smaller ones
     -  Separate functionalities to different files
     -  Point out code smells
 -  Understand base concept of hosting
 -  Deployment and continuous integration
 -  Using design patterns
 -  Integration testing
 -  Differentiate between backend and frontend (client) functionality


**Choose one from below:**

### Backend

 -  Use async structures:
     -  Writing functions that are taking and calling callbacks
     -  Determining the calling order in nested callbacks
 -  Authentication:
     -  Handle authentication
     -  Handle token based authorization
 -  Database
     - Using complex data structures
     - Understanding and using table connections
     - Understanding migration 

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
