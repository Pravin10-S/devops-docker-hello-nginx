# DevOps Docker Hello Nginx

Simple project: custom nginx Docker image serving a page at http://localhost:8080.

## How to run

1. Build image:
   docker build -t pravin-nginx:v1 .

2. Run container:
   docker run --name pravin-nginx -p 8080:80 -d pravin-nginx:v1

Then open http://localhost:8080 in your browser.
