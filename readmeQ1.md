# Q1: Microservices and GitHub Actions

In this part, i containerize multiple microservices and set up an automated pipeline using GitHub Actions to build and push Docker images to both GitHub and Docker Hub.

## Commands and Descriptions

These are the commands:


 `docker-compose up --build`  Builds the Docker images for all microservices and starts them as a application

 `git add .`  Stages all changes

 `git commit -m "new commit"`  Commit the changes to the local repository .

 `git push origin main`  Push the code to the main branch, 

 `docker ps`  List all running containers

 `docker-compose down`  Stop and removes the containers, networks, and images/
