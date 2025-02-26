# Banking Microservices

Este monorepo contiene dos microservicios que conforman un sistema bancario:

- **ms-cliente-persona**: Microservicio de gestión de clientes
- **ms-cuenta-movimiento**: Microservicio de cuentas y movimientos bancarios

## Descripción General

Sistema bancario basado en microservicios (Spring Boot, PostgreSQL) para la gestión de clientes, cuentas y operaciones bancarias. Usa Spring WebFlux para un enfoque asíncrono y reactivo que mejora la escalabilidad y la concurrencia.

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
