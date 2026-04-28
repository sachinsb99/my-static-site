# My Static Site (Docker + AWS)

This is a simple static website deployed using Docker on AWS EC2.

## 🚀 Run Locally

### 1. Build Docker Image
docker build -t my-static-site .

### 2. Run Container
docker run -d -p 80:80 my-static-site

### 3. Open in Browser
http://localhost

## ☁️ Deploy to AWS EC2

1. Launch EC2 instance
2. Install Docker:
   sudo apt update
   sudo apt install docker.io -y

3. Clone repo:
   git clone <your-repo-url>
   cd my-static-site

4. Build & run:
   docker build -t my-static-site .
   docker run -d -p 80:80 my-static-site

5. Visit:
   http://<your-ec2-public-ip>

## 🛠 Tech Stack
- HTML, CSS, JavaScript
- Docker (Nginx)
- AWS EC2