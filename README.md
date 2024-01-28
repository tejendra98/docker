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


