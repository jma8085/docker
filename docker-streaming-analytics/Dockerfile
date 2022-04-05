FROM openjdk:8-jdk-alpine

#configure SpringBoot Application
ADD application/micro.streaming.analytics-0.0.1.jar app.jar
ADD application/micro.streaming.analytics-0.0.1.jar.original app.jar.original  

VOLUME /tmp

ENTRYPOINT ["java","-jar","/app.jar"]
