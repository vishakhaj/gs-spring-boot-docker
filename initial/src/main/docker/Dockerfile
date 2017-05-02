FROM frolvlad/alpine-oraclejdk8:slim
MAINTAINER Vishakha Jangida
ADD gs-spring-boot-docker-0.1.0.jar app.jar
EXPOSE 8080
ENTRYPOINT ["sh", "-c", "java -jar /app.jar" ]