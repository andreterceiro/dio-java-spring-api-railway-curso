# General

[Link](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/138c435a-5be5-450b-a292-cf6ea002f54c?back=/play) of the challenge.


# Generating the boilerplate

We generated the boilerplate in the [http://start.spring.io](http://start.spring.io) again. I tried to use the configurations more next to the teacher. These was the configurations that I selected:

![Configurations in Spring Initializr](images/configurations-in-spring-initializr.png)

I tried to make the same configuration as the teacher, used `Java 17`, but the Spring Boot version had to be newer because the course was recorded last year.

I had to change the port of the application because I already had an application running in the por 8080. I changed adding a file `application.properties` in the root directory with this content:

```
server.port = 8081
```

I renamed the main class as instructed by the teacher to `Application.java` (in src/main/java/dio/), had some changes in this file to reflect this new name and runned the appplication clicking with the left button over the class `Application.java` and selecting "`Run as > Java Application`".
