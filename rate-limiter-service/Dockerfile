FROM eclipse-temurin:21-jdk-jammy

WORKDIR /app

COPY target/rate-limiter-service-0.0.1-SNAPSHOT.jar rate-limiter-service.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "rate-limiter-service.jar"]