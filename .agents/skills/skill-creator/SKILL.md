---
name: skill-creator
description: Habilidad especializada en la creación, documentación y despliegue de nuevas capacidades (skills) dentro del workspace de Antigravity, asegurando que sigan el formato técnico oficial y utilicen el español como idioma principal para instrucciones y metadatos.
---

# Creador de Habilidades en Español

Esta habilidad permite al asistente generar nuevas capacidades de forma estructurada y profesional dentro del entorno de Antigravity.

## Metodología de Creación

Para crear una nueva habilidad, sigue estos pasos:

1. **Definición del Alcance:** Identifica qué tarea específica o flujo de trabajo automatizará la nueva habilidad.
2. **Estructura de Carpetas:** Crea un nuevo directorio en `.agents/skills/` con un nombre descriptivo en minúsculas y separado por guiones (kebab-case).
3. **Escritura del Archivo:** Genera el archivo `SKILL.md` dentro de la carpeta creada.
4. **Validación:** Asegúrate de que el YAML frontmatter sea válido y que las instrucciones sean claras.

## Estándar de Formato

Todas las habilidades deben seguir este formato de Markdown con YAML:

```markdown
---
name: nombre-de-la-habilidad
description: Breve descripción de lo que hace (en español).
---

# Título de la Habilidad

Instrucciones detalladas de cómo el asistente debe comportarse cuando esta habilidad está activa.
```

## Guía de Estilo (Español)

- **Tono:** Profesional, técnico y directo.
- **Voz:** Utilizar la voz activa y el imperativo para instrucciones claras.
- **Terminología:** Utilizar términos técnicos estándar en español (ej. "implementación" en lugar de "deployment", si aplica el contexto).

## Procedimiento de Despliegue

Siempre que se cree una habilidad, informa al usuario sobre la ruta del archivo y un breve resumen de las nuevas capacidades adquiridas por el asistente.
