---
title: Services
layout: default
parent: Backend
nav_order: 7
---

- common: Package that offers common functionality and configuration (security, exception handling etc) for all other subprojects
- e2e-test: Subproject that runs some tests when the docker compose setup is running


- gateway-server: Spring Cloud Gateway Server that is the entry point to the application at port 8080
- eureka-server: Discovery Client and Load Balancer


- auth-service: Offers functionality to register and manage user. Issues JWT after login
- event-service: Create and update events, register artists
- volunteer-service: Shift setup and volunteer registration
- ticket-service: Ordering and verifying tickets
- inventory-service: Storing items and inventory information
- email-service: Sending emails for tickets and contacting volunteer

---