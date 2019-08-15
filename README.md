# Cloud Develop

It´s a fork of the original repo with my personal projects and exercises

## Installation

Use [docker](https://www.docker.com/) to build the images. Go to folder course-03/udacity-c3-deployment/docker and run:

```bash
docker-compose -f docker-compose-build.yaml build --parallel
```

## CI/CD

You´ll find a .travis.yml file in root folder with the commands to build an image on every push to github repository

## Docker Images

Microservices and frontend app have their docker file, also you can find the images in docker hub

1. lemena86/udacity-frontend
2. lemena86/udacity-restapi-feed
3. lemena86/udacity-restapi-user
4. lemena86/udacity-reverseproxy

## Kubernetes

Deployments, services and secrets config are located in folder course-03/udacity-c3-deployment/k8s