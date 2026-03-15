FROM --platform=linux/amd64 eclipse-temurin:21-jdk-jammy


WORKDIR /app

COPY ./demo-0.0.1-SNAPSHOT.jar ./myapp.jar

EXPOSE 8080

CMD ["java", "-jar", "myapp.jar"]