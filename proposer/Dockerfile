FROM openjdk:8
WORKDIR /home
ADD target/proposer-0.0.1-SNAPSHOT-jar-with-dependencies.jar .
ADD src/main/resources/hosts.json .
CMD ["java", "-jar", "proposer-0.0.1-SNAPSHOT-jar-with-dependencies.jar"]
