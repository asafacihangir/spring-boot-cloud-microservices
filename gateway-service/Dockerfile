FROM openjdk:8
COPY /target/gateway-service.jar gateway-service.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","gateway-service.jar"]