# GESTION-RESERVA ⚡
> Microservicio autónomo desarrollado con **Quarkus 3.15 LTS** y **Java 21**.
> Equipo responsable: **Logistica** | Grupo: `com.empresa.gestionreserva`

---

## 📋 Resumen del Microservicio
Desarrollar un microservicio encargado de registrar, consultar y actualizar el estado de los pedidos de una tienda en línea, coordinando la validación del cliente y notificando eventos asíncronos para el inventario y facturación.

* **Enfoque de diseño:** Contract-First (OpenAPI 3.1 congelado).
* **Patrón Arquitectónico:** HEXAGONAL.
* **Base de datos:** PostgreSQL.
* **Seguridad:** JWT (SmallRye JWT).
* **Modo de Generación:** Medio.

---

## 🚀 Arranque Rápido en Modo Desarrollo
Para iniciar el microservicio con recarga en caliente (*Live Coding* de Quarkus):

```bash
./mvnw quarkus:dev
```

* **Swagger UI / OpenAPI:** `http://localhost:8080/q/swagger-ui`
* **Quarkus Dev UI:** `http://localhost:8080/q/dev`
* **Health Probes:** `http://localhost:8080/q/health`
* **Métricas Prometheus:** `http://localhost:8080/q/metrics`

---

## 🧪 Ejecución de Pruebas Unitarias e Integración
```bash
./mvnw test
```
