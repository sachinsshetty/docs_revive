---
layout: post
title: "Sprint Tasks"
excerpt: "Step by Step info to help in migration"
categories: wiki
tags: [ wiki ]

date: 2022-06-26T08:08:50-04:00

---


# Sprint Logs 

* Sprint 6
# Retrofit HTTP library
 * https://github.com/eugenp/tutorials/tree/master/libraries-http
 * https://www.baeldung.com/retrofit

# okta Auth
 * https://developer.okta.com/blog/2017/10/27/secure-spa-spring-boot-oauth#get-your-oauth-info-ready
 * https://developer.okta.com/blog/2018/03/21/dropwizard-oauth
 * https://github.com/na703/DropwizardRethinkDB/blob/master/pom.xml


* Sprint 5 

# JetBrains - IntelliJ Plugin
 * Create Repo from Template - https://github.com/JetBrains/intellij-platform-plugin-template
 * Sign the Plugin - https://plugins.jetbrains.com/docs/intellij/plugin-signing.html
 * Upload to Marketplace - 
   * https://plugins.jetbrains.com/docs/intellij/update-plugins-format.html#optional-updatepluginxml-elements
   * https://account.jetbrains.com/licenses
   * 
 * tutorial video - https://www.youtube.com/watch?v=vAlor5-hC0Q


* Sprint 4

# version 8
* Gradle Dropwizard
  * https://karollotkowski.wordpress.com/2015/10/13/run-dropwizard-with-gradle/
  * https://github.com/dropwizard/dropwizard/tree/master/dropwizard-example

  * To Test - HelloWorldApplication.java
    * http://localhost:8080/hello-world?name=Successful+Dropwizard+User
    * To Get metric
      * http://localhost:8081/metrics
  * Dropwizard Manual
    * https://www.dropwizard.io/en/latest/manual/configuration.html

  * ./gradlew build --refresh-dependencies
  * https://jdbc.postgresql.org/documentation/head/connect.html  _ set property- Intergration test

# version 7
* Composite Github Actions
  * https://docs.github.com/en/actions/using-workflows/about-workflows

  * https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions

  * https://docs.github.com/en/actions/using-workflows/reusing-workflows

  * https://github.blog/2022-02-10-using-reusable-workflows-github-actions/


* Example -
  * https://wallis.dev/blog/composite-github-actions

  * https://betterprogramming.pub/streamline-your-github-actions-with-composite-actions-a8ebc6d28f6b
  
* Deploy to Azure
  * https://docs.microsoft.com/en-us/azure/app-service/deploy-github-actions?tabs=applevel
  * node.js - https://docs.microsoft.com/en-us/azure/app-service/quickstart-nodejs
  * java - https://docs.microsoft.com/en-us/azure/app-service/quickstart-python
  * https://github.com/Azure/actions-workflow-samples
  * https://github.com/Azure/actions

* Buildkit  -
* https://medium.com/titansoft-engineering/docker-build-cache-sharing-on-multi-hosts-with-buildkit-and-buildx-eb8f7005918e
# version 6

* Publish multiple dockers from mono repo
  * https://github.com/marketplace/actions/publish-docker
* Dropwizard Demo
  * maven - https://howtodoinjava.com/dropwizard/tutorial-and-hello-world-example/
  * https://www.dropwizard.io/en/latest/getting-started.html
  * https://levelup.gitconnected.com/create-an-app-with-dropwizard-maven-and-kotlin-24a6277b946c
  * gradle
    * https://automationrhapsody.com/build-dropwizard-project-gradle/
    * https://github.com/ireardon/dropwizard-example-gradle
    * https://www.anuragkapur.com/blog/programming/java/2017/06/21/gradle-dropwizard-uber-jar.html

* docker compoase AWS - https://aws.amazon.com/blogs/containers/deploy-applications-on-amazon-ecs-using-docker-compose/

* https://aws.amazon.com/blogs/containers/automated-software-delivery-using-docker-compose-and-amazon-ecs/

* https://docs.docker.com/cloud/ecs-integration/

* docker- local to AWS
 - https://www.docker.com/blog/docker-compose-from-local-to-amazon-ecs/


* Sprint 3

* Install Docker CLI 

curl -L https://raw.githubusercontent.com/docker/compose-cli/main/scripts/install/install_linux.sh | sh

* AWS DEploy
* https://docs.github.com/en/actions/deployment/deploying-to-your-cloud-provider/deploying-to-amazon-elastic-container-service
* https://github.com/actions/starter-workflows/blob/main/deployments/aws.yml
* https://github.com/aws-actions/amazon-ecs-render-task-definition
* https://github.com/aws-actions/amazon-ecs-deploy-task-definition
* https://aws.plainenglish.io/build-a-docker-image-and-publish-it-to-aws-ecr-using-github-actions-f20accd774c3 

AWS IAM - https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html

https://github.com/aws-actions/configure-aws-credentials


# Version 5 

* Unit Test
    * https://www.baeldung.com/jpa-default-column-values

SpringBoot TDD -
https://tanzu.vmware.com/content/springone-platform-2017/test-driven-development-with-spring-boot-sannidhi-jalukar-madhura-bhave



* Github Actions Runner
    * https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows


* Push multiple dockerfiles to docker Hub
https://github.com/docker/build-push-action/issues/561

    * https://stackoverflow.com/questions/62750603/github-actions-trigger-another-action-after-one-action-is-completed


* Add your Docker ID as a secret to GitHub. Navigate to your GitHub repository and click Settings > Secrets > New secret.
* Create a new secret with the name DOCKER_HUB_USERNAME and your Docker ID as value.
* Create a new Personal Access Token (PAT). To create a new token, go to Docker Hub Settings and then click New Access Token.
* Enter value as project-name ****

* setup secrets : https://docs.docker.com/ci-cd/github-actions/
* Docker CI/CD Best Practice : https://www.docker.com/blog/best-practices-for-using-docker-hub-for-ci-cd/
* https://tutorials.releaseworksacademy.com/learn/building-your-first-docker-image-with-jenkins-2-guide-for-developers
* https://github.com/marketplace/actions/build-and-push-docker-images
* https://docs.docker.com/ci-cd/github-actions/
* https://www.prestonlamb.com/blog/creating-a-docker-image-with-github-actions

* READ These
    * https://docs.github.com/en/actions/security-guides/automatic-token-authentication
    * https://github.com/docker/build-push-action/tree/master/docs/advanced
    * https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry
    *





# Version 4

|No. | Step | Status | Date |
|---|---|---|---|
|1.| JRE Size Reduction/Custom JRE | Done  | 27-May-22 |
|2.| Split WebApp : Front End + Back End | WIP  | 27-May-22 |


* VSCode Setup + codespace

* Install OpenJDK17 -  https://adoptium.net/temurin/releases/?version=17

* Make builds for
    * 0.1 - Core Java + PostgreSQL
    * 0.2 - SpringBoot + Hibernate JPA
    * 0.3 - UT with Thymeleaf + v0.2
    * 0.4 - ReactJS frontend integration


* Create custom jre17 docker - https://levelup.gitconnected.com/java-developing-smaller-docker-images-with-jdeps-and-jlink-d4278718c550
    * https://dzone.com/articles/dockerizing-with-a-custom-jre
    * https://blog.adoptium.net/2021/08/using-jlink-in-dockerfiles/
    * https://github.com/fedeoliv/java-custom-jre
    * https://blog.adoptium.net/2021/10/jlink-to-produce-own-runtime/
    *  https://shekhargulati.com/2019/01/13/running-tests-and-building-react-applications-with-gradle-build-tool/
   * Jlink - fix objcopy : https://medium.com/@david.delabassee/jlink-stripping-out-native-and-java-debug-information-507e7b587dd7

* ReactJS + SpringBoot Split
    * https://www.callicoder.com/spring-boot-mysql-react-docker-compose-example/
    * material UI - https://medium.com/geekculture/a-reactjs-web-application-with-a-spring-boot-backend-and-containerizing-it-using-docker-3eeaed8cb45a
    * multi-stage docker - https://blog.obeosoft.com/multi-stage-docker-build-for-react-and-spring

* nodejs docker
    * https://github.com/nodejs/docker-node/blob/main/README.md#how-to-use-this-image
    * https://hub.docker.com/_/node
    * http://nginx.org/
    * https://tiangolo.medium.com/react-in-docker-with-nginx-built-with-multi-stage-docker-builds-including-testing-8cc49d6ec305
    * https://medium.com/bb-tutorials-and-thoughts/how-to-serve-react-application-with-nginx-and-docker-9c51ac2c50ba
    * https://dev.to/bahachammakhi/dockerizing-a-react-app-with-nginx-using-multi-stage-builds-1nfm


* Spring Rest API 
    * https://hevodata.com/learn/spring-boot-rest-api/,



# Version 3

|No. | Step | Status | Date |
|---|---|---|---|
|1.| UI | WIP  | 25-May-22 |
|2.| Github actions | Done | 23-May-22|
|3.| Readme status links | Done | 23-May-22 |
|4.| Integrate ReactJS Front-end | Done | 24-May-22 |
|5.| Integrate Oauth | -- | --|
|6.| docker compose for AWS |-- | -- |
|7.| Gradle pack  Reach + SpringBoot | WIP | 25-5-22 |


Source for steps
* Github Actions - 
  * https://tomgregory.com/build-gradle-projects-with-github-actions/

* Micro Service -  
  * https://dzone.com/articles/build-and-package-a-microservices-architecture-wit

* ReactJS -
  * https://spring.io/guides/tutorials/react-and-spring-data-rest/
  * https://github.com/eugenp/tutorials/tree/master/spring-boot-modules/spring-boot-react

* MongoDB - 
  * Spring - https://spring.io/guides/gs/accessing-mongodb-data-rest/

* Oauth - Oktta -
  * https://developer.okta.com/docs/guides/sign-into-web-app-redirect/spring-boot/main/#redirect-to-the-sign-in-page
  * https://github.com/okta/samples-java-spring/tree/master/okta-hosted-login
  * oauth .- https://www.baeldung.com/spring-security-oauth

* Spring Live reload - 
  * https://www.codejava.net/frameworks/spring-boot/spring-boot-auto-reload-changes-using-livereload-and-devtools

Init DB ;
* custom sequence
  * https://thorben-janssen.com/hibernate-tips-use-custom-sequence/
* https://www.baeldung.com/spring-boot-data-sql-and-schema-sql
* https://docs.spring.io/spring-boot/docs/current/reference/html/howto.html#howto.data-initialization.using-basic-sql-scripts
* https://www.baeldung.com/hibernate-identifiers
* https://github.com/eugenp/tutorials/tree/master/persistence-modules/spring-boot-persistence

* Gradle split
* https://www.petrikainulainen.net/programming/gradle/getting-started-with-gradle-creating-a-multi-project-build/


* Integrating Gradle + Spring Boot + React 
	* https://github.com/node-gradle/gradle-node-plugin/blob/master/docs/usage.md
	* https://github.com/rewolf/blog-spring-and-react-1-setup/tree/master/src/main/webapp/javascript
	* https://andrew-flower.com/blog/Spring-Boot-and-React-1



Sprint 2

# Version 2

|No. | Step | Status | Date |
|--|--|--|--|
|1.| Connect to Postgres JDBC| Done | 18-May-22 |
|2.| Connect Postgres with  Hibernate | Done | 18-May-22| 
|3.| Update to SpringMVC | Done | 19-May-22|
|4.| Hibernate Map Object | Done | 20-May-22|
|5.| Simple UI - Display All Table Info | Done | 24-May-22 |
|7 | Exception Handling |Done |21-5-22| 
|8 |Setup Docker - SpringBoot + PostgreSQL|Done |22-MAy-25 | 


Source for steps

* sprint boot bootstrap
	* https://github.com/eugenp/tutorials/tree/master/spring-boot-modules/spring-boot-bootstrap
	* https://www.baeldung.com/spring-boot-start
	* https://spring.io/guides/gs/convert-jar-to-war/
	* SpringBoot Gradle - https://docs.spring.io/spring-boot/docs/2.6.7/gradle-plugin/reference/htmlsingle/
	* baeldung - https://github.com/eugenp/tutorials/tree/master/spring-boot-modules/

* Test Case Setup
	* https://github.com/eugenp/tutorials/blob/master/spring-boot-modules/spring-boot-bootstrap/src/test/java/com/baeldung/SpringBootBootstrapLiveTest.java	

* Exception handling

	* https://github.com/eugenp/tutorials/blob/master/spring-boot-modules/spring-boot-bootstrap/src/main/java/com/baeldung/web/exception/BookIdMismatchException.java
	https://www.baeldung.com/spring-5-junit-config



Sprint 1

* Junit - 
	* https://www.baeldung.com/junit-5-gradle
* postgres

	* ubuntu - https://www.tecmint.com/install-postgresql-and-pgadmin-in-ubuntu/

	* create database avti;
	* grant all privileges on database avti to postgres;
	* https://www.postgresqltutorial.com/postgresql-jdbc/connecting-to-postgresql-database/
	* https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/
	* https://www.postgresqltutorial.com/postgresql-getting-started/connect-to-postgresql-database/
	* https://thorben-janssen.com/hibernate-postgresql-5-things-need-know/
	* https://stackabuse.com/implementing-hibernate-with-spring-boot-and-postgresql/
	* ubuntu - https://www.pgadmin.org/download/pgadmin-4-apt/
 create database avti_db;
	* grant all privileges on database avti_db to avti_db;
	* Access PSQL
		* psql -d postgres -U postgres 
	* https://www.enterprisedb.com/postgres-tutorials/connecting-postgresql-using-psql-and-pgadmin
* Docker
	* https://www.baeldung.com/spring-boot-postgresql-docker
	* docker reduce . https://medium.com/@ievgen.degtiarenko/reduce-size-of-docker-image-with-spring-boot-application-2b3632263350
	* recuing jre sizw - https://www.baeldung.com/jlink
	* https://hub.docker.com/r/bellsoft/liberica-openjdk-alpine

* Spring JPA
	* Hibernate Mapping - https://thorben-janssen.com/ultimate-guide-association-mappings-jpa-hibernate/
	* https://thorben-janssen.com/entity-mappings-introduction-jpa-fetchtypes/
	* https://www.baeldung.com/hibernate-query-to-custom-class

* Spring MVC
	* https://www.learn-it-with-examples.com/development/java/thymeleaf/display-database-table-java-thymeleaf.html
	* https://www.codementor.io/@olebueziobinnadavid/setting-up-and-displaying-a-list-of-objects-in-a-table-thymeleaf-1cifoviz5e
	* https://bushansirgur.in/spring-boot-thymeleaf-display-list-of-records-from-database/
	https://spring.io/guides/gs/serving-web-content/
	* https://frontbackend.com/thymeleaf/spring-boot-bootstrap-thymeleaf-datatable
	* https://github.com/ro6ley/java-hibernate-example
	* https://spring.io/guides/gs/consuming-rest/
	* https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mvc.html
	* Spring MVC - https://www.baeldung.com/spring-mvc-tutorial
	

* Docker
* https://github.com/docker-library/postgres/blob/4e56664f1797ba4cc0f5917b6d794792a5571b45/14/alpine/Dockerfile
* https://github.com/docker-library/docs/blob/master/postgres/README.md
* https://hub.docker.com/_/postgres
* https://snapshooter.com/learn/postgresql/deploy-postgres-with-docker
* https://hub.docker.com/r/cafapi/java-postgres
* https://www.baeldung.com/spring-boot-postgresql-docker
* https://hub.docker.com/_/openjdk






### Day 1

# Version 1

|No. | Step | Status | Date |
|--|--|--|--|
|1.| Run main class from Server.java eclipse control panel| Done | 18-May-22 |
|2.| Generate artifacts for deployment | Done| 18-May-22|
|3.| Create Test Suite|Done|20-May-22|
|4.| Run from apache-tomcat/spring boot | Done |21-5-22|
|5.| Create github action to build | Done | 18-May-22|


Source for steps
* https://www.jetbrains.com/help/space/publish-artifacts-from-a-gradle-project.html
* https://www.vogella.com/tutorials/EclipseGradle/article.html
* createing fat jar or uber-jar :  https://www.baeldung.com/gradle-fat-jar
* shadowJar - https://imperceptiblethoughts.com/shadow/publishing/#publishing-with-maven-publish-plugin
* Conversion Steps
	* Add build.gradle file in root project directory
	* Add configurations
	* Close the project in Eclipse and Re.import as Gradle Project
	* In Gradle Tasks menu bar, run "gradle init"
* Installing gradle in linux - Ubuntu : https://linuxize.com/post/how-to-install-gradle-on-ubuntu-18-04/ :: install version 6.8 
* In terminal run "gradle build"
* java -jar build/libs/reviveJar-1.0-SNAPSHOT.jar
* Setup Gradle with github action :  https://tomgregory.com/build-gradle-projects-with-github-actions/
