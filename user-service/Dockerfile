FROM openjdk:11
COPY target/user-service-1.0.jar user-service.jar
ENTRYPOINT ["java", "-jar", "user-service.jar", "-encoding", "utf-8"]