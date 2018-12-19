# Docker

Docker is a computer program that performs operating-system-level virtualization, also known as "containerization".[6] It was first released in 2013 and is developed by Docker, Inc

# docker installation

sudo apt-get remove docker docker-engine docker.io

sudo apt-get update

sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo apt-key fingerprint 0EBFCD88

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu \ $(lsb_release -cs) \ stable"

sudo apt-get update

sudo apt install docker.io

docker --version

sudo docker run hello-world

# List Docker CLI commands


docker container --help

# Display Docker version and info

docker --version

docker version

docker info

# Execute Docker image
 
 docker run hello-world

# List Docker images

docker image ls

# List Docker containers (running, all, all in quiet mode)

docker container ls

docker container ls --all
