### build  and rebuild services
```
docker compose build
```
###  build services skipping cache -> fresh build
```
docker compose build --no-cache
```
### create and start containers
```
docker compose up
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
