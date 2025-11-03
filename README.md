# Evaluación DevOps - Pipeline CI/CD

Este proyecto contiene un microservicio de ejemplo con su ciclo de vida completamente automatizado mediante GitHub Actions.

## Componentes del pipeline

- **Dockerfile**: conteneriza el microservicio.
- **GitHub Actions**: construye imagen, ejecuta tests, hace análisis de seguridad y despliegue.
- **Dependabot y Snyk**: escanean dependencias y vulnerabilidades.
- **Despliegue**: con `docker-compose` como entorno cloud simulado.
- **Orquestación**: el `docker-compose.yml` asegura el funcionamiento completo del servicio.

## Trazabilidad

Cada cambio en `main` activa automáticamente el pipeline. Todos los pasos quedan registrados como evidencia de cumplimiento de calidad.

## IA utilizada

Este documento fue asistido parcialmente con herramientas de IA para generar archivos base del pipeline, los cuales fueron revisados y ajustados por el equipo.
