# base image
FROM openjdk:17-jdk-slim

# set working directory
WORKDIR /app

# copy jar file
COPY target/my-spring-boot-app.jar /app/my-spring-boot-app.jar

# expose port
EXPOSE 8081

# start the app
CMD ["java", "-jar", "/app/spring-boot-server.jar"]
