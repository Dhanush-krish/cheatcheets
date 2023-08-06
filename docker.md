### Docker client and server version
```
docker version
```
### Docker client version
```
docker -v
```
### Information about the docker service
```
docker info
```
### Streams logs from docker daemon
```
docker system events
```
### Pull and run image
```
docker container run <image> <command>
```
### Interacting with Containers
```
docker container run -it <image> <command> 
```
### Containers with detach mode
```
docker container -d <image> <command>
```
### List running containers
```
docker ps
```
### List running and stopped containers
```
docker ps -a
```
### Lists all the images
```
docker images
```
### Remove one or more image
```
docker image rm <name or id>
```
### List volumes
```
docker volume ls
```

### Remove all unused local volumes
```
docker volume prune
```

### Remove one or more volumes
```
docker volume rm
```
### build and tag image from different file
```
docker build -f api.Dockerfile . -t api:latest
```
