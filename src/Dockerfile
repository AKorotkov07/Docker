FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD build/libs/<название вашего архива>.jar myapp.jar
ENTRYPOINT ["java","-jar","/myapp.jar"]