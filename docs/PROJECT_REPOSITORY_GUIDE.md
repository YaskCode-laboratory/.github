# Guía de estructura de repositorio

No existe una estructura universal para los proyectos de YaskCode Laboratory. La estructura debe seguir al proyecto, no al revés.

## Base conceptual

```text
README.md
docs/
tests/                    # cuando corresponda
src/ o app/               # cuando corresponda
notebooks/                # cuando corresponda
data/                     # solo cuando sea apropiado y seguro
.github/workflows/        # CI/CD
.gitignore
```

Dentro de `docs/` pueden existir:

```text
PROJECT_PASSPORT.md
adr/
arquitectura/
evidencias/
```

Una aplicación web, un proyecto de IA, uno de ciencia de datos, una simulación o un sistema distribuido pueden necesitar estructuras diferentes. Evita almacenar datos sensibles, secretos o archivos generados innecesarios; documenta la decisión y usa un `.gitignore` apropiado.

Consulta el [Starter Kit](STUDENT_PROJECT_STARTER_KIT.md) para el flujo de inicio y [CI/CD y automatización](CI_CD.md) para la adopción proporcional de pipelines.
