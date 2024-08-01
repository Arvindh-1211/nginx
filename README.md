# README

This repository contains a simple HTML page, hosted using Nginx in a Docker container.

Nginx (pronounced "engine-x") is a popular, open-source web server software that can also be used as a reverse proxy, load balancer, and HTTP cache. It is known for its high performance, scalability, and reliability.

### Prerequisites

- Docker installed on your machine
- Basic understanding of Docker and containerization

### Step 1: Create your HTML content
 - Create a html file called index.html.

### Step 2: Create a Docker Compose file

 - Use the official Nginx image
 - Mount/copy the html files to `/usr/share/nginx/html` in the container

### Step 3: Run the container
Run the following command in your terminal:

```bash
docker-compose up
```
This will start the Nginx container, and you can access your HTML page by visiting http://localhost:8080 in your web browser.

### To stop the container:

```bash
docker-compose down
```
This will stop and remove the container.