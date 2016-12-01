# WordPress on Docker

Use this boilerplate if you want to run WordPress on Docker.

## Introduction

This is a fairly simple docker-compose file that uses two images: `mysql` and `wordpress`.

The docker-compose file volumes the `/wordpress` directory with the Docker image web folder.

The first time you'll up the containers, it will copy every WordPress files into the volumed `/wordpress` directory.

Then you'll be able to edit the WordPress file and start developing.

## Usage

Start the containers :

`docker-compose up -d`

Note : the `-d` argument means detached

Read the logs :

`docker-compose logs`

Note : You'll get a tail of the logs. Add `-f` argument to see it live.

Stop the containers

`docker-compose stop`

Remove the containers :

`docker-compose down`

Note : add a `--volume` argument to also remove volumes

## Contributing

You are free to contact me to improve this repository in any way.
