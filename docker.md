### Docker version
```
docker version
```
### Information about the docker service
```
docker info
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
