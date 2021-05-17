FROM maven:3.6.2-jdk-8
ADD /target/ZuulServer-0.0.1-SNAPSHOT.jar ZuulServer-0.0.1-SNAPSHOT.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "ZuulServer-0.0.1-SNAPSHOT.jar"]