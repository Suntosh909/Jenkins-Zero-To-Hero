# Updated base image - adoptopenjdk is deprecated, use eclipse-temurin instead
FROM eclipse-temurin:17-jre-alpine

ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT ["java","-jar","app.jar"]
