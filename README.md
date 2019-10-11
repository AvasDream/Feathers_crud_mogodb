## Feathers CRUD example with mongodb

Simple example an code skeletton to implement CRUD with feathers and mongodb.

## Docker 

```
docker pull mongo:latest

docker volume create feathers_data

docker run -p 27017:27017 -v feathers_data:/data/db -d mongo
```


## ToDo 

* Connect Feathers and DB
* Integrate React in Feathers
* Create simple frontend to create Projects
* Create
* Read
* Update
* Delete