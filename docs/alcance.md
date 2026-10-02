# Alcance del proyecto: Diseñador de Cursos

## Problema que resuelve

Diseñar un curso en educación continua toma mucho tiempo y depende de
pocas personas. Cada diseño se empieza casi desde cero, los cursos que ya
diseñaron docentes y facultades quedan dispersos en archivos sueltos con
formatos distintos, y sus módulos rara vez se reutilizan para armar
nuevas ofertas.

El Diseñador de Cursos convierte una idea en un diseño completo con
ayuda de IA, reúne todos los cursos de la institución en una sola
biblioteca y permite combinar sus módulos para crear nuevos cursos.

## Usuario objetivo

**Usuario principal:** el equipo de educación continua de una
universidad (coordinadores y diseñadores de la oferta de cursos,
talleres y diplomados).

**Usuarios indirectos:** docentes y facultades, cuyos cursos ya
diseñados entran a la biblioteca.

## Funcionalidades principales (MVP)

1. **Ingreso de la idea:** un espacio donde el equipo describe la idea
   del curso e indica su duración (por ejemplo, un taller de 8 horas o
   un diplomado de 120), para que la IA ajuste el número de módulos y
   el presupuesto.
2. **Diseño con IA:** la aplicación genera el diseño completo del curso
   a partir de esa idea, con ocho componentes: justificación, público
   objetivo, resultados de aprendizaje, contenidos por módulo,
   metodología, evaluación, duración y presupuesto.
3. **Ingreso de cursos existentes:** el equipo carga cursos ya diseñados
   por docentes o facultades de la institución.
4. **Enriquecimiento con IA (opcional):** la IA puede completar o
   mejorar un curso cargado, por ejemplo redactando los componentes que
   le falten. La aplicación conserva el curso original y el equipo
   decide si acepta los cambios.
5. **Biblioteca de cursos:** los diseños generados y los cursos
   cargados quedan en una misma biblioteca, organizados por módulos.
6. **Armado modular (tipo LEGO):** el equipo combina cursos y módulos
   de la biblioteca para crear nuevos cursos.
7. **Coherencia de la ruta:** la IA ordena los módulos combinados y
   señala vacíos o repeticiones, para que formen una ruta de
   aprendizaje coherente.

## Límites (fuera de esta primera versión)

1. **No produce los contenidos:** entrega el diseño del curso, no los
   videos, guías, presentaciones ni actividades.
2. **No publica ni vende:** no hace mercadeo, inscripciones, matrículas
   ni pagos.
3. **No es una plataforma de aprendizaje:** los cursos no se dictan
   ahí; para eso está el LMS (Moodle u otro).
4. **No reemplaza la aprobación institucional:** el diseño sigue
   pasando por el comité, la facultad o quien deba aprobarlo.
5. **No certifica:** no emite certificados ni insignias.
6. **No reemplaza el criterio experto:** todo diseño generado o
   enriquecido por la IA requiere revisión del equipo y de un experto
   en el tema antes de usarse.
7. **El presupuesto es una estimación:** se calcula con las tarifas y
   costos que el equipo ingrese; no reemplaza el presupuesto oficial
   de la institución.
