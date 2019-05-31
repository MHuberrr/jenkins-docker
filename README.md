# jenkins-docker

## Building image
```
docker build -t ooober60/jenkins:1.0 . 
```
## Running docker
```
docker run -d -p 8080:8080 --rm --name jenkins ooober60/jenkins:1.0
```
## Useful Docker commands
```
docker images
docker container ls
docker system prune -a
docker stop {container}
```