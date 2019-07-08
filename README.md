# Docker Images

# Installation

To build docker files and run the docker images install docker from here: https://docs.docker.com/install/

# 1. Redis Image

This is a simple docker file which runs redis-server.
You can directly run the command:

```
docker run akashmarwah007/redis
```

or you can go to the redis folder and run:

```
docker build .
```

on the terminal and copy the id generated and run the command:

```
docker run <ID>
```

# 2. Node Simple Server Image

    This is a simple docker file which runs node-server.
            You can directly run the command:
        ```
        docker run -p 8080:8080 akashmarwah007/simplenodeapp
        ```
        or you can go to the simplenodeapp folder and run:
        ```
        docker build .
        ```
        on the terminal and copy the id generated and run the command:
        ```
        docker run -p 8080:8080 <ID>
        ```
    After above steps go to: localhost:8080 on your browser.
