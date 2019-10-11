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

# realtime-chat

> 

## About

This project uses [Feathers](http://feathersjs.com). An open source web framework for building modern real-time applications.

## Getting Started

Getting up and running is as easy as 1, 2, 3.

1. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
2. Install your dependencies

    ```
    cd path/to/realtime-chat
    npm install
    ```

3. Start your app

    ```
    npm start
    ```

## Testing

Simply run `npm test` and all your tests in the `test/` directory will be run.

## Scaffolding

Feathers has a powerful command line interface. Here are a few things it can do:

```
$ npm install -g @feathersjs/cli          # Install Feathers CLI

$ feathers generate service               # Generate a new Service
$ feathers generate hook                  # Generate a new Hook
$ feathers help                           # Show all commands
```

## Help

For more information on all the things you can do with Feathers visit [docs.feathersjs.com](http://docs.feathersjs.com).
