# h2-docker

## how to start

```bash
$ docker-compose up -d --build
```

## how to stop
```bash
$ docker-compose down
```

## check
```bash
$ docker ps
CONTAINER ID   IMAGE                   COMMAND                  CREATED              STATUS          PORTS                                        NAMES
f74afe2f8d3c   oscarfonts/h2:2.0.204   "/bin/sh -c 'java -c…"   About a minute ago   Up 59 seconds   0.0.0.0:81->81/tcp, 0.0.0.0:1521->1521/tcp   h2
```
