### compose file syntax check
```
docker-compose config 
```

### build  and rebuild services
```
docker compose build
```
###  build services skipping cache -> fresh build
```
docker compose build --no-cache
```
### create and start all services
```
docker compose up
```
### create and start particular container
```
docker compose up <service name>
```
###  updated  compose file
```
docker compose up --force-recreate
```
### stop the container and networks
```
docker compose down
```
### remove volumes attached to the containers
```
docker compose down -v
```
