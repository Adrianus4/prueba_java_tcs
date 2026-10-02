# 🛠️ Guía de Operación y Puesta en Producción (gestion-reserva)

## Variables de Entorno Clave
* `QUARKUS_HTTP_PORT`: Puerto HTTP (por defecto `8080`).
* `QUARKUS_DATASOURCE_JDBC_URL`: Cadena de conexión a base de datos.
* `QUARKUS_DATASOURCE_USERNAME`: Usuario de BD.
* `QUARKUS_DATASOURCE_PASSWORD`: Contraseña de BD.

## Despliegue en Kubernetes / Docker
```bash
# Construir imagen Docker JVM
docker build -f src/main/docker/Dockerfile.jvm -t gestion-reserva:latest .

# Ejecutar localmente
docker run -i --rm -p 8080:8080 gestion-reserva:latest
```
