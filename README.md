# mongodb-docker

## Install docker
https://docs.docker.com/engine/install/ubuntu/

## Add current user to docker group
sudo usermod -aG docker $(whoami)
logout

cp docker-compose.yml.example docker-compose.yml
docker-compose up -d
## OR
docker compose up -d