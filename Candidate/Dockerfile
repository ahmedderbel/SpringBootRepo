FROM java:8
EXPOSE 8080
ADD /target/Candidate-0.0.1-SNAPSHOT.jar condidate-test-docker.jar
ENTRYPOINT ["java", "-jar" , "condidate-test-docker.jar"]