FROM openjdk:21-jdk


WORKDIR /app


COPY target/appspa-0.0.1-snapshot.jar app.jar


EXPOSE 8081


ENTRYPOINT ["java", "-jar", "app.jar"]
