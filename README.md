# Orientation
```commandline
docker run hello-world

docker image ls

docker container ls -aq
```

# Containers
```commandline
docker build -t friendlyhello .
docker run -dp 4000:80 friendlyhello
docker container ls -a

docker container stop $(docker container ls -aq)
docker container prune

docker image rm $(docker image ls -aq)

docker login
docker tag <image> username/repository:tag
docker push username/repository:tag
docker run username/repository:tag
```
