# Nginx Dockerfile

This repository contains an automated **Dockerfile** of [HHVM](http://hhvm.com/)

## Supported tags

+ `latest`
+ `3.7.2` (Base image nginx:1.9.2)

### Base Docker Image

* [julienvincent/nginx](https://registry.hub.docker.com/u/julienvincent/nginx/)

### Usage

    docker run --name nginx-hhvm -v /some/content:/data/www -d julienvincent/nginx-hhvm