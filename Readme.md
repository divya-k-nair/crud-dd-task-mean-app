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

<img width="1920" height="1080" alt="Screenshot 2025-11-28 161410" src="https://github.com/user-attachments/assets/59e9ded4-dde9-45ab-a57b-a4780e11173b" />

<img width="1920" height="1080" alt="Screenshot 2025-11-28 161441" src="https://github.com/user-attachments/assets/6107f9a4-ea5d-45b2-aff0-580c1b7417df" />


pushing the images to dockerhub

<img width="1920" height="1080" alt="Screenshot 2025-11-28 163209" src="https://github.com/user-attachments/assets/fbf3ce9b-8634-4bdb-9c00-09ce434a2a3e" />


<img width="1920" height="1080" alt="Screenshot 2025-11-28 163236" src="https://github.com/user-attachments/assets/412bfd77-e7ae-4916-918a-d453f368b7d8" />

<img width="1918" height="622" alt="Screenshot 2025-11-28 164533" src="https://github.com/user-attachments/assets/4ed296d8-b6a0-430a-a2b5-79fd138b686a" />







 
