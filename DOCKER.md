1. What is Docker? What is container
Container is a way to package an application with all the necessary depedencies and configurations

Package is portable. It can easily be shared

2. Where do the containers live?
Containers live in Container repositories. There is also public repository for Docker containers where you can
find any application container you want. (DockerHub)

3. What is Container (technical Standpoint)
* layers of images
* Linux Base Image (Alpine)
* Application image


4. pulling docker image from dockerhub
```bash
docker run postgres: 17.6
```