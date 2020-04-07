FROM openjdk:8
EXPOSE 8080
ADD target/docker_deployment-jar-with-dependencies.jar docker_deployment-jar-with-dependencies.jar 
ENTRYPOINT ["java","-jar","docker_deployment-jar-with-dependencies"]