# Docker environments

This directory is a collection of docker compose files representing environments
to use in development. Each environment is stored in a folder and contains
a `docker-compose.yml` file.

To use the environment in your project, create a symlink to the desired
`docker-compose.yml` file and run `docker-compose up -d` to start it.
To stop the environment run `docker-compose down`.

