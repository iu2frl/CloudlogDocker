~~This repository is no longer relevant other than fore some personal testing, by cooperating with the Cloudlog creators, this is now included in the official release [magicbug/Cloudlog](https://github.com/magicbug/Cloudlog)~~

Unarchiving the repository as the original creator removed the Docker support

## CloudlogDocker
Create a Cloudlog instance on a Docker container

## Requirements
- MySQL engine up and running
  - A custom DB to store data
  - A custom user with write access to that DB

## Required steps

### Building the image
- Clone this repo
- cd to cloned folder
- run `sudo docker build -t cloudlog:latest .`

### Execute the image
- run `docker-compose up --build -d cloudlog`

### Executing full cloudlog stack
- Clone this repo
- cd to cloned folder
- run `sudo docker compose up -d`

## Full setup guide
Full setup can be found at [IU2FRL Website](https://www.iu2frl.it/cloudlog-su-docker-container/)

## Public image
Image can be accessed on the hub at [iu2frl/cloudlog](https://hub.docker.com/repository/docker/iu2frl/cloudlog/general)
