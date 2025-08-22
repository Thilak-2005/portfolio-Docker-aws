# portfolio-Docker-aws
Personal portfolio website containerized with Docker, served with Nginx, and deployed on AWS EC2.
Personal Portfolio Deployment on AWS with Docker & Nginx

This repository contains the complete setup and deployment process of **my personal portfolio website**.  
The site was fully containerized using **Docker**, served using **Nginx**, and deployed on an **AWS EC2 instance** for global access.

 # Project Overview
As part of my cloud and DevOps learning journey, I built and deployed my personal portfolio to showcase my skills, projects, and achievements.  
Instead of using simple static hosting, I challenged myself to use **containerization and cloud deployment** to gain real-world deployment experience.

  Why this project matters?
- Shows ability to work with **Docker, Linux, and Nginx**  
- Hands-on with **AWS EC2 deployment**  
- Covers **cloud networking & security configuration** (Security Groups, ports)  
- Demonstrates a **practical DevOps project** for a fresher  

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript, Bootstrap  
- Server: Nginx (Alpine image)  
- Containerization: Docker  
- Cloud Hosting: AWS EC2 (Ubuntu)  
- Operating System: Linux  


## ⚙️ Steps to Deploy

### Clone this repository 
```bash
git clone https://github.com/Thilak-2005/portfolio-docker-aws.git
cd portfolio-docker-aws
```
----
### Build the Docker image  
```bash
docker build -t my-portfolio .
```
----
### Run the container
```bash
docker run -d -p 80:80 my-portfolio
```

### Access the portfolio
```bash
Open your browser → http://<your-ec2-public-ip>
