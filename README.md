Use WordPress locally with Docker using Docker compose

## Installation
 Open a terminal and cd to the folder in which docker-compose.yml is saved and run:<br />
 ```
 docker-compose up
 ```
## Usage
### Starting containers

You can start the containers with the up command in daemon mode (by adding -d as an argument) or by using the start command:
```
docker-compose start
```
### Stopping containers
```
docker-compose stop
```
### Removing containers

To stop and remove all the containers use thedown command:
```
docker-compose down
```
