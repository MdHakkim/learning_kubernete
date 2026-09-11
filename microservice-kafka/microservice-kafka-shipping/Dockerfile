FROM openjdk:18.0.2.1-slim

WORKDIR /app

COPY target/microservice-kafka-shipping-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-Xmx400m", "-Xms400m", "-XX:TieredStopAtLevel=1", "-jar", "app.jar"]
