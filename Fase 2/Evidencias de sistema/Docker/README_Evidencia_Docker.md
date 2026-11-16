# RivalMatch — Evidencia de contenedores (Fase 2)

Esta carpeta documenta **el uso previsto de Docker en el entorno local** para PostgreSQL y componentes asociados. Los archivos `Dockerfile` y `compose.yaml` que estaban aquí eran ejemplos genéricos y se retiraron para evitar confundirlos con una configuración del proyecto probada.

## Qué se puede afirmar

- Se definió una arquitectura de prototipo con API, persistencia PostgreSQL y contenedores en un entorno de desarrollo local.
- La configuración ejecutable debe obtenerse del **repositorio real del código**, contrastando versiones, servicios y variables requeridas.
- Este documento, por sí solo, **no demuestra** que exista un despliegue reproducible o público.

## Evidencia requerida para validar

Registrar fecha y versión; `docker ps` con servicios operativos; inicialización de PostgreSQL; conexión de la API; salida de una consulta inocua o prueba de salud; y resultado real (correcto o con errores). Nunca subir secretos, archivos `.env` con contraseñas ni volcados con información privada.
