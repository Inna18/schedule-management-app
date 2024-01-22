FROM openjdk:11

ENTRYPOINT ["sudo", "mkdir", "/app/"]

WORKDIR app

COPY /build/libs/schedule-management-rest-0.0.1-SNAPSHOT.jar /app

EXPOSE 9010

ENTRYPOINT ["java", "-jar", "/app/schedule-management-rest-0.0.1-SNAPSHOT.jar"]