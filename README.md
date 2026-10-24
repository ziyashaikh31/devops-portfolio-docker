# Dockerized Portfolio Website on AWS EC2

## Project Overview
A responsive personal portfolio website containerized using Docker and Nginx, then deployed on an AWS EC2 Ubuntu instance.

## Technologies Used
- AWS EC2 (Ubuntu)
- Docker
- Nginx
- HTML and CSS
- Git and GitHub

## Deployment Steps
1. Created a portfolio website using HTML and CSS.
2. Created a Dockerfile using the Nginx Alpine image.
3. Built the Docker image using `docker build -t portfolio-website .`
4. Ran the container and mapped port 80 using `docker run -d -p 80:80 portfolio-website`.
5. Deployed the website on AWS EC2 and verified public access.

## Project Links
- **Live Website:** http://15.252.180.80
- **GitHub Repository:** https://github.com/ziyashaikh31/devops-portfolio-docker

## Author
Ziya Shaikh — Aspiring DevOps Engineer
