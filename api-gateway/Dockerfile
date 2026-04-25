FROM eclipse-temurin:21-jdk-jammy

WORKDIR /app

COPY target/api-gateway-0.0.1-SNAPSHOT.jar api-gateway.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "api-gateway.jar"]