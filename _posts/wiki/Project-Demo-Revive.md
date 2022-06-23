---
layout: post
title: "Project Demo"
excerpt: ""
categories: wiki
tags: [ wiki ]

date: 2022-06-23T08:08:50-04:00

---
# Revive

### Problem Statement : 

> To reduce configuration steps and time-taken to deploy a Web Application with Micro-services support from scratch.

### Project Goals :

> To provide a WebApp Initializor with Micro-services similar to Spring Initialitor at start.spring.io. Options to be provided

* Server - Spring Boot

* FrontEnd - ReactJS, AngularJS, VueJS

* Database - PostgreSQL, MySQL, Oracle

* CI/CD - Github Actions, Jenkins, Circle CI, TravisCI

* Cloud Provider - AWS, GCP, MS AZURE

* Container - Docker

	 
### Current Iteration : 
> Why we chose the current stack

* Server - Spring Boot - Runtime Dependency injection + JPA support

* FrontEnd - ReactJS - ComponentBased + Community Support

* Database - PostgreSQL - OpenSource + Community Support

* CI/CD - Github Actions - Collaboration with other + No additional setup 

* Container - Docker -Community Support

* Cloud Provider - AWS - //TODO


### FAQ

> How you set up an API using a framework like Spring Boot

* SpringBoot comes with Runtime dependency injection with the use of Annotation, that reduces the configurations, xml's to be generated and boilerplate code which was a issue with Java projects. @AutoWired annotation provides dependency injection.
* It has embedded server which bootstraps the process for testing new Feature
* @SpringBootApplication provides component scanning for autoconfiguration and property support.
* MVC approach handles
    * Database definition with Model - Model defines a domain model with @Entity annotation which maps objects for DB deinition.
    * Bypasses view-based rendering for Http Response and send the response as JSON
    * Controller - @RestController provides mapping to URI(Universal Resource Indicator) with support for HTTP requests
        * @GetMapping - for GET request
        * @PostMapping - for POST request
        * @PutMapping - for PUT request
        * @DeleteMapping - for Delete request 


> How you do persistence, perhaps even into a postgres database
* Spring-data-jps provides JPARepository and CRUDRepostitory object which handles access to objects from DB.
* Using @AutoWired annotation for the Repository classes in the Controller, HTTP requests can be serviced with DB access.
* @Entity annotation provides DB definition and spring.jpa.hibernate.ddl-auto=update property provides DB Objects like table creation on startup.

> How you use automated unit & integration tests to proof the functionality
* JUnit5 library is used to setup mockup environment to test the use cases.
* TDD approach is used to build new feature. Feature is identified and code is tested against the use cases.
* Jest library is used for ReactJS testing

> Whether you have a CI/CD pipeline, preferably using Github Actions
* Github Action workflow's is used for CI/CD pipeline.
* Used workflow triggers to run the following tasks based on order of execution.
    * BuildSetup - all_branch.yml : runs on each commit, compiles server(SpringBoot) and client(ReactJS) and generates output build
    * IntegrationTest - test_unit_integration.yml - runs's on each commit and dependent on BuildSetup completion. Runs Unit, Integration tests and generates Test Report.
    * DockerBuild - build_docker.yml - creates DockerImages for Server,Client,DB. Depends on IntegrationTest workflow completion. Run on main branch for tag releases and pull request.
    * DockerPush - docker_push.yml - Push docker images to dockerhub and Github Package repository. Depends on DockerBuild workflow completion. Run on main branch and on tag release only.
    * AWSDeploy - deploy_aws.yml - Deploys to AWS on tag releases for main branch. Depends on DockerPush workflow completion.

> A minimalistic frontend app / UI is a clear bonus
* A simple page to display values in the database. Plus button option to ADD/ Edit/ Delete entries.

> An automated deployment into your favorite cloud would be awesome, but really a stretch
* TODO in next version.

> How you present all of this, including problems, challenges, tricks etc.
* Problems faced are logged in Issues tab.
* Tricks - Reusability of components, Refactoring after completion.
* Linux terminal allows for rapid build,test,destroy cycle
* Github CodeSpaces - allows for coding when setup is unavialable.