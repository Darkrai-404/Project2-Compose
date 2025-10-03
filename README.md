# Project2-Compose - Jenkins CI/CD with Docker

## Overview
This repository contains Docker Compose configuration for running Jenkins with Docker-in-Docker capabilities for CI/CD automation.

## Architecture
- **Jenkins**: CI/CD automation server
- **Docker-in-Docker (DinD)**: Allows Jenkins to build and manage Docker images

## Prerequisites
- Docker Engine 20.10+
- Docker Compose 1.29+
- Linux Server (Ubuntu 20.04+)
- Minimum: 1GB RAM, 2 CPU cores, 10GB disk space

## Setup Instructions

### 1. Start the Services
```bash
docker-compose up -d
```

