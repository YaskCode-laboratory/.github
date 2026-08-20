# Reconocimientos YaskCode Laboratory

Los reconocimientos identifican cualidades específicas demostradas por proyectos del laboratorio mediante evidencia verificable.

| Concepto | Significado |
| --- | --- |
| GitHub Status Badge | Estado técnico automático, por ejemplo build o tests. |
| YaskCode Recognition | Reconocimiento institucional basado en evidencia. |
| GitHub Stars | Señal orgánica de interés de la comunidad. |
| Featured Project | Selección institucional integral de una experiencia especialmente valiosa. |
| Community Recognition | Futura capa basada en recepción pública. |

**Recognition ≠ Achievement oficial de GitHub.**
**Recognition ≠ calificación.**
**Recognition ≠ ranking.**
**Recognition ≠ GitHub Stars.**

## Catálogo V1

Los seis reconocimientos son independientes: no tienen niveles, puntos, jerarquías ni una distinción especial por obtenerlos todos.

### Engineering Quality

Reconoce prácticas coherentes de ingeniería en diseño, arquitectura, implementación y evolución técnica. Puede considerar requisitos claros, arquitectura o enfoque explicado, decisiones justificadas, implementación coherente, Pull Requests, mantenibilidad, trazabilidad, Project Passport o ADR cuando corresponde, y ausencia de problemas técnicos críticos conocidos sin documentar.

No se otorga automáticamente porque el código compile: requiere revisión humana.

### Documentation Excellence

Reconoce documentación que permite comprender, ejecutar, estudiar y mantener el proyecto. La evidencia puede incluir README, contexto, objetivo, arquitectura, instrucciones, tecnologías, testing, documentación técnica, Project Passport, ADR cuando corresponde, fuentes, autoría, uso de IA y enlaces funcionales.

Las comprobaciones automáticas son evidencia auxiliar; la decisión final es institucional.

### Testing & Quality

Reconoce evidencia consistente de verificación y calidad: tests relevantes, criterios de aceptación, ejecución reproducible, CI, corrección de fallos, métricas cuando son apropiadas, estrategia proporcional y limitaciones documentadas.

No exige el mismo testing para sistemas web, IA, ciencia de datos, simulaciones o sistemas distribuidos. Un workflow verde no basta por sí solo.

### Security Practices

Reconoce prácticas responsables de seguridad y privacidad: ausencia de secretos, `.gitignore` adecuado, dependencias revisadas, protección de credenciales, tratamiento responsable de datos, privacidad, riesgos, seguridad de IA cuando corresponde y decisiones documentadas.

Puede apoyarse en automatización, pero requiere revisión humana antes del otorgamiento.

### Open Education Ready

Reconoce proyectos preparados para ser recursos educativos abiertos. Requiere evaluación académica finalizada, revisión técnica, repositorio público, contexto educativo, documentación, autoría, consentimiento cuando corresponde, licencia, revisión de información sensible, fuentes, atribución, uso de IA declarado cuando corresponde y Publication Readiness completado.

Se relaciona con la [Política de educación abierta](OPEN_EDUCATION_POLICY.md), [Autoría y publicación](AUTHORSHIP_AND_PUBLICATION.md), [Política de licencias](LICENSE_POLICY.md) y el [Publication Readiness Checklist](../templates/PUBLICATION_READINESS_CHECKLIST.md). No se otorga mientras el proyecto siga privado durante el semestre.

### Project Passport Complete

Reconoce proyectos cuyo Project Passport conserva suficientemente la memoria técnica y académica: propósito, contexto, requisitos, decisiones, arquitectura, ADR cuando corresponde, riesgos, testing, métricas, evidencias, retrospectivas, resultados, fuentes, uso de IA, autoría, aprendizajes y condiciones de publicación.

“Complete” no significa llenar mecánicamente todos los campos: se aplica proporcionalmente a la naturaleza y complejidad del proyecto.

## Reconocimiento basado en evidencia

Todo reconocimiento debe responder: **¿por qué recibió este proyecto este reconocimiento?** La respuesta apunta a evidencia verificable desde repositorio, Pull Requests, GitHub Actions, tests, documentación, Project Passport, ADR, arquitectura, Sprint Reviews, evidencias técnicas, Publication Readiness o revisión del Tech Lead académico. No se aceptan afirmaciones sin evidencia razonable.

## Automatización y revisión humana

| Reconocimiento | Automatización potencial | Decisión final |
| --- | --- | --- |
| Engineering Quality | Baja | Humana |
| Documentation Excellence | Media | Humana |
| Testing & Quality | Alta para evidencia | Humana |
| Security Practices | Media/Alta para evidencia | Humana |
| Open Education Ready | Media | Humana |
| Project Passport Complete | Media | Humana |

Las comprobaciones pueden ser:

- **Manual:** requiere principalmente juicio técnico o educativo, como Engineering Quality.
- **Asistida:** herramientas comprueban parte de la evidencia, pero una persona decide, como Documentation Excellence, Testing & Quality, Security Practices y Project Passport Complete.
- **Objetiva auxiliar:** confirma existencia de README, tests, CI verde, señales de secretos, Project Passport, licencia o documentación.

**Automatización potencial ≠ otorgamiento automático.** Esta V1 no automatiza el otorgamiento ni crea workflows.

## Proceso de otorgamiento

**Proyecto elegible → evidencia disponible → revisión del reconocimiento → comprobaciones automáticas cuando existan → revisión humana → decisión → registro → publicación del reconocimiento**

El Tech Lead académico puede participar y la decisión se documenta. Un reconocimiento solo se muestra públicamente cuando la etapa académica correspondiente terminó, el proyecto puede presentarse públicamente, tiene autoría identificada, no expone información sensible y posee contexto suficiente. Algunos podrían evaluarse internamente durante el semestre sin mostrarse aún.

Un proyecto puede obtener varios reconocimientos, pero no se exige obtener los seis ni se calcula una puntuación total. Esto permite describir fortalezas reales —por ejemplo, documentación o testing— sin convertir el sistema en competencia.

## Relación con Featured Projects y GitHub Stars

Un **Featured Project** es una selección integral institucional; un **Recognition** representa una fortaleza específica verificable. Un Featured Project puede tener reconocimientos, y un proyecto con reconocimientos no necesariamente será Featured Project.

⭐ Las GitHub Stars muestran interés orgánico. No otorgan reconocimientos YaskCode, no aumentan su número, no sustituyen criterios técnicos ni afectan la evaluación académica. Su uso futuro se definirá en Community Recognition V1; no se implementan conteos ni GitHub API.

## Identidad visual futura

Posteriormente los reconocimientos podrán formar una colección visual de YaskCode Laboratory como insignias, iconos, sellos o tarjetas (“barajitas”). Cada pieza podría incluir símbolo, nombre, identidad del laboratorio y versión de colección. La apariencia puede evolucionar sin cambiar los criterios institucionales.

Referencias conceptuales, no diseños finales:

| Reconocimiento | Concepto iconográfico |
| --- | --- |
| Engineering Quality | Engranaje, arquitectura o compás técnico. |
| Documentation Excellence | Libro o documento. |
| Testing & Quality | Matraz, check o pruebas. |
| Security Practices | Escudo o candado. |
| Open Education Ready | Libro abierto, globo o compartir. |
| Project Passport Complete | Pasaporte, credencial o brújula. |

Esta V1 no elige colores ni crea imágenes, SVG o badges gráficos.

## Recursos

- [Catálogo estructurado](../recognitions/catalog.yml)
- [Plantilla de evidencia](../templates/RECOGNITION_EVIDENCE_TEMPLATE.md)
- [Plantilla de registro](../templates/RECOGNITION_RECORD_TEMPLATE.md)
- [Featured Projects](FEATURED_PROJECTS.md)
- [Project Passport](PROJECT_PASSPORT.md)
