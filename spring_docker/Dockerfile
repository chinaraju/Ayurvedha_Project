FROM openjdk:17

COPY target/spring_docker-0.0.1-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

ENTRYPOINT [ "java","-jar","spring_docker-0.0.1-SNAPSHOT.jar" ]