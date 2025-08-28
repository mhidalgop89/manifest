# Microservices Docker Setup

Este repositorio contiene un entorno Docker Compose para ejecutar:

- Base de datos MySQL con datos iniciales.
- Microservicio Clientes.
- Microservicio Cuentas.
- Postman-Collection para probar los endpoints.

## Tecnologías

- Docker y Docker Compose
- MySQL
- Java/Spring Boot (Clientes y Cuentas)
- Postman Collection

## Requisitos

- Tener Docker y Docker Compose instalados.
- Tener el puerto 3306 libre para la base de datos.

## Levantar la solución

Para levantar todos los servicios, simplemente ejecuta:

```bash
docker compose up
docker ps

mi-repo/
│
├─ docker-compose.yml
├─ clientes/         # Código del microservicio Clientes
├─ cuentas/          # Código del microservicio Cuentas
├─ db/               # Scripts para la base de datos MySQL
└─ README.md
