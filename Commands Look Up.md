# Command	and Action

### docker ps
Lists all running containers. -a option will list stopped and running both

### docker inspect [container_name]	
Provides all info about the container

### docker stop [container_name]	
Stops the running container

### docker kill [container_name]	
Kills(stops) the container and removes the container from the system

### docker rmi [image/s]	
Removes the provided image

### docker images	
Lists all images on the system

### docker exec [-it]	
Executes command in a Docker container

### docker system	
Gets the Docker system information such as memory usage and housekeeping stuff

### docker system prune	
This command will save you from getting the “No memory left” nightmare with production systems
