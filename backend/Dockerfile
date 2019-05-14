FROM openjdk:8-alpine
ADD backend*.jar backend.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/backend.jar"]