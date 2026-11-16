# RivalMatch — Evidencia de base de datos (Fase 2)

**Modelo conceptual:** usuarios, equipos, membresías, encuentros, solicitudes, cupos, asistencia y evaluaciones. Ver «Modelo de datos.pdf».

## Tecnología prevista
PostgreSQL con Prisma ORM como acceso desde la API; instancia local de pruebas.

## Integridad a validar
- Pertenencia usuario-equipo y roles.
- Un encuentro no puede confirmar un rival inexistente.
- Solicitudes y asistencia deben referenciar entidades vigentes.
- Las consultas deben respetar permisos y contexto deportivo.

## Evidencias de ejecución pendientes
Exportar esquema exacto de Prisma correspondiente al periodo, registrar migraciones reales ejecutadas y adjuntar capturas o consultas de la BD tras pruebas verificadas. No se incluyen datos personales, claves ni un esquema SQL inventado.
