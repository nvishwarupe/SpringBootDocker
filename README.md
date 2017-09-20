# SpringBootDocker
Dockerizing Spring Boot application

mvn clean package

docker build -t livelessons-cloud-docker .

docker run -d -p 8080:8080 --name livelessons-cloud-docker livelessons-cloud-docker

Stopping docker :
Useful commands : docker ps -a
Docker container stop containerId (found by ps -a)


