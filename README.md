# DockerCentral
A central dev stack with services that can be used by multiple applications.

# Installation

#### Setup an internal Docker network
Before you can start DockerCentral, you need to create an internal Docker network. This can be done by running the following command:

```
docker network create docker-central-gateway
```

#### Start DockerCentral
Now we have installed the Docker network, we can start DockerCentral by entering the following command:


```
docker-compose up --build --detach
```
