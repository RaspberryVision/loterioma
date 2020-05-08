# Server

## Prerequisites

To start work with docker you must install docker and docker-compose.

## Running jenkins

Jenkins for the system is fired in a docker container (for educational purposes, there is a chance that for reasons of effort, 
you will have to deviate from this idea).

```
sudo docker run -d -p 5549:8080 -p 50000:50000 -v /var/applications/loterioma/jenkins:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock -v $(which docker):/usr/bin/docker jenkins/jenkins:lts
```

## Dev instance

## Prod instance

