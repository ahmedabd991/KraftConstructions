# base image
FROM openjdk:17-jdk-slim

# set working directory
WORKDIR /app

# copy jar file
COPY ./spring-boot-server/target/spring-boot-server.jar /app/spring-boot-server.jar

# expose port
EXPOSE 8081

# start the app
CMD ["java", "-jar", "/app/spring-boot-server.jar"]
