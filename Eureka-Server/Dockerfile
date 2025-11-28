FROM eclipse-temurin:17-jre-focal
ARG JAR_FILE=target/Eureka-Server-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} servidor_eureka.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "servidor_eureka.jar"]
