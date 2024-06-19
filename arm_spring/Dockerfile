#Dockerfile arm

FROM arm64v8/openjdk:19
ARG JAR_FILE=sbb-0.0.8-SNAPSHOT.jar
COPY ${JAR_FILE} /sbb-0.0.8-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "./sbb-0.0.8-SNAPSHOT.jar"]

