# Docker w/ Python 3.7-slim 

<img src="https://andykdocs.de/development/Docker/Getting+Started/files/assets/Docker.svg"></img>


### Utils Flask and Redis

#### Build to images
```
docker build -t python-docker .
```

#### runnig images set port
```
docker run -d -p 4000:80 python-docker:v1
```
#### image on hub.docker.com

```
docker pull williamkoller/python-docker:latest
```
