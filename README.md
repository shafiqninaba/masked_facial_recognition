# Facial Recognition w/ Accessories using CNN
## Overview
This repository contains the [docker-compose.yml file](docker-compose.yml) that can be used after pulling the images from my [Docker hub repository](https://hub.docker.com/r/shafiqninaba/fyp). This project requires [Docker Desktop](https://www.docker.com/products/docker-desktop/) to run.

## Instructions
1. Pull the images
   1. `docker pull shafiqninaba/fyp:sql-1.0`
   2. `docker pull shafiqninaba/fyp:app-1.0`
   3. `docker pull shafiqninaba/fyp:backend-1.0` (takes quite a while as the image size is relatively huge)
3. Download the [docker-compose.yml file](docker-compose.yml) into an empty folder.
4. Run `docker-compose up` in the same directory as the docker-compose.yml file.
