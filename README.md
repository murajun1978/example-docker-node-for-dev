# Example Node.js with Docker for Dev
> Node.js + Postgresql

## Get started

Install Docker and Docker compose

Docker: https://docs.docker.com/install/

Docker compose: https://docs.docker.com/compose/install/

Run containers:

```
$ docker-compose up
```

Run shell with container:

```
$ docker-compose run --rm runner
```

In container:

```
/home/app $ node -v
v12.9.0
```
