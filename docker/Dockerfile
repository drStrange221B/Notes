#Start with base image containing Java Runtime
FROM eclipse-temurin:17-jdk-jammy as build

#Information around who maintains the image
MAINTAINER emrys.com

#Working Directory
WORKDIR /app


COPY build/libs/demo-0.0.1-SNAPSHOT.jar ./

#Execute the application
ENTRYPOINT ["java","-jar", "demo-0.0.1-SNAPSHOT.jar"]
