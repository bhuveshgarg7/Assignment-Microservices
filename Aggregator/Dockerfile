FROM openjdk:8u212-jdk-slim

VOLUME /tmp

COPY target/*.jar Aggregator-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/Aggregator-0.0.1-SNAPSHOT.jar"]

EXPOSE 8002