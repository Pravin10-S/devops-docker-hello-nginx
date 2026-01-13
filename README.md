# DevOps Docker Hello Nginx

Simple project: custom nginx Docker image serving a page at http://localhost:8080.

## Features

- **Dockerfile**: Multi-stage build with nginx:alpine for small image size.
- **GitHub Actions CI/CD**: Automatically builds Docker image on every push to `main`.
- **Local testing**: Easy to run locally for quick testing.

## How to run locally

1. Build image:
   ```bash
   docker build -t pravin-nginx:v1 .
