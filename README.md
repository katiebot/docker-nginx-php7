# docker-nginx-php7 #

Based on https://github.com/ngineered/nginx-php-fpm.

This is a Dockerfile to build a container image for nginx and php7.0-fpm.

## Installation ##

    docker build -t touchcast/docker-nginx-php7 ./

## Running ##
To run the container:

    docker run --name nginx_php7 -p 8080:80 -d touchcast/docker-nginx-php7
    
To SSH into the running container:

    docker exec -i -t <containerID> bash
    
