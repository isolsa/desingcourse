# Contexto para asistentes de IA

Este documento resume el proyecto para que un copiloto o modelo de IA
(Claude, ChatGPT u otro) genere respuestas alineadas con él. Léalo
completo antes de proponer o escribir código.

## Objetivo del proyecto

**Diseñador de Cursos** es una aplicación web potenciada por IA que
convierte una idea en el diseño completo de un curso para el equipo de
educación continua de una universidad, reúne en una biblioteca tanto
los diseños nuevos como los cursos ya diseñados por docentes y
facultades, y permite combinar cursos y módulos existentes para armar
nuevos cursos con una ruta de aprendizaje coherente.

El detalle de funcionalidades y límites está en `docs/alcance.md`.

## Stack técnico

- **HTML5** para la estructura.
- **CSS3** para los estilos, sin frameworks.
- **JavaScript** puro (sin frameworks ni librerías) para la interacción.
- Sin backend en esta etapa: la aplicación corre abriendo `index.html`
  en el navegador.
- La integración con el servicio de IA y el almacenamiento de la
  biblioteca están por definir. No asuma ninguno: pregunte antes de
  proponer uno.

## Reglas de estilo de código

- **Idioma:** textos de la interfaz, comentarios y documentación en
  español. Nombres de variables, funciones y archivos de código en
  inglés. Los archivos de documentación pueden ir en español (por
  ejemplo, `docs/alcance.md`). Ningún nombre lleva tildes ni eñes.
- **Nombres:** `camelCase` para variables y funciones de JavaScript,
  `kebab-case` para archivos, clases e identificadores de CSS.
- **Indentación:** 2 espacios, sin tabuladores.
- **HTML:** semántico (`header`, `main`, `section`, `footer`), con
  etiquetas `label` en todos los campos de formulario y atributo `lang="es"`.
- **CSS:** en archivos separados, no en línea. Diseño adaptable a
  celular y computador.
- **JavaScript:** `const` y `let`, nunca `var`. Funciones cortas con un
  solo propósito. Sin dependencias externas salvo que se pida.
- **Comentarios:** solo para explicar el porqué de una decisión, no lo
  que el código ya dice.

## Vocabulario del proyecto

Use siempre estos términos, con este significado:

- **Idea:** descripción inicial del curso que ingresa el equipo.
- **Diseño:** documento con los ocho componentes del curso
  (justificación, público objetivo, resultados de aprendizaje,
  contenidos por módulo, metodología, evaluación, duración y
  presupuesto).
- **Módulo:** unidad de contenido de un curso; es la pieza que se
  reutiliza.
- **Biblioteca:** conjunto de diseños generados y cursos cargados.
- **Curso existente:** curso ya diseñado por un docente o facultad,
  cargado a la biblioteca.
- **Enriquecimiento:** mejora opcional de un curso existente con IA.
- **Ruta de aprendizaje:** secuencia coherente de módulos que forma un
  curso nuevo.

## Reglas para la IA

- No proponga funcionalidades que estén en los límites de
  `docs/alcance.md` (producción de contenidos, matrículas, pagos, LMS,
  certificados).
- Al enriquecer un curso existente, nunca sobrescriba el original:
  la versión enriquecida se guarda aparte.
- Todo lo que genere la IA dentro de la aplicación debe presentarse
  como propuesta que el equipo revisa y aprueba.
- Haga cambios pequeños y explique qué archivo modifica y por qué.
- Si falta información para decidir, pregunte en vez de suponer.
