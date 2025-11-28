This project is a fully containerized MEAN stack application (MongoDB, Express, Angular, Node.js) using Docker, Docker Compose, and Nginx as a reverse proxy.
clone the repo
  git clone https://github.com/<your-username>/<repo-name>.git
  cd <repo-name>
push the project to github
  git init
  git add .
  git commit -m "Initial commit"
  git remote add origin <your-repo-url>
  git push -u origin main
Install docker
 sudo apt update
 sudo apt install docker.io -y
 sudo usermod -aG docker $USER && newgrp docker
Install docker compose
 sudo apt install docker-compose -y
Create backend dockerfile
Create frontend dockerfile
Create docker-compose.yml
Build and run with docker-compose
 docker-compose build
 docker compose up -d
Check running containers
  docker ps
Your application is now available on:http:ipaddress
<img width="1920" height="1080" alt="Screenshot 2025-11-28 161259" src="https://github.com/user-attachments/assets/023e6fd9-0182-4a6d-b704-787d8128a5e4" />

 
