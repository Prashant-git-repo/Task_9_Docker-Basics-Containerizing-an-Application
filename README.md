# Docker Basics – Containerizing a Flask Application

## Objective
Understand Docker image creation, container execution, and lifecycle.

## Tools
- Docker
- Python Flask

## Steps Performed
1. Installed Docker and verified setup
2. Created Flask application
3. Wrote Dockerfile
4. Built Docker image
5. Ran container and exposed port
6. Checked logs and container status
7. Cleaned up containers and images

## Dockerfile Explanation
- FROM: Python base image
- WORKDIR: Application directory
- COPY: Copy dependencies and app code
- RUN: Install dependencies
- EXPOSE: Application port
- CMD: Start Flask app

## Output
Application accessible at `http://localhost:5000`
