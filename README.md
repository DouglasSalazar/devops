# Devops

Este repositório contém arquivos aplicados em alguns projetos.

## Tecnologias
* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Hub](https://hub.docker.com/)
* [Jenkins](https://www.jenkins.io/)

## Docker

### Comandos

* docker ps
* docker rm name_container
* docker status name_container
* docker volume create mongodb
* docker build -t mongodb . --no-cache
* docker run -d -v mongodb:/data/db --name mongodb mongodb:latest
* sudo docker-compose up -d --build
* sudo docker-compose down & sudo docker system prune -a
* sudo docker network create default_network
* docker exec -it node_server /usr
* docker system prune -a -f
