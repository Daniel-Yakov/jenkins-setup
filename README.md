# Jenkins Setup
This repository contains the necessary files to quickly set up a Jenkins server as a Docker container on an EC2 instance.
It also installs Docker, Docker Compose, and the AWS CLI on the container for convenience.

## Getting Started
To get started, you will need to have Docker and Docker Compose installed on your EC2 instance. Once you have these prerequisites, follow these steps:

1. Clone this repository onto your EC2 instance.
2. Navigate to the directory containing the docker-compose.yaml file.
3. Run the following command to start the Jenkins container: 
```
docker-compose up -d
```
Once the container is up and running, you can access the Jenkins server by navigating to `http://<ec2-instance-ip>:8080` in your web browser.
Follow the Jenkins setup wizard to configure your Jenkins server.

## Customization
If you need to customize the Jenkins setup, you can modify the `Dockerfile` and `docker-compose.yaml` files in this repository to suit your needs.