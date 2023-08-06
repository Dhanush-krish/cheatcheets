#### Docker client and server version
```
docker version
```
#### Docker client version
```
docker -v
```
#### Information about the docker service
```
docker info
```
#### Streams logs from docker daemon
```
docker system events
```
#### Pull and run image
```
docker container run <image> <command>
```
#### Interacting with Containers
```
docker container run -it <image> <command> 
```
#### Containers with detach mode - running container in background
```
docker container -d --name <image name> <image> <command>
```
#### List running containers
```
docker ps
```
#### List running and stopped containers
```
docker ps -a
```


## Exposing Apps
#### 80000 is host port and 80 is container port 
```
docker container run -itd -p 80000:80 <image name>
```
#### choose random host port and docker file EXPOSE port in container port
```
docker container run -itd -P <image name>
```

## Container lifecycle
#### create container
```
docker container create -it <image name> <command>
```
#### start one or more container
```
docker container start <image name>
```
#### stop one or more container
```
docker container stop <image name>
```
#### remove one or more container
```
docker container rm <image name>
```


## Debug containers
#### Logs of running application in the container
```
docker logs -f <container id / name>
```
#### Information about the container
```
docker inspect <container id / name>
```
#### Getting Inside the container
```
docker exec -it <container id/name> <shell>
```


## Docker Image
#### History of the image
```
docker image <image id / name>
```

#### Lists all the images
```
docker images
```
#### Remove one or more image
```
docker image rm <name or id>
```

## Docker Volumes
#### List volumes
```
docker volume ls
```

#### Remove all unused local volumes
```
docker volume prune
```

#### Remove one or more volumes
```
docker volume rm
```
#### build and tag image from different file
```
docker build -f api.Dockerfile . -t api:latest
```
