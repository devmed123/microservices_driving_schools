FROM openjdk:17
VOLUME /tmp
ADD target/gatway-service-0.0.1-SNAPSHOT.jar gatway-service.jar
ENTRYPOINT ["java", "-jar" , "/gatway-service.jar"]
EXPOSE 8085