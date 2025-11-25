## 🐳 Dockerized Node.js Todo App

A fully containerized Node.js Todo Application built as part of my Docker learning journey.
This project demonstrates building Docker images, running containers, port mapping, and pushing images to Docker Hub.

## 📌 Project Overview

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

📌 1. Project Setup & package.json

![Project Setup   package json](https://github.com/user-attachments/assets/26518a17-8aa8-40dd-aa9e-938b2a32ef29)

📌 2. Dockerfile Creation & Build Output

![Dockerfile Creation   Build Output](https://github.com/user-attachments/assets/381b4744-e455-4b5b-8e76-49cc55c17ee4)

📌 3. Docker Images (Local)

![Docker Images (Local)](https://github.com/user-attachments/assets/1ccc73a0-45d9-42f0-968d-8e9b89a6578d)

📌 4. Running Container in Docker Desktop

![Running Container in Docker Desktop](https://github.com/user-attachments/assets/427a16f6-ccd7-4c7b-862f-a0be20eb1a29)

📌 5. Todo App Running on localhost:3000

![Todo App Running on localhost3000](https://github.com/user-attachments/assets/1d9fcb58-5246-4f42-92fa-c4d6dd6603b2)

📌 6. Docker Hub Repository (Image Pushed)

![Docker Hub Repository (Image Pushed)](https://github.com/user-attachments/assets/528ea518-67dd-4b59-8bf7-ef254604afb1)

## 🔗 Docker Hub Link

You can pull the image using:

docker pull harshakanduri/myfirstapp

## 🚀 What I Learned

✔ Writing a Dockerfile from scratch
✔ Building & tagging Docker images
✔ Running containers with port mapping
✔ Checking container logs & status
✔ Publishing images to Docker Hub
✔ Testing application inside Docker environment

## 🙌 Acknowledgements

Thanks to the DevOps community and learning resources that guided me through this project.

## 🎯 Summary

This project demonstrates full hands-on Docker workflow:

* Creating Dockerfile

* Building images

* Running containers

* Exposing ports

* Pushing to Docker Hub

* Testing app inside container

* Maintaining snapshot proof
