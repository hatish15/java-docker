FROM maven:3.8-jdk-11
RUN mkdir /project
COPY demo/ /project
WORKDIR /project
RUN gradle build
CMD ["java", "-jar", "/build/libs/demo-0.0.1-SNAPSHOT.jar"]
