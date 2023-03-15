FROM openjdk:11
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=target/demo-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} target/demo-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/target/demo-0.0.1-SNAPSHOT.jar"]
# ----------------------