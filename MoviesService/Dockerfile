# system bazowy
FROM openjdk:14
EXPOSE 8300
ADD ./target/moviessservice.jar moviessservice.jar
ENTRYPOINT ["java", "-jar", "moviessservice.jar"]