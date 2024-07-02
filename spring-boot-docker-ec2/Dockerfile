FROM openjdk:11-jre-slim
ADD target/spring-boot-docker-ec2.jar spring-boot-docker-ec2.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "spring-boot-docker-ec2.jar"]