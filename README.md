# Showcase: Dockerizing Spring Boot Applications

This repository contains two project demonstrating how to dockerize a Spring
Boot application:

- `maven-spring-boot-application` using Maven and producing a docker image
labeled `example/maven-spring-boot-application`
- `gradle-spring-boot-application` using Gradle and producing a docker image
labeled `example/gradle-spring-boot-application`

Also included in this repository is a docker-compose file for easy start and
stop of the produced docker images. The Maven container will run on port
`8080` and the Gradle container on port `8090`

You can see that the service is running inside the container when you `GET`
the `/info` endpoint of each service.
