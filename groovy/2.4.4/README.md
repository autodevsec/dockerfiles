## Groovy Dockerfile

This repository contains **Dockerfile** of [Groovy](http://groovy.codehaus.org/) for [Docker](https://www.docker.com/)'s [build](https://registry.hub.docker.com/u/sierratecnologia/groovy/) published to the public [Docker Hub](https://hub.docker.com/).

### Installation

1. Install [Docker](https://www.docker.com/).

2. Pull the image 
  * `docker pull sierratecnologia/groovy`
  * `docker pull sierratecnologia/groovy:2.3`
  * `docker pull sierratecnologia/groovy:2.3.7`
  * `docker pull sierratecnologia/groovy:2.3.8`
  * `docker pull sierratecnologia/groovy:2.3.9`
  * `docker pull sierratecnologia/groovy:2.3.10`
  * `docker pull sierratecnologia/groovy:2.3.11`
  * `docker pull sierratecnologia/groovy:2.4`
  * `docker pull sierratecnologia/groovy:2.4.0`
  * `docker pull sierratecnologia/groovy:2.4.1`
  * `docker pull sierratecnologia/groovy:2.4.2`
  * `docker pull sierratecnologia/groovy:2.4.3`
  * `docker pull sierratecnologia/groovy:2.4.4`
  
### Usage

    docker run -v $(pwd):/source -v <grape-root-dir>:/graperoot sierratecnologia/groovy <groovy-file> 
