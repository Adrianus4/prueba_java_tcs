# 📖 Catálogo de Endpoints de la API (gestion-reserva)
Generado a partir del contrato **OpenAPI 3.1** aprobado por **Logistica**.

## Matriz de Operaciones REST

| Método HTTP | Ruta / Endpoint | Descripción / Resumen |
|:-----------:|:----------------|:----------------------|
| `GET` | `/reservas` | Listar reservas |
| `POST` | `/reservas` | Crear una nueva reserva |
| `GET` | `/reservas/{id}` | Obtener reserva por ID |
| `PUT` | `/reservas/{id}` | Actualizar estado de reserva |

---

## Observabilidad y Diagnóstico de Fábrica
* **Liveness Probe:** `GET /q/health/live` (Indica si el contenedor está vivo).
* **Readiness Probe:** `GET /q/health/ready` (Valida conexión a base de datos y dependencias).
* **Prometheus Metrics:** `GET /q/metrics` (Métricas de runtime JVM, latencia y throughput).
* **OpenAPI 3.1 Spec:** `GET /q/openapi` (Especificación en JSON/YAML).
