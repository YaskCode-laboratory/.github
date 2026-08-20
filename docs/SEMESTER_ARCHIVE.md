# Archivo por semestres

## Propósito

El Archivo por semestres conserva la memoria de cohortes, asignaturas, tecnologías, procesos de ingeniería, aprendizajes y proyectos desarrollados en YaskCode Laboratory. Permite observar la evolución del laboratorio con una lógica de **memoria → evidencia → aprendizaje → reutilización responsable → conocimiento abierto**.

No sustituye a YaskCode Research: el archivo documenta experiencias educativas, proyectos y evidencias de ingeniería. La investigación científica formal, las publicaciones y la producción investigativa corresponden a **YaskCode Research**.

## Principio de privacidad

Durante el semestre, los repositorios pueden permanecer privados. No se publican nombres, usuarios, calificaciones ni información personal sin autorización; tampoco enlaces a repositorios privados, entregas parciales, errores académicos o evaluaciones individuales.

## Apertura posterior

Al finalizar un semestre, un proyecto podrá incorporarse al archivo público solo después de evaluación concluida, revisión técnica, Project Passport preparado, documentación adecuada, revisión de seguridad y dependencias, autoría identificada, consentimiento, licencia definida y preparación del repositorio. La publicación no es automática.

## Organización

La memoria se organiza de forma progresiva:

**Año → Período → Nivel académico → Asignatura → Cohorte → Proyectos seleccionados**

```text
2026
└── 2026-I
    └── Postgrado
        └── Sistemas Inteligentes
```

Consulta el [índice de semestres](semesters/README.md). Esta V1 evita niveles de carpetas innecesarios.

## Ciclo de vida del archivo

**Proyecto asignado → Repositorio privado → Planificación → Sprints → Revisión técnica → Testing y calidad → Entrega final → Evaluación → Preparación para apertura → Publicación seleccionada → Archivo del semestre → Recurso educativo abierto**

No todos los proyectos necesariamente llegan a publicación pública.

## Criterios de incorporación

Un proyecto puede incorporarse públicamente cuando exista evidencia razonable de:

- finalización académica;
- revisión técnica;
- documentación suficiente y testing apropiado;
- ausencia de secretos y revisión de datos sensibles;
- Project Passport actualizado;
- autoría, consentimiento y licencia;
- contexto educativo claro.

Las estrellas de GitHub no son un criterio principal de calidad. Esta V1 no implementa badges, votaciones, Community Choice ni rankings.

## Aprendizaje entre cohortes

El archivo ayudará a futuras cohortes a estudiar soluciones anteriores, decisiones arquitectónicas, prácticas de testing, errores y mejoras documentadas, tecnologías, retrospectivas y patrones de evolución a través de varios sprints. Los proyectos publicados son recursos educativos contextualizados, no soluciones perfectas.

## Relación con Project Passport y CI/CD

El **Project Passport** es la memoria de un proyecto: conserva decisiones y evidencias de una experiencia concreta. El **Archivo por semestres** es la memoria del laboratorio: organiza esas experiencias a través del tiempo sin duplicar el Passport.

Las evidencias de GitHub Actions —builds, tests, lint, calidad, Docker builds y correcciones— pueden contribuir a la trazabilidad del semestre. No se almacenan logs completos en este repositorio ni se automatiza aún su recopilación.

## Recursos relacionados

- [Índice de semestres](semesters/README.md)
- [Plantilla de resumen de semestre](../templates/SEMESTER_SUMMARY_TEMPLATE.md)
- [Plantilla de proyecto publicado](../templates/PUBLISHED_PROJECT_ENTRY_TEMPLATE.md)
- [Project Passport](PROJECT_PASSPORT.md)
- [Autoría y publicación responsable](AUTHORSHIP_AND_PUBLICATION.md)
- [Política de educación abierta](OPEN_EDUCATION_POLICY.md)
- [Política de licencias](LICENSE_POLICY.md)
- [CI/CD y automatización](CI_CD.md)
