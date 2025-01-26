# Docker Image Build and Push

This project demonstrates how to build a Docker image and push it to Docker Hub using Git Hub Actions.

## Purpose

This repository contains a simple example of:
- Creating a Dockerfile to build a Docker image.
- Setting up a GitHub Actions workflow to automatically build the Docker image when code is pushed to the repository.
- Pushing the built Docker image to Docker Hub.

## Prerequisites

Before you can use this repository, ensure you have the following:
- A **Docker Hub** account to store the Docker images.
- **GitHub repository secrets** configured with your Docker Hub username and password to allow GitHub Actions to push to your Docker Hub repository.

## How to Use

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repository.git
