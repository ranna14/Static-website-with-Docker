# Static Website with Docker Volumes

## About This Project
This project is an enhancement of the previous project using **Docker Volumes**.  
Instead of copying the website files into the Docker Image, here we link the website folder on the host machine directly to the container using a Volume.  

This allows any changes made to the files to appear immediately in the browser **without rebuilding the image**.

---

## What I Did
- Used the same static website from the previous project
- Created a new Docker Image without copying files into it
- Used Docker Volume to link the website folder from the host to the container
- Ran the container with Nginx to see live updates
- Verified that any file changes appear immediately in the browser

---

## Technologies Used
- Docker
- Nginx
- Docker Volumes / Bind Mount
- HTML
- Ubuntu Linux

---

## Project Structure
nginx-static/
├── Dockerfile
├── website/
│   └── index.html
└── README.md
