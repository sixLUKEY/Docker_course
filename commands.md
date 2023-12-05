## Some Docker commands

```

docker version

docker run *insert details here*  //runs container

docker run -d *insert details here*  //runs container in background

docker run *name*:*version*  //runs specific version of container

docker run -i *name*  //runs container with interactivity allowed

docker run -it *name*  //runs container in interactive terminal

docker run -p *port number here* *name*  //runs container on specified port

docker ps  //lists running containers

docker ps -a  //lists all containers

docker rm *insert container name or ID*  //removes container

docker rmi *insert image name here*  //removes image

docker pull *insert image name here*  //locally installs an image without auto running container

docker exec *insert container ID here* *insert command here*

docker inspect *name*  //inspect contents of container in JSON

docker logs *name*  //shows container logs

```
