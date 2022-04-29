FROM maven:3.8-jdk-11
RUN mkdir /project
COPY demo/ /project
WORKDIR /project
RUN mvn clean package -DskipTests
CMD ["java", "-jar", "/project/target/demo-0.0.1-SNAPSHOT.jar"]
