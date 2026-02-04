# Use OpenJDK base image
FROM eclipse-temurin:21-jdk   


WORKDIR /app

COPY target/java-app-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]