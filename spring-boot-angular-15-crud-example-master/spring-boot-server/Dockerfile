# base image
FROM openjdk:17-jdk-slim

# set working directory
WORKDIR /app

# copy jar file
COPY COPY my-spring-boot-app-0.0.1-SNAPSHOT.jar /app/my-spring-boot-app.jar

# expose port
EXPOSE 8081

# start the app
CMD ["java", "-jar", "/app/spring-boot-server.jar"]
