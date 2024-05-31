FROM openjdk:17-jdk-alpine
EXPOSE 8090
COPY target/kuber-0.0.1-SNAPSHOT.jar kuber.jar
ENTRYPOINT ["java","-jar","kuber.jar"]
