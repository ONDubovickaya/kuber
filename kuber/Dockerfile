FROM openjdk:17-jdk-alpine
EXPOSE 8090
LABEL org.opencontainers.image.source="https://github.com/ONDubovickaya/kuber"
COPY target/kuber-0.0.1-SNAPSHOT.jar kuber.jar
ENTRYPOINT ["java","-jar","kuber.jar"]
