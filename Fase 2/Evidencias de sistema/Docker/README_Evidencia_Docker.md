# RivalMatch — Contenedores en entorno local

En Fase 2 se contempla PostgreSQL en contenedor Docker para que el entorno sea reproducible.

Los archivos Dockerfile y compose.yaml en el repositorio original son ejemplos breves y NO demuestran despliegue funcional. Para ejecutar se necesita contrastarlos con los servicios reales y sus variables de entorno sin incluir contraseñas.

**Validación requerida:** `docker ps`, levantamiento controlado del servicio, conexión del API a PostgreSQL y registro fechado de éxito/fracaso. No declarar deploy público.
