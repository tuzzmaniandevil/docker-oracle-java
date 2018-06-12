# Supported tags and respective `Dockerfile` links

* `java8`, `latest` [(Dockerfile)](https://github.com/tuzzmaniandevil/docker-oracle-java/blob/master/java8/Dockerfile)

[![ImageLayers.io](https://badge.imagelayers.io/cogniteev%2Foracle-java:latest.svg)](https://imagelayers.io/?images=tuzzmaniandevil%2Foracle-java:latest,tuzzmaniandevil%2Foracle-java:java8)

# Base Docker Image

* [ubuntu:18.04](https://registry.hub.docker.com/_/ubuntu/)

# Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/cogniteev/oracle-java/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull tuzzmaniandevil/oracle-java`

### Usage

    docker run -it --rm tuzzmaniandevil/oracle-java

#### Run `java`

    docker run -it --rm tuzzmaniandevil/oracle-java java

#### Run `javac`

    docker run -it --rm tuzzmaniandevil/oracle-java javac

# LICENSE

APACHE 2.0
