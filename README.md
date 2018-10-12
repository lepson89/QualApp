# Qualification App

Application for testing ActiveMQ. Main goals:
- Send request to queue
- Receive request from queue and send to another queue
- When receive, consumeRequest by proper Service (reject, save to file, save to DB, log out)

After download repo, please run `mvn clean install` command on directory level where pom.xml file is store. 

App contains SpockTest under _src/main/test/groovy_
for testing application main goals. 

###Used technologies

-   Spring Boot
-   Spring Data JPA
-   ActiveMQ
-   H2 Database
-   Lombok
-   Spock Framework
-   Maven for build and managment

 