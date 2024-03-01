# kit-starter-headless-lamp-docker
Kit starter for headless application on LAMP and Docker

## Installation guide
### Clone the starter application
```
git clone https://github.com/rafalsamek/kit-starter-headless-lamp-docker.git
```
### Go to the project root directory
```
cd kit-starter-headless-lamp-docker
```
### Launch docker
```
docker-compose up -d
```
### Go to containers and create applications: e.g. Symfony in the backend and e.g. Vue JS in the frontend
```
docker ps
docker exec -it <container_id> bash
```