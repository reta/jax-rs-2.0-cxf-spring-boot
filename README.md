Apache CXF and Spring Boot
==============

- Build

         mvn package
         
- Run using Spring Boot Maven plugin

         mvn spring-boot:run
         
- Run using standalone JAR

         java -jar target/jax-rs-2.0-cxf-spring-boot-0.0.1-SNAPSHOT.jar         

- Invoke People REST service  

        curl http://localhost:8080/api/people