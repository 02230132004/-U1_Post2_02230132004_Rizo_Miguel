# Guía de Contribución al Proyecto

Este proyecto sigue un flujo de trabajo profesional con GitFlow y Conventional Commits.

## Convenciones de Commits (Conventional Commits)
Todos los mensajes de commit deben seguir este formato:


Tipos principales usados:
- **feat**: nueva funcionalidad
- **fix**: corrección de bug
- **docs**: cambios en documentación
- **chore**: tareas de mantenimiento (ej: bump version)
- **ci**: cambios en CI/CD (ej: workflows)
- **style**: cambios de formato sin afectar lógica

Ejemplos:
- feat(app): agregar pantalla de login
- docs(readme): actualizar instrucciones de instalación
- chore(release): preparar versión 1.0.0

## Proceso de trabajo
- Siempre crear rama desde **develop**:
  - feature/nombre-feature
  - release/1.0.0
  - hotfix/1.0.1
- Hacer commits descriptivos.
- Crear Pull Request a **develop** o **main**.
- Usar **Create a merge commit** para merges (simula --no-ff).
- Borrar rama después de merge.

## Estilo de código
- Para Android: seguir estándares de Kotlin/Java de Google.
- Mantener carpetas organizadas (app/src/main/...).

Gracias por contribuir.
