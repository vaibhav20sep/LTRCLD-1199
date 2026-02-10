LTRCLD-1199
Files used during the LAB Session

Docker version = 24.09
## Command to build the container
docker build -t swiss-knife-alpine:latest -f Dockerfile.swiss-alpine .
## Command to save container as tar file 
docker save swiss-knife-alpine:latest -o swiss-knife-alpine.tar
