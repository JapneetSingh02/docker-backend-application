# node-docker
Simple node and express docker 

## To build the Dockerfile
Execute the command: docker build -t japneet/backend-docker

Note: Remember to change image name "japneet/backend-docker" as per your choice.

It will start pulling and downloading images.

## Check created image
Run command: docker images

You will see as below (might be your image name instead of japneet/backend-docker)

japneet/backend-docker   latest              81aff23e773c        48 seconds ago      971MB

node                     latest              91a3cf793116        6 days ago          942MB

## Now Run image
execute command: docker run -p 4000:4000 japneet/backend-docker

Here i am executing at port 4000.

You can try to run http://localhost:4000/ on browser to verify if image is running or not.
