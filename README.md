# Pterodactyl with Docker
Pterodactyl panel using three docker containers: 1 for DB, 1 for PHP, 1 for Web

# Getting Started
In the top level directory of the repository:
```
docker build -t pterodactyl-standalone .
docker-compose up -d
```

You can check that the containers are up with:
```
docker ps
```