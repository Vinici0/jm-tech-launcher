# Banking Microservices

Este monorepo contiene dos microservicios que conforman un sistema bancario:

- **ms-cliente-persona**: Microservicio de gestión de clientes
- **ms-cuenta-movimiento**: Microservicio de cuentas y movimientos bancarios

## Descripción General

Sistema bancario compuesto por microservicios desarrollados con Spring Boot y PostgreSQL que permite la gestión de clientes, cuentas y operaciones bancarias.

## Documentación API

La documentación completa de las APIs está disponible en Postman:

[Documentación API Bancaria](https://documenter.getpostman.com/view/19616580/2sAYdbPYVt#5535fd87-e5d5-4750-a150-16104e6d4cc4)

## Estructura

```
.
├── ms-cliente-persona/     # Gestión de clientes
├── ms-cuenta-movimiento/   # Gestión de cuentas y movimientos
└── .gitmodules
```

## Requisitos Básicos

- Java 17+
- Maven 3.8.x+
- Docker y Docker Compose

Para instrucciones detalladas de instalación, configuración y uso, consulte el README de cada microservicio.
