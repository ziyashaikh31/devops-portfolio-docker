# Dockerized Portfolio Website with CI/CD Automation

## Project Overview
A personal portfolio website containerized using Docker and Nginx, deployed on AWS EC2, with CI/CD automation using GitHub Actions. The workflow automatically builds and pushes the Docker image to Docker Hub whenever code is pushed to the `main` branch.

## Technologies Used
- AWS EC2 (Ubuntu)
- Docker and Docker Hub
- Nginx
- HTML and CSS
- Git and GitHub
- GitHub Actions
- YAML

## Project Features
- Containerized a portfolio website using Docker.
- Deployed the application on an AWS EC2 Ubuntu instance.
- Automated Docker image builds using GitHub Actions.
- Automatically pushed the image to Docker Hub.
- Used GitHub Secrets to store Docker Hub credentials securely.
- Verified successful pipeline execution and live website access.

## CI/CD Workflow
1. Push code to the GitHub repository.
2. GitHub Actions triggers the workflow.
3. The workflow builds the Docker image.
4. The image is pushed to Docker Hub.
5. The image is available for deployment on AWS EC2.

## Run Locally
Build the image:

```bash
docker build -t portfolio-website .
```

Run the container:

```bash
docker run -d -p 8080:80 portfolio-website
```

Open `http://localhost:8080` in your browser.

## Project Links
- **Live Website:** http://3.108.215.123
- **GitHub Repository:** https://github.com/ziyashaikh31/devops-portfolio-docker
- **Docker Hub Image:** https://hub.docker.com/r/ziyashaikh18/portfolio-website

## Author
Ziya Shaikh — Aspiring DevOps Engineer
