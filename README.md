# Multi Container App

This project is setup to demo a multi conatiner app end to end. It is using docker-compose, Travis CI and AWS beanstalk.

The intention is to experiment with docker, the build pipelines and how to deploy to AWS using Travic CI. 

## Project Structure

### Client: 
This folder contains a demo react app that acts as user interface. It will be hosted in a nginx container.

### Nginx:
This folder contains config for routing to backend api and client app. It is again hosted on a nginx container

### Server:
This is Nodejs api that supports actions from UI. It connects to Postgres db container and the redis cache container.

### Worker:
This is backedn nodeJs worker process. It listens to messages posted on redis cache and performs certain calculations. It is hosted on NodeJs container.

## Instructions:
To follow.





