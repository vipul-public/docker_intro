# Docker Build

## Format:

docker build -t <image tag name> . 

Example:
docker build -t app1 .

# Docker Run 

## Format:

docker run <run arguments> <image tag name> 

Example:
docker run app1 

# Docker Exec (Lets you inspect the container)

## Format: 

docker exec -it <running container id_or_name> /bin/bash 

Examples: 
docker run -t -i ubuntu /bin/bash
docker exec -it ubuntu /bin/bash

# Usefull commands

docker run -d -p 5000:5000 web_app:latest

