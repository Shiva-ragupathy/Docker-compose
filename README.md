# Custom Nginx Deployment using Docker Compose

## Project Overview
This project demonstrates how to deploy a custom Nginx container using Docker and Docker Compose on an AWS EC2 instance.

## Technologies Used
- AWS EC2
- Docker
- Docker Compose
- Nginx

## Project Features
- Custom Nginx Docker image
- Docker Compose deployment
- Bind mount at `/var/opt/nginx`
- Image pushed to Docker Hub

## Run the Project

```bash
docker compose up -d --build
