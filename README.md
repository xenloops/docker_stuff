# Docker commands

## Management Commands
  
Launch the Docker daemon

```docker dockerd```

Display system-wide information

```docker info```

Return low-level information on a container or image

```docker inspect```

Show the Docker version information

```docker version```


## Image Commands

Build an image from a Dockerfile

```docker build```

Create a new image from a container’s changes

```docker commit```

Show the history of an image

```docker history```

List images

```docker images```

Import the contents from a tarball to create a filesystem image

```docker import```

Load an image from a tar archive or STDIN

```docker load```

Remove one or more images

```docker rmi```

Save images to a tar archive

```docker save```

Tag an image into a repository

```docker tag```
  
## Container Commands

Attach to a running container

```docker attach```

Copy files/folders from a container to a HOSTDIR or to STDOUT

```docker cp```

Create a new container

```docker create```

Inspect changes on a container’s filesystem

```docker diff```

Get real time events from the server

```docker events```

Run a command in a running container

```docker exec```

Export a container’s filesystem as a tar archive

```docker export```

Kill a running container

```docker kill```

Fetch the logs of a container

```docker logs```

Pause all processes within a container

```docker pause```

List port mappings or a specific mapping for the container

```docker port```

List containers

```docker ps```

Rename a container

```docker rename```

Restart a running container

```docker restart```

Remove one or more containers

```docker rm```

Run a command in a new container

```docker run```

Start one or more stopped containers

```docker start```

Display a live stream of container(s) resource usage statistics

```docker stats```

Stop a running container

```docker stop```

Display the running processes of a container

```docker top```

Unpause all processes within a container

```docker unpause```

Update configuration of one or more containers

```docker update```

Block until a container stops, then print its exit code 

```docker wait```



## Network and Connectivity Commands

Connect a container to a network

```docker network connect```

Create a new network

```docker network create```

Disconnect a container from a network

```docker network disconnect```

Display information about a network

```docker network inspect```

List all the networks the Engine daemon knows about

```docker network ls```

Removes one or more networks

```docker network rm```

  
## Hub and Registry Commands

Register or log in to a Docker registry

```docker login```

Log out from a Docker registry

```docker logout```

Pull an image or a repository from a Docker registry

```docker pull```

Push an image or a repository to a Docker registry

```docker push```

Search the Docker Hub for images

```docker search```
  

## Shared Data Volume Commands

Create a new volume where containers can consume and store data

```docker volumes create```

Display information about a volume

```docker volumes inspect```

Lists all the volumes Docker knows about

```docker volumes ls```

Remove one or more volumes

```docker volumes rm```
  
