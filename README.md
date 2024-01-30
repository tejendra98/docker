
# What is a Container?

A way to package application with all the necessary dependencies and configuration 
Portable artifact, easily shared and moved around
Make development and deployment more effiient


Container lives in Container Repository. DockerHub is public repository for Docker


Container

Layers of Images
Mostly Linux Base Image, because small in size
Application Image on top


Container is a running environment for Image



# Basic Commands

List images available locally

    docker images


List running containers

    docker ps


Lists running and stopped container

    Docker ps -a


Pull image locally and start new container

    docker run <image>

    docker run -d -p <host_port>:<container_port> --name <conatiner_name> <image>


stops the container
    
    docker stop <conatiner_id>


starts stopped container

    docker start <conatiner_id>



Docker rmi <image>

Docker rm <conatiner>


docker exec -it <conatiner_id> /bin/bash


Docker Network


Docker network ps
Docker network create <network_name




Docker-compose up -f <file_name> -d

Docker-compose -f <file_name> down



Docker Volume

Data is gone! When restarting or removing the container

Folder in physical host file system is mounted into the virtual file system of Docker
