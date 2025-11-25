## 🐳 Dockerized Node.js Todo App

A fully containerized Node.js Todo Application built as part of my Docker learning journey.
This project demonstrates building Docker images, running containers, port mapping, and pushing images to Docker Hub.

📌 Project Overview

This application is a simple Todo App built using Node.js + Express + HTML.
I created a production-ready Dockerfile, built a Docker image, ran it locally, and published it to Docker Hub:

📦 Docker Hub Repository → https://hub.docker.com/r/harshakanduri/myfirstapp 

📁 Folder Structure
├── src/
├── Dockerfile
├── package.json
├── package-lock.json
├── README.md
├── Docker snapshots/   ← screenshots folder

🐳 Docker Setup & Commands
# Build the Docker image
docker build -t myfirstapp .

# Run the container on port 3000
docker run -it -d -p 3000:3000 myfirstapp

# Verify running container
docker ps

# Tag image for Docker Hub
docker tag myfirstapp harshakanduri/myfirstapp

# Push to Docker Hub
docker push harshakanduri/myfirstapp

🖼 Screenshots (Snapshots)

Below are the key steps visually demonstrated using screenshots.


