# system bazowy
FROM openjdk:14
EXPOSE 8080
ADD ./target/authservice.jar authservice.jar
ENTRYPOINT ["java", "-jar", "authservice.jar"]