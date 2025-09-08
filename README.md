# 🚀 Docker in DevOps – Week 12 Journey

In my **DevOps Learning Journey (Week 12)**, I focused on **Docker** and practiced how it is used for **Node.js app deployment on AWS EC2**.  

---

## 🔹 What I Learned
- Why **Docker** is needed in DevOps → consistency, automation, containerization.
- Built Docker images using:
  ```bash
  docker build -t my-node-app .
Ran containers with:

bash
Copy code
docker run -p 3000:3000 my-node-app
Wrote a Dockerfile using the official Node.js image.

Deployed on AWS EC2, exposing port 3000 in security groups.

Understood Docker as the root of deployment automation → no manual dependency installation needed.

🔹 Repo Details
This repository contains:

Dockerfile → defines Node.js base image and dependencies

Node.js application files

Deployment steps & Docker commands

📌 Deployment
Clone the repo:

bash
Copy code
git clone https://github.com/azmatahmed11/docker-push-docker.git
cd docker-push-docker
Build Docker image:

bash
Copy code
docker build -t my-node-app .
Run the container:

bash
Copy code
docker run -p 3000:3000 my-node-app
🌐 Portfolio: https://azmatahmed.netlify.app/
📂 GitHub Repo: https://github.com/azmatahmed11/docker-push-docker
