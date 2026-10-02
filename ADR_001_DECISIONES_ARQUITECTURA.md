# ADR-001: Decisiones de Arquitectura para gestion-reserva

## Estado
**APROBADO** por Logistica y el Agente Arquitecto.

## Contexto
El microservicio `gestion-reserva` requiere implementar las reglas de negocio descritas:
> "Desarrollar un microservicio encargado de registrar, consultar y actualizar el estado de los pedidos de una tienda en línea, coordinando la validación del cliente y notificando eventos asíncronos para el inventario y facturación."

## Decisiones Técnicas
1. **Patrón Arquitectónico:** Se seleccionó el patrón **HEXAGONAL**.
2. **Framework Base:** Quarkus 3.15 LTS (Java 21 LTS) por su optimización para microservicios y soporte nativo GraalVM.
3. **Persistencia:** Quarkus Hibernate ORM con Panache y migraciones automáticas con Flyway.
4. **Motor de Datos:** PostgreSQL.
5. **Seguridad:** JWT (SmallRye JWT).

## Consecuencias
* Alta mantenibilidad y aislamiento de capas.
* Compatibilidad con despliegues en contenedores Kubernetes de bajo consumo de memoria.
