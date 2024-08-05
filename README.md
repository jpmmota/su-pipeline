# Platform Engineer Take-Home Assignment

## Introduction

Welcome to the Platform Engineer take-home assignment! In this task, you will set up a React frontend and an Express.js backend, containerize both applications using Docker, and configure Docker Compose to orchestrate them. Additionally, you will set up GitHub Actions to automate the build and publish the Docker images to your personal Docker repository.

## Assignment Overview

You will be provided with the source code for a React frontend and an Express.js backend. Your task is to:
1. Create Dockerfiles for both the frontend and backend.
2. Create a `docker-compose.yml` file to run the frontend and backend services.
3. Configure GitHub Actions to build and publish the Docker images to your personal Docker repository.
4. Ensure the environment variables are correctly handled during the build process.

## Requirements

### 1. Containerization

#### Dockerfile for the Frontend

- Create a `Dockerfile` in the frontend directory to:
  - Install dependencies.
  - Build the React application.
  - Serve the application using Nginx.

#### Dockerfile for the Backend

- Create a `Dockerfile` in the backend directory to:
  - Install dependencies.
  - Run the Express.js application.

### 2. Docker Compose

- Create a `docker-compose.yml` file to:
  - Define the frontend and backend services.
  - Ensure the frontend service depends on the backend service.
  - Use environment variables from `.env` files.

### 3. GitHub Actions

- Set up GitHub Actions to:
  - Build Docker images for the frontend and backend.
  - Push the Docker images to your personal Docker repository (e.g., Docker Hub).

### 4. Environment Variables

- Ensure the environment variables are correctly handled during the build process using `.env` files.

## Provided Files

- `frontend`: Source code for the React application.
- `backend`: Source code for the Express.js application.

## Instructions

### Step 1: Create Dockerfiles

- Create Dockerfiles for the frontend and backend applications. Ensure that the Dockerfiles correctly build and run the applications.

### Step 2: Docker Compose

- Create a `docker-compose.yml` file that defines both the frontend and backend services. Ensure the frontend service depends on the backend service and that environment variables are correctly passed using `.env` files.

### Step 3: Environment Variables

- Create `.env.frontend` and `.env.backend` files to store environment variables. Ensure that these variables are used in your Dockerfiles and Docker Compose configuration.

### Step 4: GitHub Actions

- Set up GitHub Actions to automate the build and publish process for the Docker images:
  - Create a workflow file (e.g., `.github/workflows/docker-publish.yml`) to define the CI/CD pipeline.
  - Configure the workflow to build the Docker images for the frontend and backend.
  - Push the Docker images to your personal Docker repository (e.g., Docker Hub).

### Submission Instructions

1. **Submit your solution as a GitHub repository link.**
2. **Ensure your repository includes:**
  - Dockerfile for the frontend
  - Dockerfile for the backend
  - `docker-compose.yml`
  - `.env.frontend` and `.env.backend` files
  - GitHub Actions workflow file

## Evaluation Criteria

- **Technical Competence**: Correctness and completeness of the Docker setup, CI/CD pipeline, and environment variable handling.
- **Problem-Solving**: Ability to address and solve potential challenges in the setup and deployment process.
- **Documentation**: Clarity and completeness of the provided documentation.
- **Creativity and Innovation**: Use of innovative solutions or tools to enhance the task.

## Questions?

If you have any questions about the assignment, please reach out to us at [max.vega@sensorup.com].

Good luck, and we look forward to seeing your solution!