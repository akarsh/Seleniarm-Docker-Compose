# Seleniarm-Docker-Compose

This project contains a docker-compose yaml file which is targeted towards users of arm64 architecture M1 Mac

The docker-compose yaml file follows the hub and node usage of Selenium Grid. It uses seleniarm docker images.

## Build and run

For detached execution docker-compose yaml file execute

```
docker-compose -f docker-compose.yaml up -d
```

The Selenium Grid will be running on host url: http://localhost:4444/ui

## Stop

To stop the selenium-hub container execute

```
docker-compose -f docker-compose.yaml down
```
