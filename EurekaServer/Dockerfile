FROM maven:3.6.2-jdk-8
ADD /target/Eureka-Server-0.0.1-SNAPSHOT.jar Eureka-Server-0.0.1-SNAPSHOT.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "Eureka-Server-0.0.1-SNAPSHOT.jar"]