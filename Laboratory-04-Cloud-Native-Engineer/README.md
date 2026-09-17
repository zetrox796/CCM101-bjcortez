# Checkpoint 6 - Technical Documentation

## Mission Overview
This lab explores the shift from Virtual Machines to containers. We deployed an Nginx web server using Docker. We learned how containers save memory and start fast.

## Objectives
* Compare the Virtual Machines and containers.
* Access a Docker environment using the KillerCoda.
* Run the basic commands of Docker.
* Manage an Nginx container.

## Docker Commands Executed
| Command | Description |
| :--- | :--- |
| `docker --version` | Checks Docker version. |
| `docker info` | Shows Docker environment status. |
| `docker pull nginx` | Downloads the Nginx image. |
| `docker run -d -p 8080:80 nginx` | Runs the server and maps the port. |
| `curl http://localhost:8080` | Tests local web server. |
| `docker ps` | Lists active containers. |
| `docker stop <container_id>` | Stops running container. |
| `docker ps -a` | Shows all containers. |
| `docker rm <container_id>` | Deletes stopped container. |

## Skills Learned
* I learned how to start and stop the containers.
* I learned how to map the network ports.

## Challenges Encountered
* Remembering the basic Docker commands