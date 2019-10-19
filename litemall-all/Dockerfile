
FROM openjdk:8-jdk-alpine
MAINTAINER Aleksandar Nikolikj
COPY target/litemall-all-*-exec.jar /litemall-all-exec.jar
ENTRYPOINT ["java","-jar","-Dfile.encoding=UTF-8","/litemall-all-exec.jar"]
