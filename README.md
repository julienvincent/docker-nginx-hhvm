## Debian Dockerfile

This repository contains **Dockerfile** of [Nginx](http://nginx.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/julienvincent/nginx/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [debian:wheezy](https://registry.hub.docker.com/u/library/debian/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/julienvincent/nginx-php/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull julienvincent/nginx-php`

   (alternatively, you can build an image from Dockerfile: `docker build -t="julienvincent/nginx-php" github.com/julienvincent/docker-nginx-php`)


### Usage

    docker run -it --rm julienvincent/nginx-php
