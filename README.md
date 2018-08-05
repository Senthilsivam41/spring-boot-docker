# spring-boot-docker

Spring Boot Application Demo to deploy the application as Docker image

Once the Spring Boot Application is build run the following command

docker build -f docker-file -t docker-boot-demo .
docker images
docker run -p 8085:8085 docker-boot-demo


