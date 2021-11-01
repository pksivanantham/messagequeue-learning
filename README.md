# messagequeue-learning
Message Queue Learning

Download latest docker images from https://registry.hub.docker.com/_/rabbitmq/
```
  docker pull rabbitmq  
```
Start the docker

```
docker run -it --rm --hostname my-rabbit --name my-rabbit -p 5672:5672 -p 15672:15672 rabbitmq:latest

```
