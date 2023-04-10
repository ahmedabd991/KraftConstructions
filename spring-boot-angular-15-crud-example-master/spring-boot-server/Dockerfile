# base image
FROM openjdk:11-jre-slim

# set working directory
WORKDIR /app

# copy jar file
COPY target/spring-boot-server.jar /app/spring-boot-server.jar

# expose port
EXPOSE 8081

# start the app
CMD ["java", "-jar", "/app/spring-boot-server.jar"]
