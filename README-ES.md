# Eventos Santiago - Proyecto de Programación Web Avanzada - Noviembre de 2021

## Hecho por

- Audric Rosario
- Zheng Peng Li

### Presentación

[![Eventos Santiago – Proyecto de Programación Web Avanzada](http://img.youtube.com/vi/tw6RCLD3xQA/0.jpg)](https://www.youtube.com/watch?v=tw6RCLD3xQA&ab_channel=AudricRosario "Eventos Santiago")

En este proyecto, se implementa una arquitectura de microservicios con el motivo de crecer de forma horizontal, para garantizar alta disponbilidad y rendimiento.

Para lograr esto, se utilizan los recursos de Spring Boot Cloud.

### Características

- Springboot v2.5 (Backend) (Aplicación)
  - Instancias (3 de cada uno):
    - Base Usuario
    - Base Compra
    - Base Notificaciones
- Spring Cloud Gateway (Enrutamiento dinámico)
- Spring Cloud Netflix Eureka Server (Balanceador de carga)
- Spring Boot Actuator (Monitoreo de instancias de la aplicación)
- Spring Cloud Config Server (Centralización de la configuración de la instancias)
- Base de datos MySQL Server
- Java Web Token (JWT)
- Java Mail API
- Docker
  - Configuración: Docker Compose

### Diseño del Proyecto

![Diseño del proyecto](readme/0-project-design.png)

### Página Principal

![Página principal 1](readme/1-main-page.png)

![Página principal 2](readme/2-main-page-2.png)

### Inicio de sesión

- Inicio

  ![Inicio de sesión](readme/3-login.png)

- Registro

  ![Registro de usuario](readme/4-signup.png)

- Correo de registro exitoso

  ![Registro exitoso](readme/5-mail-successful-signup.png)

- Página principal después de iniciar sesión

  ![Página luego de inicio](readme/6-main-page-signup.png)

### Vistas del cliente

- Tienda

  ![Tienda](readme/7-shop-client.png)

- Historial de compra

  ![Historial](readme/8-client-history.png)

- Facturación

  ![Factura](readme/9-billing.png)

- Perfil de usuario

  ![Perfil de usuario](readme/10-profile.png)

### Vistas del administrador

- Dashboard

  ![Dashboard](readme/11-admin-dashboard.png)

- Control de usuarios

  ![Control](readme/12-admin-user-control.png)

  Cambio de datos del usuario

  ![Cambio](readme/13-change-user.png)

  Cambio de autoridad de usuario

  ![Autoridad 1](readme/14-authority.png)

  ![Autoridad 2](readme/15-authority-changed.png)

  Eliminar usuario

  ![Eliminar usuario](readme/16-delete-user.png)

- Órdenes de compra

  ![Órdenes de compra](readme/17-orders.png)

- Historial de ventas

  ![Historial de ventas](readme/18-sales-history.png)

### Preparación de microservicios

- Levantar servidores con docker compose, desde "api-gateway.yml"

  ![Docker Compose](readme/19-setting-up-microservices.png)

  ![Microservicios arriba, Docker UI](readme/20-microservices.png)
