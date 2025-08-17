# XOps Static Web App

A simple static "Hello from XOps!!!" web appplication running inside a Docker container.

## Steps to Run

### 1. Build the Docker Image

docker build -t xops-webapp .

###2.run the docker 

docker run -d -p 8080:80 xops-webapp
