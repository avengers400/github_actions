FROM adoptopenjdk/openjdk11:alpine-jre
ARG JAR_FILE=target/gs-maven-0.1.0.jar
COPY ${JAR_FILE} spring-boot-web.jar
ENTRYPOINT ["java", "-jar", "spring-boot-web.jar"]
