FROM openjdk:11
COPY target/catalog-service-0.0.1-SNAPSHOT.jar catalog-service.jar
ENTRYPOINT ["java", "-jar", "catalog-service.jar", "-encoding", "utf-8"]