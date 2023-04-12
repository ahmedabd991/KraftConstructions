# base image
FROM adoptopenjdk/openjdk17:alpine-slim

# set working directory
WORKDIR /app

# copy jar file
COPY target/spring-boot-server.jar /app/spring-boot-server.jar

# expose port
EXPOSE 8081

# start the app
CMD ["java", "-jar", "/app/spring-boot-server.jar"]
