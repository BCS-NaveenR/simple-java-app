FROM openjdk:8-jdk-alpine
COPY target/my-app-1.0-SNAPSHOT.jar server.jar
EXPOSE 5555
ENTRYPOINT ["java","-jar","/server.jar"]