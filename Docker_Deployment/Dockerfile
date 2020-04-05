FROM openjdk:8
EXPOSE 8080
ADD target/docker_deployment.jar docker_deployment.jar 
ENTRYPOINT ["java","-jar","docker_deployment.jar"]