## Feathers CRUD example with mongodb


## Docker 

```
docker pull mongo:latest

docker volume create feathers_data

docker run -p 27017:27017 -v feathers_data:/data/db -d mongo
```