# Spring-Boot RestFul + Docker

## Compile
mvn package docker:build

## Push
docker push gallo/spring-rest-service

## Deploy & Run
docker run -p 8080:8080 -t gallo/spring-rest-service
