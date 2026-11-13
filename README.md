# My DevOps Project

## Project Overview
A simple website deployed on AWS EC2 using Docker and Nginx.

## Technologies Used
- AWS EC2
- Amazon Linux 2023
- Docker
- Nginx
- HTML

## Deployment
1. Launch an EC2 instance.
2. Install Docker.
3. Create an HTML website.
4. Build a Docker image.
5. Run the container on port 80.
6. Access the website using the EC2 public IP.

## Docker Commands
docker build -t my-devops-site:v1 .
docker run -d --name my-devops-web -p 80:80 my-devops-site:v1

## Author
Nanda Kumar
