# Dockerized Angular App - Helpdesk

This project demonstrates how to Dockerize an Angular application. It includes a custom Dockerfile, a .dockerignore file, and detailed instructions on how to build and run the Docker container.

## Project Overview

The Helpdesk app is a simple Angular application that has been containerized using Docker. This allows the application to be easily deployed and run in any environment that supports Docker.

## Features

- **Custom Dockerfile**: Defines the steps to build and run the Angular app within a Docker container.
- **.dockerignore**: Specifies files and directories to exclude from the Docker image, optimizing the build process.
- **Production-ready**: The application is configured for production with efficient build and environment settings.

## Docker Image

The Docker image for this project is available on Docker Hub:

[helpdesk.app Docker Image](https://hub.docker.com/repository/docker/omartamer12/helpdesk.app/general)

## Getting Started

### Prerequisites

- Docker installed on your local machine
- Node.js and Angular CLI installed if you want to run the app outside of Docker

### Clone the Repository

```bash
git clone https://github.com/omartamer630/Dockerized-Angular-App.git
cd Dockerized-Angular-App
