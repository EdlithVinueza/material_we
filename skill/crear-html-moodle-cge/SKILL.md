---
name: crear-html-moodle-cge
description: Crea y corrige los fragmentos HTML de asignaturas CGE para Moodle en la carpeta PARA CREAR HTML. Úsala para adaptar las plantillas institucionales al piloto o a otros cursos con PEA, sílabo y guías, y resolver diferencias entre el HTML local y su visualización en Moodle.
---

# HTML de asignaturas CGE para Moodle

Usa la [estructura base CGE](../../Organizacion_HTML_Plantillas_CGE/CARRERA/), los [documentos académicos seleccionados](../../LEEME.md) y el [curso VENDIG-P1-04](../../VENDIG-P1-04%20-%20Psicolog%C3%ADa%20del%20consumidor%20digital%2C%20Pensamiento%20cr%C3%ADtico%20y%20comunicaci%C3%B3n%20para%20ventas/) como referencias locales. El archivo base correspondiente manda sobre el ejemplo rellenado del piloto. Mantén las modificaciones dentro del curso solicitado.

## Correcciones acordadas

### Estructura y contenido académico

1. Conserva la forma de cada plantilla. Respeta el orden de los bloques, tarjetas y acordeones, y la cantidad, el nivel y la posición de los encabezados. Sustituye los datos de ejemplo por los de la materia en los campos correspondientes. Mantén las imágenes, los mensajes y los rótulos originales que el usuario haya indicado conservar. Las capturas orientan la disposición y la plantilla local define el HTML base.
   - Conserva el texto exacto, los iconos y el estilo de los botones de la plantilla correspondiente. Al recibir una URL definitiva, sustituye solo el destino del botón. Si el usuario solicita un cambio de rótulo o aspecto, aplícalo al botón indicado.
2. Entrega un fragmento HTML por bloque de Moodle, apto para pegar en modo **Código HTML**. Usa la estructura y los estilos en línea de la plantilla. Limita el fragmento al contenido del bloque y deja las pestañas, el índice lateral y los controles de edición a cargo de Moodle. Los índices locales sirven para abrir los archivos del proyecto.
3. Reutiliza la bienvenida común acordada. Para el contenido de cada materia, toma del PEA los títulos, el orden y los resultados. Coteja la secuencia y la evaluación con el sílabo. Usa la guía didáctica para las consignas y la guía práctica para el procedimiento, la evidencia y la rúbrica. Integra el material de estudio y los H5P correspondientes cuando estén disponibles. Conserva el trabajo autónomo y el práctico-experimental previstos por unidad.
4. Coloca las unidades 1 y 2 en el primer bisemestre y las unidades 3 y 4 en el segundo. En el piloto corresponden a las semanas 1 a 4 y 5 a 8. Conserva los nombres de carpeta y la denominación **Bimestre** donde la use la plantilla.
5. Deja pendientes los datos docentes y los destinos de Moodle que falten, como correo, hoja de vida, videos, tutorías, entregas y recursos. La columna **Asignado** del seguimiento identifica al responsable de preparación. Usa en el aula los datos docentes confirmados. Si un vínculo de ejemplo apunta a otra materia, deja pendiente el destino real. Si el usuario indica conservar una referencia de imagen para cargarla después, mantén el valor original y registra la carga como pendiente.

### Instituto CGE y Soporte

6. En **Instituto CGE**, coloca el saludo del rector como primer contenido, con un solo reproductor, seguido de los acordeones y accesos institucionales de la plantilla. Usa la inserción original. Un segundo enlace al mismo video puede convertirse en otro reproductor en Moodle.
7. Conserva **soporte.html** como bloque independiente, debajo del contenido institucional y encima de **Avisos**. Usa el recuadro y los botones de WhatsApp y Tutoriales de la plantilla. Conserva el título únicamente en la posición que tiene dentro de la tarjeta original. Para mostrar el recuadro dentro de la pestaña usa **Área de texto y medios**, llamada **Etiqueta** en algunas versiones.
8. La flecha **Antes de empezar ▸** pertenece a la navegación entre secciones de Moodle. Si el curso usa **Temas en pestañas**, se configura en **Configuración → Formato de curso → Usar navegación en secciones → En la parte superior e inferior de la sección**. Comprueba que **Antes de empezar** esté visible e inmediatamente después de **Instituto CGE**.

### Antes de empezar

9. Crea **01_Antes_de_empezar/Antes_de_empezar.html** a partir del archivo homónimo de la plantilla. Va como primer bloque de la sección, encima de Bienvenida. Conserva literalmente el mensaje original y el bloque de imagen con su referencia. Rellena la carrera y el título de la asignatura directamente en el HTML para que se vean aunque Moodle filtre el script de la plantilla. Reserva la carga de la imagen para después, según lo indicado. El archivo preexistente **00_Banner_Portada.html** puede permanecer como referencia. Monta una sola portada en la sección.
10. Mantén estos ocho apartados en archivos HTML independientes, en el orden de la captura. **Bienvenida**, **Datos generales**, **Ruta de aprendizaje**, **Enlace de tutorías**, **Cronograma de actividades**, **Rúbricas de evaluación**, **Evaluación diagnóstica** y **Bibliografía**. En Datos generales conserva los acordeones y la posición que tienen los accesos a las guías en la plantilla. Completa los enlaces de descarga cuando estén disponibles.
11. En Moodle crea un **Área de texto y medios** por archivo, incluida la portada, para mostrar los bloques uno debajo de otro en la misma pestaña. Usa **Nombre** para identificar el bloque en el índice y pega su fragmento en **Código HTML**. Usa **Cuestionario** si se solicita registrar respuestas o intentos de la evaluación diagnóstica. Usa **Página** cuando el usuario quiera que el contenido se abra en una pantalla aparte.

12. En **Enlace de tutorías**, conserva la tabla y el botón de la plantilla. Etiqueta a la persona como **Docente** y usa su nombre y apellidos confirmados. En **Mail**, **Teléfono** y **Horario Tutorías**, escribe exactamente **---** cuando el dato esté pendiente. Completa el correo y el celular ecuatoriano si una fuente los atribuye al mismo docente. Toma el día y la hora de la tutoría de la fila y columna de la asignatura, su PAO y módulo en el horario suministrado, diferenciándolos de las franjas generales, clases y gestión académica. Muestra el día y el intervalo en formato de 24 horas, sin indicar la zona horaria. Conserva el enlace original de Teams como provisional cuando así se indique.

13. En **Rúbricas de evaluación**, conserva la tabla, los rótulos y los estilos de la plantilla. Completa las descripciones y los instrumentos con la tabla de evaluación del PEA en Word y coteja su apartado en Markdown. Usa la ponderación confirmada de la asignatura. Si el PEA deja sin definir la ponderación de un bimestre, aplica **60 % y 6.00 puntos** a Socioformativas y **40 % y 4.00 puntos** a Examen Parcial o Actividad Sumativa (Examen Final), con **100 % y 10.00 puntos** de total en ese bimestre. Mantén la comprobación integrada cuando así la defina el PEA.

### Bloques de cada unidad

14. En **Actividades interactivas**, conserva el encabezado de la plantilla y crea un HTML independiente únicamente por cada H5P que el usuario comparta para esa unidad. Usa un desplegable con un emoji según el tipo y un rótulo que describa la actividad. Para **Arrastra y suelta** usa 🖐️ y para **Orden correcto** usa 🔢. Conserva el enlace de inserción del H5P compartido y limita la carpeta y el índice a esas actividades confirmadas.

15. En la Unidad 1 del curso VENDIG-P1-04, guarda las descripciones HTML de las dos tareas de Moodle en [Recursos de la asignatura](../../VENDIG-P1-04%20-%20Psicolog%C3%ADa%20del%20consumidor%20digital%2C%20Pensamiento%20cr%C3%ADtico%20y%20comunicaci%C3%B3n%20para%20ventas/02_Bimestre_1/03_Unidad_1/07_Actividad_autonoma/Recursos_de_la_asignatura/Unidad_1/), dentro de `07_Actividad_autonoma`. Prepara primero los HTML de Trabajo autónomo y Trabajo práctico-experimental. Luego, enlaza las vistas locales desde las tarjetas de `actividad_autonoma.html` y desde el índice del piloto. En Moodle, sustituye los enlaces de vista local por las URL de las dos Tareas. El bloque `06_Recursos_adicionales` va antes de Actividad autónoma y conserva su propio HTML.

16. En las descripciones de las tareas de cada unidad, dirige la consigna al estudiante con instrucciones directas sobre qué hacer, qué entregar y cómo hacerlo. Conserva los datos del caso necesarios para resolver la actividad y reserva las notas de coordinación y los campos de calificación docente para sus espacios de Moodle. En los HTML de Trabajo autónomo y Trabajo práctico-experimental, pon en negrita el encabezado y el nombre completo de la actividad.

17. En el bloque **Objetivos** de cada bimestre, deja **Objetivos Específicos** desplegado por defecto con `<details open="open">`. Muestra cada unidad en orden, con su número y título en negrita, seguidos de su objetivo específico y de su resultado de aprendizaje en párrafos separados. Toma el título, el objetivo y el resultado propio de cada unidad del PEA.

## Verificación antes de entregar

- Compara cada fragmento con su archivo base. Verifica los encabezados, los componentes, los datos de la materia y el estado de los vínculos. Comprueba que el contenido de ejemplo se haya sustituido en los campos pertinentes.
- Comprueba los archivos guardados en la ruta exacta del piloto y los enlaces de los índices locales. Soporte debe coincidir con la tarjeta de la plantilla. Instituto CGE debe tener un solo reproductor. El índice de Antes de empezar debe enlazar la portada antes de Bienvenida.
- Si Visual Studio Code muestra una versión anterior, comprueba primero la ruta y el contenido en disco. Corrige el archivo si volvió a una versión antigua. Si el archivo guardado ya es el correcto, abre la ruta exacta o recarga la pestaña tras conservar cualquier edición pendiente. Indica en la entrega si la comprobación se limitó a los HTML locales.
