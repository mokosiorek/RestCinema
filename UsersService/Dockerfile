# system bazowy
FROM openjdk:14
EXPOSE 8400
ADD ./target/usersservice.jar usersservice.jar
ENTRYPOINT ["java", "-jar", "usersservice.jar"]