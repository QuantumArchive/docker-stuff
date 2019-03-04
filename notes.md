# Running Docker on Windows While Primarily Using Ubuntu Shell (Headaches...)

## List Docker CLI commands
```bash
docker
docker container --help
```

## Display Docker version and info
```bash
docker --version
docker version
docker info
```

## Execute Docker image
```bash
docker run hello-world
```
Windows (or the image?) seems to kill this image afterwards since I can't see it using `docker ps`?

## List Docker images
```bash
docker image ls
```

## List Docker containers (running, all, all in quiet mode)
If container is not running, you won't need to see all/quiet mode
```bash
docker container ls
docker container ls --all
docker container ls -aq
```
