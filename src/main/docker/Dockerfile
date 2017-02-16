FROM openjdk:8-jre
MAINTAINER ltlamontagne@gmail.com
VOLUME /tmp
ADD spring-boot-admin-0.0.1-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]