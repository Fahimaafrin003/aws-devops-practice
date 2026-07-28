# Docker Basics

## What is Docker?
Docker is a platform used to create, deploy and run applications using containers.

## Docker Image
- A Docker image is a template used to create containers.
- It contains application code, libraries and dependencies.

## Docker Container
- A container is a running instance of a Docker image.
- It provides an isolated environment to run applications.

## Difference Between Image and Container

Image:
- Static template
- Used to create containers

Container:
- Running application environment
- Created from an image

## Common Docker Commands

### Check Docker Version
```bash
docker --version
docker images
docker ps
docker pull image_name
docker run image_name
docker stop container_id
