# Supported tags and respective `Dockerfile` links

* `latest` [(ubuntu/Dockerfile)](https://github.com/lysender/docker-node/blob/master/ubuntu/Dockerfile)
* `ubuntu` [(ubuntu/Dockerfile)](https://github.com/lysender/docker-node/blob/master/ubuntu/Dockerfile)
* `alpine` [(alpine/Dockerfile)](https://github.com/lysender/docker-node/blob/master/alpine/Dockerfile)

# Docker NodeJS images

Builds base images for NodeJS 6.x for the following OS:

* Ubuntu 16.04 Xenial - currently 6.3.0
* Alpine Linux 3.4 - currently 6.2.0

## Test versions

Note: Default command to execute is: `/usr/bin/node --version` so running below will simply print the node version.

~~
docker run --rm lysender/node:latest
docker run --rm lysender/node:ubuntu
docker run --rm lysender/node:alpine
~~

## NodeJS and OS References

* [NodeJs](https://hub.docker.com/_/node/)
* [Ubuntu](https://hub.docker.com/_/ubuntu/)
* [Alpine](https://hub.docker.com/_/alpine/)


