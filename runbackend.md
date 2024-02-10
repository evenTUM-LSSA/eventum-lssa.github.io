---
title: Run
layout: default
parent: Backend
nav_order: 6
---

### Setup

You need to have **Docker** and **Java 17** installed to run this project.

1. Run `build-docker.sh all` on Linux or `build-docker.bat all` on Windows
2. Start the application with `docker compose up`

### Scripts

- docker-compose.yaml: docker compose for local deployment
- build-docker.sh / build-docker.bat: build subprojects and docker container
- deployment
  - docker_build_push.sh: builds subprojects, images and pushes them to Azure Container Registry
  - docker_push: assumes images are already built, tags them and pushes to Azure Container Registry
  - docker-compose-azure-prod.yml: docker compose for production deployment on Azure App Service

---