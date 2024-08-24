Project Description Project Title: Web Application Deployment using Containerization.

In this project, I set up a containerized environment using Docker on an Ubuntu machine and deployed a web application. This involved several key steps:

Key Steps:

Install Docker on Ubuntu: Configured and installed Docker on an Ubuntu machine, setting up the environment for containerization.

Pull BusyBox Image from DockerHub: Pulled the lightweight BusyBox image from DockerHub to understand the basics of working with Docker images and containers.

Run BusyBox Container: Created and ran a BusyBox container to print "hello docker" on the console. This step helped in understanding how to interact with containers and execute commands within them. (docker run busybox echo "hello docker")

Deploy Web Application on Container: Deployed a web application on a Docker container, ensuring that the application runs smoothly in an isolated environment. This included creating a Dockerfile, building the Docker image, and running the container. Sample Dockerfile:

Dockerfile

FROM nginx:latest

COPY . /usr/share/nginx/html

Commands:

docker build -t my-webapp .

docker run -d -p 80:80 my-webapp

Outcomes:

Gained hands-on experience with Docker installation and configuration on Ubuntu.

Learned to pull and run Docker images from DockerHub.

Developed skills in deploying and managing web applications within Docker containers.

Enhanced understanding of containerization benefits, such as isolated environments and streamlined deployment.

This project showcased the power of Docker in simplifying development workflows and ensuring consistent environments across different stages of the software development lifecycle.
