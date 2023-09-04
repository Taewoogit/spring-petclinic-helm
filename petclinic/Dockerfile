FROM openjdk:18-jdk-alpine

ADD target/spring-petclinic-3.0.0-SNAPSHOT.jar /spring-petclinic-3.0.0-SNAPSHOT.jar

CMD ["java", "-jar", "-Dspring.profiles.active=mysql", "/spring-petclinic-3.0.0-SNAPSHOT.jar"]
