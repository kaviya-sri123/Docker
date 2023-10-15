# Docker
> Container is a running environment for image
 ***Pulling an image from docker hub***
### docker run dockerimage:version
> Pulls image and starts container ( Pull and start )
 ***To check running containers***
### docker ps
 ***Command to pull image*** ###
### docker pull imagename
 ***Command to start container*** ###
### docker start id
 ***Command to stop container*** ###
### docker stop id
 ***Command to check existing images*** ###
### docker images
 ***Command to run container in detached mode*** ###
### docker run -d redis
 ***Command to list running and stopped containers*** ###
### docker ps -a
 ***Command to bind post to container*** ###
### docker run -p6000:6379 redis ( host_port:container_port 
 ***Command to see logs*** ###
### docker logs container id
 ***Command to create name for the container*** ###
### docker run -d -p6001:6379 --name redis-older redis:4.0
 ***Command to get interactive interminal for running container*** ###
### docker exec -it docker-id /bin/bash


