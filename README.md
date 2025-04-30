# Photography Services Website - Advanced Web Programming Project - November 2021

## Made by

- Audric Rosario
- Zheng Peng Li

### This README is available in

- [English](README.md)
- [Spanish](README-ES.md)

### Presentation

[![Eventos Santiago – Advanced Web Programming Project](http://img.youtube.com/vi/tw6RCLD3xQA/0.jpg)](https://www.youtube.com/watch?v=tw6RCLD3xQA&ab_channel=AudricRosario "Eventos Santiago")

In this project, a microservices architecture is implemented to scale horizontally and ensure high availability and performance.

To achieve this we used Spring Boot Cloud Services.

### Features

- Springboot v2.5 (Backend) (App)
  - Instances (3 ea):
    - User Base
    - Purchase Base
    - Notification Base
- Spring Cloud Gateway (Dynamic Routing)
- Spring Cloud Netflix Eureka Server (Load Balancer)
- Spring Boot Actuator (Application Instance Monitoring)
- Spring Cloud Config Server (Instance Configuration Centralization)
- MySQL Server Database
- Java Web Token (JWT)
- Java Mail API
- Docker
  - Configuration: Docker Compose

### Project Design

![Project Design](readme/0-project-design.png)

### Main page

![Main page 1](readme/1-main-page.png)

![Main page 2](readme/2-main-page-2.png)

### Log in

- Log in

  ![Log in](readme/3-login.png)

- Sign Up

  ![Sign Up](readme/4-signup.png)

- Registration success email

  ![Registration success email](readme/5-mail-successful-signup.png)

- Home page after login

  ![Home page after login](readme/6-main-page-signup.png)

### Client Views

- Shop

  ![Shop](readme/7-shop-client.png)

- Purchases History

  ![Purchases History](readme/8-client-history.png)

- Billing

  ![Billing](readme/9-billing.png)

- User's profile

  ![User's profile](readme/10-profile.png)

### Admin Views

- Dashboard

  ![Dashboard](readme/11-admin-dashboard.png)

- User CRUD

  ![Control](readme/12-admin-user-control.png)

  Update user

  ![Update user](readme/13-change-user.png)

  Change authority

  ![Authority 1](readme/14-authority.png)

  ![Authority 2](readme/15-authority-changed.png)

  Delete User

  ![Delete User](readme/16-delete-user.png)

- Purchase Orders

  ![Purchase Orders](readme/17-orders.png)

- Sales History

  ![Sales History](readme/18-sales-history.png)

### Microservices

- Set up servers with Docker Compose, from "api-gateway.yml"

  ![Docker Compose running](readme/19-setting-up-microservices.png)

  ![Microservices up, Docker UI](readme/20-microservices.png)
