# CI/CD y automatización

## CI/CD en YaskCode Laboratory

**CI** integra cambios, construye, ejecuta pruebas y verifica automáticamente aspectos de calidad. **CD** prepara y automatiza la entrega o el despliegue cuando el proyecto y su contexto lo permiten.

Esta V1 implementa principalmente **CI** y deja una base para CD. No incluye despliegues reales, publicación de imágenes, credenciales ni infraestructura de producción.

## Relación con el Marco de Ingeniería YaskCode

CI/CD fortalece especialmente **Construir → Verificar → Compartir**: convierte validaciones repetibles en evidencia y ayuda a que los cambios lleguen a revisión con una base técnica común.

## Evidencias y Project Passport

Las ejecuciones de GitHub Actions pueden aportar evidencia sobre build, tests, lint, calidad, reproducibilidad, contenedores, fallos y correcciones. El equipo puede referenciarlas en el Project Passport; esta V1 no modifica el Passport automáticamente.

## Progresividad

Cada pipeline se adapta al nivel académico, asignatura, arquitectura, madurez, riesgos y tecnología del proyecto. No todos los proyectos necesitan el mismo flujo ni las mismas exigencias. Las plantillas son un punto de partida educativo, no una certificación obligatoria.
