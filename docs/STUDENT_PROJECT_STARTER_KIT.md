# Student Project Starter Kit

Punto de partida para proyectos de YaskCode Laboratory. Este kit orienta cómo iniciar y organizar un proyecto sin convertir la metodología en una receta rígida.

**Construye · Aprende · Itera · Comparte** se traduce en **Diseñar → Construir → Verificar → Compartir** y se gestiona mediante **Backlog → Ready → In Progress → Review → Done**. Es adaptable a proyectos individuales o en equipo, de pregrado o postgrado, y no presupone una tecnología específica.

## Cómo comienza un proyecto

1. Proyecto o problema asignado.
2. Repositorio privado creado.
3. Lectura del objetivo y criterios de evaluación.
4. Inicialización del README.
5. Inicialización del Project Passport.
6. Identificación del contexto y requisitos.
7. Creación del Backlog.
8. Definición del primer Sprint.
9. Selección de CI/CD apropiado.
10. Inicio del trabajo mediante Issues, ramas y Pull Requests.

Los proyectos permanecen privados durante el semestre, salvo decisión institucional posterior y el proceso de publicación responsable.

## Trabajo con ramas

La rama principal se mantiene estable y protegida cuando corresponda. Se recomiendan ramas breves, con un propósito claro: `feat/`, `fix/`, `docs/`, `test/`, `refactor/` y `chore/`; `experiment/` puede usarse para experimentación técnica controlada.

Ejemplos: `feat/rag-retrieval`, `fix/vector-search`, `docs/project-passport`, `test/retrieval-evaluation`, `experiment/chunking-strategies`.

Estas convenciones no son requisito absoluto si una asignatura define otra estrategia.

## Pull Request workflow

**Issue → rama → implementación → pruebas → actualización documental → Pull Request → revisión → correcciones → aprobación → Squash and merge → eliminación de rama**

Un Pull Request representa una unidad de trabajo coherente. Usa el [template de Pull Request](../.github/PULL_REQUEST_TEMPLATE.md) para reunir objetivo, testing, seguridad, documentación, evidencias, Project Passport, autoría y uso de IA cuando corresponda.

## Matriz de adopción de CI/CD

| Proyecto | CI sugerido |
| --- | --- |
| Python | YaskCode · Python CI |
| Node / JavaScript / TypeScript | YaskCode · Node CI |
| Docker | YaskCode · Docker Build |
| Cualquier repositorio | YaskCode · Project Quality |

Las plantillas pueden combinarse cuando corresponda; no todos los proyectos necesitan todas. Consulta [CI/CD y automatización](CI_CD.md).

## Project Passport, ADR y aprendizaje

Cada proyecto usa el [Project Passport](PROJECT_PASSPORT.md) de forma proporcional y puede comenzar con su [plantilla](../templates/PROJECT_PASSPORT_TEMPLATE.md). Momentos naturales para actualizarlo: decisiones arquitectónicas, cambio importante de alcance, selección de tecnología, riesgo, experimento, resultado de testing, retrospectiva y preparación de publicación.

Un [ADR](../templates/ADR_TEMPLATE.md) es útil ante una elección arquitectónica significativa —por ejemplo, base de datos, framework, modelo, despliegue o integración externa— especialmente si es difícil de revertir. No hace falta crear uno para decisiones triviales.

La [Sprint Review](../templates/SPRINT_REVIEW_TEMPLATE.md) registra qué se construyó y qué evidencia existe; la [Retrospectiva](../templates/RETROSPECTIVE_TEMPLATE.md) identifica lo aprendido sobre el proceso y las mejoras siguientes. La [revisión técnica](../templates/TECHNICAL_REVIEW_CHECKLIST.md) ayuda a verificar una entrega sin sustituir el criterio del equipo.

## Tech Lead académico

El Tech Lead académico orienta, revisa decisiones, formula preguntas, revisa evidencias, ayuda a gestionar riesgos, supervisa calidad y promueve autonomía. No implementa el trabajo de los estudiantes: la responsabilidad técnica sigue perteneciendo al equipo, conforme a la [Gobernanza](../GOVERNANCE.md).

## Uso responsable de IA

GitHub Copilot, ChatGPT u otras herramientas pueden apoyar exploración, programación, testing, documentación, debugging y diseño. El equipo debe comprender el código, revisar resultados, validar fuentes, probar cambios, reconocer el uso de IA cuando corresponda y conservar responsabilidad sobre sus decisiones. “La IA lo generó” no sustituye la evidencia técnica.

## Seguridad desde el inicio

No subas archivos `.env`, claves, tokens ni credenciales cloud. Usa `.gitignore`, protege datos personales, revisa dependencias y revisa archivos antes de cada commit. Consulta la [política de seguridad](../SECURITY.md).

## Publicación

Completar este kit no implica hacer público un proyecto. Al finalizar el semestre, el recorrido es: **desarrollo terminado → evaluación → revisión técnica → [Publication Readiness Checklist](../templates/PUBLICATION_READINESS_CHECKLIST.md) → autoría → consentimiento → licencia → publicación seleccionada**.

El [Archivo por semestres](SEMESTER_ARCHIVE.md) conserva experiencias seleccionadas; no reemplaza la evaluación ni automatiza la apertura pública.
