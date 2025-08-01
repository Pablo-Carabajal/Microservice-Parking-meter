# 🅿️ Sistema de Parquímetro - Microservicios

Este proyecto implementa una arquitectura de microservicios para gestionar un sistema de parquímetros inteligentes.

## 🔧 Microservicios principales

- **config-server**: Configuración centralizada.
- **discovery-server (Eureka)**: Registro y descubrimiento de servicios.
- **gateway-server**: Entrada única con control de rutas y seguridad.
- **usuario-service**: Gestión de usuarios.
- **parqueo-service**: Control de espacios de estacionamiento.
- **pago-service**: Procesamiento de pagos.
- **notificacion-service**: Envío de mensajes por correo o WhatsApp.
- **reportes-service**: Generación de reportes.

## ☁️ Tecnologías utilizadas

- Spring Boot / Spring Cloud
- Spring Config
- Eureka
- Gateway
- Feign Client
- Spring Security
- Keycloak (OAuth2)
- RabbitMQ (mensajería)
- Spring Bus (actualización de config en caliente)
- Vault (manejo de secretos)
- JPA + MySQL
- Resilience4j (tolerancia a fallos)
- Actuator (monitorización)

> Proyecto en desarrollo por Pablo Ezequiel Carabajal.
