# Simple Static Website with Docker and Nginx

## About This Project
This project is a hands-on Docker practice that I built step by step to understand how containerization works in a real DevOps environment.

I started from Ubuntu machine, installed Docker manually, created a simple static website, and containerized it using Nginx. All steps were done manually through the terminal.

---

## What I Did in This Project
- Set up a new Ubuntu machine
- Installed Docker from the official Docker repository
- Created a simple static website using HTML
- Used the official Nginx Docker image
- Wrote a Dockerfile to copy the website into the container
- Built the Docker image locally
- Ran a Docker container and exposed it on port 80
- Verified the website through the browser

---

## Technologies Used
- Docker
- Nginx
- HTML
- Ubuntu Linux

---

## Project Structure
```bash
nginx-static/
├── Dockerfile
├── website/
│   └── index.html
└── README.md
