---
title: Deployment
layout: default
parent: Backend
nav_order: 2
---

We deploy our application on Azure.
For this we use the following services:
- Azure App Service
- Azure Container Registry
- Azure Application Insight
- Azure Database PostgreSQL

The microservices are packed into a docker container each and started together via Docker Compose.
You find the respective file in the deployment folder.
It uses the 'proddockersecrets' profile of each Spring Microservice

---