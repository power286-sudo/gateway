FROM --platform=linux/amd64 eclipse-temurin:17-jdk-alpine
COPY build/libs/inquiry.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
