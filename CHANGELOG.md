# Registro de Cambios

Este archivo documenta todos los cambios notables en el proyecto de Plantilla de Componente VUCEM.

## [0.1.0] - 2025-03-19

### Añadido
- Estructura inicial del proyecto siguiendo patrones de Clean Architecture
- Implementación base de controlador, servicio y repositorio de Recurso
- Configuración básica de seguridad con JWT
- Configuración inicial para tests unitarios e integración
- Soporte para puntos de extensión a través de la clase PuntoExtension
- Configuración básica de OpenAPI para documentación de API
- Configuración inicial de resiliencia con Resilience4j
- Soporte para auditoría de entidades
- Plantillas de documentación en directorio docs
- Plantillas de issues para GitHub:
  - Reporte de Error
  - Solicitud de Documentación
  - Solicitud de Funcionalidad
  - Reporte de Vulnerabilidad de Seguridad
  - Deuda Técnica
- Configuración de enlaces de contacto para issues

### Modificado
- Mejora del README.md con instrucciones de uso
- Ampliación de la documentación de CI/CD con sección detallada de Variables y Secretos

### Seguridad
- Implementación inicial de filtro de autenticación JWT
- Configuración base para autorización de endpoints
- Plantilla para reporte confidencial de vulnerabilidades

### Técnico
- Estructura de proyecto Maven con dependencias básicas
- Configuración de propiedades para entornos de desarrollo
- Documentación detallada de variables y secretos requeridos para pipelines de CI/CD

## [0.0.1] - 2025-03-19

### Añadido
- Commit inicial
- Estructura básica de directorios del proyecto
- Configuración inicial de Maven (pom.xml)
- Implementación de clases base para la arquitectura hexagonal
- Estructura de paquetes según Clean Architecture:
  - Application
  - Domain
  - Infrastructure
  - Interfaces
- Archivos base de configuración de Spring Boot
- Migraciones iniciales de base de datos con Flyway
- Archivos README.md, LICENSE, CONTRIBUTING.md y CODE_OF_CONDUCT.md
- Configuración inicial de Docker y Kubernetes
- Scripts de utilidad para generación de componentes