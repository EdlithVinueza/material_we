# GUÍA DE PRÁCTICAS — MODALIDAD EN LÍNEA

## INTRODUCCIÓN
Esta guía de prácticas desarrolla los cuatro Trabajos Práctico-Experimentales de la asignatura Lógica Matemática y Gestión de Datos de la carrera Desarrollo de Software, articulados paso a paso con las unidades temáticas de la Guía Didáctica. Cada práctica parte del caso aplicado presentado en la unidad correspondiente para transformarlo en un producto verificable mediante simulación, modelado formal o ejecución real de consultas dentro de una sola entrega asincrónica.

Los escenarios empresariales, reglas de negocio, registros de ejemplo y bases de datos señalados como ficticios se han diseñado exclusivamente con fines formativos y no representan organizaciones reales. En estas dos guías dispone de las definiciones, tablas base y procedimientos necesarios para ejecutar todas sus prácticas sin obligación de adquirir libros adicionales; las referencias bibliográficas listadas al final provienen del Programa de Estudio de la Asignatura y se consultan según los recursos que habilite su docente en Moodle.

## INFORMACIÓN DE LA ASIGNATURA
- NOMBRE_ASIGNATURA: Lógica Matemática y Gestión de Datos
- CARRERA: Desarrollo de Software
- NIVEL_SEMESTRE: Primer nivel
- MODALIDAD: En línea (virtual)
- UNIDAD_ORGANIZACION_CURRICULAR: Básica
- CAMPO_FORMACION: Por definir en el registro curricular institucional
- HORAS_DEDICACION_ESTIMADA: 144 horas totales: 48 horas de aprendizaje en contacto con el docente, 48 horas de aprendizaje práctico-experimental y 48 horas de aprendizaje autónomo, distribuidas en 8 semanas y 4 unidades temáticas de 2 semanas cada una.
- RESULTADOS_APRENDIZAJE_ASIGNATURA: Resuelve proposiciones simples y compuestas aplicando operadores booleanos, tablas de verdad y leyes de De Morgan para fundamentar condiciones en programación; clasifica y modela datos, tipos primitivos y estructuras lineales como listas, pilas de tipo último en entrar, primero en salir (LIFO), colas de tipo primero en entrar, primero en salir (FIFO) y registros; diseña modelos de tablas relacionales aplicando claves primarias, claves foráneas, relaciones de cardinalidad, integridad referencial y normalización básica hasta tercera forma normal; y formula consultas estructuradas en lenguaje de consulta estructurado (SQL) para seleccionar, filtrar, ordenar y contar información de bases de datos relacionales.
- DESCRIPCION_ASIGNATURA: La asignatura Lógica Matemática y Gestión de Datos articula las bases formales del razonamiento lógico-deductivo con los fundamentos de estructuración, modelado y consulta de datos en el desarrollo de software. A través de un enfoque integrado, el estudiante domina la lógica proposicional, las tablas de verdad, los operadores booleanos y las estructuras de datos fundamentales (listas, pilas, colas y registros). Posteriormente, traslada estos principios a la organización de información en tablas relacionales, comprendiendo el rol de las claves primarias y foráneas, la normalización básica y la formulación de consultas elementales mediante álgebra relacional y sentencias en lenguaje de consulta estructurado (SQL), tales como SELECT, WHERE y ORDER BY. Esta materia fortalece el rigor analítico indispensable para concebir algoritmos eficientes y diseñar esquemas de persistencia de información consistentes.

## 1. DATOS GENERALES DEL INSTRUMENTO
- INSTITUCION: Instituto Superior Tecnológico Consulting Group Ecuador (ISTCGE)
- MODALIDAD: En línea (virtual)
- CARRERA: Desarrollo de Software
- ASIGNATURA: Lógica Matemática y Gestión de Datos
- DOCENTE_AUTOR: 
- PERIODO_ACADEMICO: Primer nivel (las fechas de inicio y cierre serán comunicadas en Moodle según el calendario académico vigente)
- NUMERO_PRACTICAS: 4 prácticas articuladas con 4 unidades didácticas

## 2. ARTICULACIÓN CON LA GUÍA DIDÁCTICA
| UNIDAD_DIDACTICA | CASO_INTRODUCTORIO | PRACTICA_RELACIONADA | RESULTADO_ESPERADO |
| --- | --- | --- | --- |
| Unidad 1: Lógica proposicional, operadores y razonamiento lógico | En la plataforma ficticia *PagoAndes*, una regla booleana con negaciones mal agrupadas bloquea clientes válidos y aprueba solicitudes fuera de límite. | Práctica 1: Construcción de tablas de verdad y simplificación de expresiones lógicas (Trabajo Práctico-Experimental 1) | Formalización proposicional, tabla de verdad completa de ocho filas, simplificación algebraica mediante leyes de De Morgan y validación en simulador lógico web. |
| Unidad 2: Datos, información y estructuras de datos fundamentales | En la aplicación ficticia *FarmaRápida*, los desarrolladores usaron una pila para despachar pedidos y una cola para el historial Deshacer, invirtiendo el orden esperado por los usuarios. | Práctica 2: Diagramación y simulación paso a paso de pilas, colas y recorridos (Trabajo Práctico-Experimental 2) | Registros tipificados, trazas y diagramas paso a paso en simulador para pila, cola y lista con pruebas de límite y explicación oral asincrónica integrada. |
| Unidad 3: Organización de datos en tablas y relaciones del modelo relacional | La tienda virtual ficticia *MercadoSierra en Línea* gestiona sus ventas en una sola tabla plana con productos en listas de texto, direcciones repetidas y pérdida de datos al anular pedidos. | Práctica 3: Modelado del esquema de tablas relacionales para tienda virtual (Trabajo Práctico-Experimental 3) | Esquema relacional normalizado hasta tercera forma normal, con claves primarias, claves foráneas, cardinalidades e integridad comprobada con registros de prueba. |
| Unidad 4: Fundamentos de consultas y gestión de datos con SQL | La librería digital ficticia *LecturaViva* requiere seis reportes confiables sobre clientes, libros y pedidos tras detectar errores por falta de paréntesis y filtros defectuosos. | Práctica 4: Ejecución interactiva de consultas y filtrado de datos con SQL (Trabajo Práctico-Experimental 4) | Script SQL ejecutado en PostgreSQL o SQLite con proyección, filtros compuestos parentizados, ordenamiento, conteo básico y evidencias reales de salida. |

## 3. DESARROLLO DE LAS PRÁCTICAS

### PRÁCTICA 1: Construcción de tablas de verdad y simplificación de expresiones lógicas
- PRACTICA_UNIDAD:
  Práctica 1 — Correspondiente al Trabajo Práctico-Experimental de la Unidad 1. Antes de iniciar el taller, repase los operadores booleanos, tablas de verdad y leyes de De Morgan en la [Guía Didáctica, Unidad 1](../03_Guias_Didacticas_V2/GD_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md) y avance su Trabajo Autónomo 1.
- RESULTADOS_APRENDIZAJE:
  Identifica proposiciones simples y compuestas asignando valores de verdad según operadores booleanos; construye tablas de verdad para determinar si una proposición constituye una tautología, contingencia o contradicción; simplifica expresiones lógicas complejas utilizando leyes de De Morgan y equivalencias fundamentales; y traduce especificaciones de requerimientos en condiciones booleanas equivalentes aplicables al control de flujo en código.
- OBJETIVO_PRACTICA:
  Formalizar requerimientos de negocio en proposiciones compuestas, construir sus tablas de verdad completas, simplificar expresiones booleanas mediante leyes de De Morgan y comprobar su equivalencia funcional en un simulador lógico web.
- TIEMPO_ESTIMADO:
  12 horas de aprendizaje práctico-experimental asincrónico distribuidas en las semanas 1 y 2. Dedicación sugerida dentro de la misma actividad: análisis del requerimiento defectuoso y formalización de variables (2 horas), construcción de tablas de verdad completas y simplificación paso a paso en simulador web (6 horas), comprobación de equivalencias bajo condiciones normales, límite y de error (2 horas y 30 minutos), e integración del expediente y entrega final en Moodle (1 hora y 30 minutos). Suma total: 12 horas. Las lecturas y ejercicios del Trabajo Autónomo 1 permanecen dentro de sus 12 horas de aprendizaje autónomo.
- RECURSOS_DIGITALES_MATERIALES:
  Equipo informático con conexión a internet; aula virtual en Moodle; simuladores lógicos y de tablas de verdad en línea gratuitos (como Wolfram Alpha, Logic Friday o generadores interactivos de tablas booleanas y compuertas lógicas en navegador web); editor de diagramas o tabla en procesador de textos u hoja de cálculo; y, de modo opcional y declarado con transparencia, un asistente de inteligencia artificial (IA) para revisar pasos intermedios de demostración algebraica (verificando siempre cada una de las filas en su propia tabla).
- CASO_SITUACION_PROBLEMA:
  La plataforma financiera ficticia *PagoAndes* (caso simulado exclusivamente con fines formativos) recibió múltiples quejas porque su módulo automático de microcréditos está aprobando y rechazando mal las solicitudes. Al revisar el código del módulo, se detectó que la especificación oficial del negocio establece la siguiente **regla válida de aprobación**:

  > «Una solicitud se **aprueba** únicamente si el cliente tiene identidad verificada (*p*) y mantiene cero cuotas vencidas (*q*), o bien si tiene identidad verificada (*p*) y el monto pedido es menor o igual al límite autorizado (*r*).»

  Sin embargo, el programador anterior intentó escribir directamente la condición contraria (**regla de rechazo**) y programó la expresión defectuosa: *(NOT p) AND (NOT q) AND (NOT r)*. Además, escribió una segunda regla de verificación redundante que el equipo necesita comprobar si siempre se cumple (tautología) o si depende de las entradas.

  Su misión durante las semanas 1 y 2 consiste en formalizar la regla de aprobación, deducir y simplificar correctamente la regla de rechazo mediante las leyes de De Morgan, construir la tabla de verdad completa de ocho filas y validar en un simulador web exactamente en qué combinaciones fallaba el código anterior.
- ACTIVIDADES_PREVIAS:
  Repase en la Guía Didáctica las tablas básicas de negación, conjunción, disyunción, condicional y bicondicional, así como las dos leyes de De Morgan. Verifique que puede acceder en su navegador a un simulador lógico web gratuito (o utilice tablas paso a paso en hoja de cálculo si trabaja sin conexión continua, validando luego en línea).
- PROCEDIMIENTO_PASO_A_PASO:
  1. **Formalización de variables y proposición de aprobación (semana 1):** Declare explícitamente las tres proposiciones atómicas del caso *PagoAndes*: *p* (identidad verificada), *q* (cero cuotas vencidas) y *r* (monto dentro del límite). Escriba la fórmula booleana literal de aprobación: *(p AND q) OR (p AND r)* y factorícela aplicando equivalencia distributiva hacia *p AND (q OR r)*.
  2. **Evaluación inicial con dos variables y prueba de operadores:** Antes de la tabla completa, compruebe en un apartado breve los cinco operadores básicos tomando el caso de control *p = verdadero* y *q = falso*: verifique el valor resultante de *p AND q*, *p OR q*, *p implica q* y *p si y solo si q*, demostrando además mediante una tabla de dos filas por qué *p OR (NOT p)* es una tautología y *p AND (NOT p)* es una contradicción.
  3. **Construcción de la tabla de verdad completa de ocho filas (semana 2):** Elabore la tabla ordenada de las ocho combinaciones posibles de *(p, q, r)* evaluando columna por columna: la fórmula literal *(p AND q) OR (p AND r)*, su forma simplificada *p AND (q OR r)*, la negación real de rechazo *NOT (p AND (q OR r))* y la expresión defectuosa del programador *(NOT p) AND (NOT q) AND (NOT r)*.
  4. **Simplificación algebraica paso a paso:** Aplique explícitamente las leyes de De Morgan para transformar *NOT (p AND (q OR r))* en *(NOT p) OR ((NOT q) AND (NOT r))*, justificando cada transformación en una línea y comprobando en la tabla de verdad que ambas columnas coinciden fila por fila en las ocho combinaciones (equivalencia lógica demostrada).
  5. **Validación en simulador lógico y prueba de tres condiciones:** Ingrese ambas expresiones (la simplificada y la defectuosa) en el simulador lógico web elegido (por ejemplo, Wolfram Alpha o Logic Friday), tome capturas legibles y documente tres casos concretos sobre la tabla: (a) **condición normal de aprobación** (*p = verdadero, q = verdadero, r = falso*); (b) **condición límite** (*p = verdadero, q = falso, r = verdadero*, donde una variable falsa en el historial se compensa con monto permitido); y (c) **condición errónea crítica** (*p = verdadero, q = falso, r = falso*, demostrando que la expresión defectuosa del programador devolvía falso en el rechazo y dejaba pasar indebidamente una solicitud riesgosa).
  6. **Traducción a pseudocódigo de control de flujo:** Redacte en cuatro líneas de pseudocódigo limpio cómo debería quedar escrita la estructura condicional ("si ... entonces aprobar; si no, rechazar") dentro del sistema *PagoAndes* para eliminar por completo la ambigüedad.
- ENTREGABLE_EVIDENCIA:
  Un único archivo en formato editable o en formato de documento portátil (PDF), por ejemplo "Apellido_Nombre_Unidad1_Practica1.docx" o ".pdf", que integre:
  - Formalización de proposiciones atómicas, evaluación de control para dos variables y clasificación de tautología frente a contradicción.
  - Tabla de verdad completa de ocho filas comparando la regla literal, la forma factorizada, el rechazo correcto y el rechazo defectuoso de *PagoAndes*.
  - Derivación algebraica paso a paso con leyes de De Morgan, capturas legibles de verificación en simulador lógico web, análisis de las tres condiciones (normal, límite y error crítico) y pseudocódigo final corregido.
- FORMA_ENTREGA_EVALUACION:
  En la semana 1 se revisan formativamente en Moodle la formalización de variables y el avance inicial de tablas; al cierre de la semana 2 se entrega la versión definitiva única en el espacio asignado al Trabajo Práctico-Experimental 1. Será evaluada mediante la rúbrica analítica adjunta y la lista de cotejo correspondiente dentro del esquema de calificación vigente en Moodle para la carrera Desarrollo de Software.
- AUTOEVALUACION_REFLEXION:
  Al final de su documento, responda brevemente en un párrafo: ¿en qué combinaciones específicas fallaba la expresión defectuosa del programador de *PagoAndes* y por qué probar solo uno o dos ejemplos al azar habría ocultado ese error? ¿Qué ley de De Morgan fue clave para corregir la condición de rechazo?

#### RÚBRICA ANALÍTICA SUGERIDA
| CRITERIO | EXCELENTE_4 | BUENO_3 | EN_PROCESO_2 | INSUFICIENTE_1 | PUNTAJE |
| --- | --- | --- | --- | --- | --- |
| Pertinencia del análisis | Formaliza con exactitud el requerimiento de *PagoAndes*, localiza todas las filas donde falla el código anterior y redacta el control de flujo correcto. | Formaliza correctamente el caso e identifica el fallo principal con omisiones menores en la explicación del pseudocódigo. | Formaliza parcialmente las variables pero no delimita qué combinaciones exactas provocaban el error del caso. | No logra traducir la regla de negocio del caso a proposiciones lógicas ni identificar la falla. | /4 |
| Aplicación conceptual | Construye sin errores las ocho filas de la tabla de verdad, demuestra la simplificación con De Morgan y verifica equivalencia y tautología/contradicción. | Construye la tabla y simplifica adecuadamente con algún error puntual de paréntesis o en una sola columna intermedia. | Omite filas en la tabla de verdad o aplica incorrectamente las leyes de De Morgan al negar paréntesis. | Presenta tablas incoherentes con operadores booleanos invertidos o sin justificación lógica. | /4 |
| Calidad del entregable | Presenta tablas limpias, derivación paso a paso, capturas claras del simulador web y las tres pruebas de control integradas en un solo archivo. | Integra tablas y capturas del simulador con pequeños detalles de organización visual o claridad en una captura. | Falta la validación en simulador web o la comprobación de las tres condiciones de prueba solicitadas. | Entrega apuntes sueltos o respuestas finales sin tablas de verdad ni desarrollo verificable. | /4 |
| Uso de fuentes y referencias | Fundamenta reglas de equivalencia con fuentes reales consultadas, declara herramientas digitales o de inteligencia artificial y cita en normas de citación y referencias de la Asociación Americana de Psicología (séptima edición). | Documenta las fuentes consultadas con imprecisiones menores de formato o puntuación en la lista final. | Omite declarar apoyo digital o utiliza referencias generales sin asociarlas al procedimiento. | Incluye referencias falsas o presenta demostraciones externas sin atribución autoral. | /4 |

### PRÁCTICA 2: Diagramación y simulación paso a paso de pilas, colas y recorridos
- PRACTICA_UNIDAD:
  Práctica 2 — Correspondiente al Trabajo Práctico-Experimental de la Unidad 2. Antes de simular los flujos, revise la diferencia entre dato e información, los tipos primitivos y compuestos y las reglas de acceso de listas, pilas de tipo último en entrar, primero en salir (LIFO) y colas de tipo primero en entrar, primero en salir (FIFO) en la [Guía Didáctica, Unidad 2](../03_Guias_Didacticas_V2/GD_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md) y avance su Trabajo Autónomo 2.
- RESULTADOS_APRENDIZAJE:
  Diferencia datos de información relacionando su representación digital con tipos de datos primitivos; estructura colecciones de datos compuestas mediante registros, tuplas y campos tipificados; modela el comportamiento operativo de listas, pilas (LIFO) y colas (FIFO) según las reglas de acceso a elementos; y selecciona la estructura de datos más eficiente considerando el tipo de acceso y persistencia requerida en el problema.
- OBJETIVO_PRACTICA:
  Modelar registros con campos tipificados, simular paso a paso operaciones de apilado, encolado y recorrido en estructuras lineales de datos mediante visualizadores interactivos y explicar oralmente por qué cada estructura responde a un requerimiento operativo específico.
- TIEMPO_ESTIMADO:
  12 horas de aprendizaje práctico-experimental asincrónico distribuidas en las semanas 3 y 4. Dedicación sugerida: diagnóstico de las estructuras invertidas del caso y definición de registros tipificados (2 horas), diagramación y simulación paso a paso de los flujos en pila, cola y lista en plataforma visual (6 horas), verificación de tres condiciones operativas incluyendo desbordamiento inferior en estructura vacía (2 horas y 30 minutos), y grabación de la explicación oral asincrónica junto con la integración final en Moodle (1 hora y 30 minutos). Suma total: 12 horas. Las lecturas y el catálogo del Trabajo Autónomo 2 permanecen dentro de sus 12 horas de aprendizaje autónomo.
- RECURSOS_DIGITALES_MATERIALES:
  Equipo informático con conexión a internet; aula virtual en Moodle (para seguimiento, intercambios secuenciales de análisis si el docente los habilita y envío único); plataforma interactiva de simulación de estructuras de datos en navegador web (Visualgo.net); diagramador de flujo y estructuras (Draw.io o equivalente); grabadora de audio o video para la sustentación asincrónica; procesador de textos; y, de manera opcional y declarada, un asistente de inteligencia artificial (IA) para generar secuencias adicionales de prueba o revisar la traza de estados (comprobando siempre cada operación manualmente y en el simulador).
- CASO_SITUACION_PROBLEMA:
  La aplicación ficticia de farmacia y logística *FarmaRápida* (caso simulado exclusivamente con fines formativos) enfrenta reclamos urgentes en dos módulos distintos de su sistema:
  1. En el **módulo de despacho de pedidos en línea**, el equipo guardó las órdenes entrantes dentro de una **pila (LIFO)**. Como resultado, cuando llegan pedidos nuevos cada minuto, los primeros compradores quedan enterrados al fondo esperando indefinidamente mientras se atiende primero al último en pedir.
  2. En el **módulo de edición de recetas médicas**, programaron el historial de acciones para el botón **"Deshacer"** usando una **cola (FIFO)**. Cuando el médico comete un error al final de la receta y presiona "Deshacer", el sistema borra la primera línea escrita al inicio en lugar del último cambio realizado.

  Para corregir ambos módulos y organizar el inventario activo, usted simulará y documentará paso a paso las tres secuencias siguientes durante las semanas 3 y 4:
  - **Secuencia de despacho (8 operaciones):** (1) Entra pedido P101; (2) Entra pedido P102; (3) Entra pedido P103; (4) Se despacha un pedido; (5) Entra pedido P104; (6) Se despacha un pedido; (7) Entra pedido P105; (8) Se despachan los pedidos restantes hasta vaciar la estructura y se intenta un despacho adicional sobre la estructura ya vacía.
  - **Secuencia del editor de recetas (6 operaciones):** (1) Acción E1 (agregar medicamento); (2) Acción E2 (ajustar dosis); (3) Acción E3 (corregir horario); (4) Presionar Deshacer; (5) Acción E4 (añadir observación); (6) Presionar Deshacer dos veces seguidas.
  - **Muestra de inventario de cuatro ítems para recorrido en lista:** códigos F01 (Paracetamol, entero en existencias 45, decimal 4,50, receta falso), F02 (Amoxicilina, existencias 18, decimal 9,80, receta verdadero), F03 (Vitamina C, existencias 60, decimal 12,00, receta falso) y F04 (Ibuprofeno, existencias 0, decimal 6,20, receta falso).
- ACTIVIDADES_PREVIAS:
  Repase en la Guía Didáctica el ejemplo comparativo de ingresar A, B, C y retirar elementos en una pila frente a una cola. Abra Visualgo.net en la sección de listas enlazadas, pilas y colas para familiarizarse con los controles de animación paso a paso.
- PROCEDIMIENTO_PASO_A_PASO:
  1. **Especificación de dato, información y registro tipificado (semana 3):** Tome el ítem F02 de *FarmaRápida* y demuestre la diferencia entre dato crudo ("18", "true") e información contextualizada (*"18 cajas disponibles en bodega, requiere receta médica"*). Luego defina el esquema completo de un **registro compuesto de producto farmacéutico** indicando exactamente cada campo, su tipo de dato primitivo (texto, entero, decimal o booleano) y el tamaño aproximado o dominio de valores válidos.
  2. **Simulación comparada en Visualgo y corrección del despacho (estructura cola FIFO):** Ejecute primero la secuencia básica de comprobación (ingresar A y luego B) para verificar en Visualgo que retirar de una pila devuelve B y retirar de una cola devuelve A. A continuación, trace las ocho operaciones de la **secuencia de despacho** de *FarmaRápida* utilizando una **cola (FIFO)** en lugar de una pila, registrando en una tabla y capturas de Visualgo o Draw.io el estado completo (frente, cuerpo y final) después de cada operación.
  3. **Simulación paso a paso del botón Deshacer (estructura pila LIFO):** Trace las seis operaciones de la **secuencia del editor de recetas** utilizando una **pila (LIFO)**, señalando en cada paso qué elemento ocupa la cima, qué elemento sale en cada pulsación de "Deshacer" y por qué la estructura anterior en cola generaba pérdida de datos correctos.
  4. **Diagramación de recorrido en lista y prueba de tres condiciones (semana 4):** Represente gráficamente en Draw.io una **lista secuencial** con los cuatro registros F01–F04 del inventario y trace un recorrido completo paso a paso para detectar productos agotados (existencias iguales a cero). Documente explícitamente tres condiciones de prueba en sus estructuras: (a) **condición normal** (retiro con elementos disponibles respetando orden FIFO/LIFO); (b) **condición límite** (desencolar el último elemento restante dejando la estructura vacía o detectar existencia cero en lista); y (c) **condición de error controlado** (intentar desapilar o desencolar cuando la estructura ya está vacía, explicando cómo debe responder el software sin colgarse).
  5. **Comparación técnica de eficiencia y persistencia:** Redacte un cuadro comparativo que justifique por qué *FarmaRápida* necesita cola para despachos, pila en memoria temporal para Deshacer y almacenamiento persistente en archivo o tabla para el catálogo de inventario al cerrar el sistema.
  6. **Explicación oral asincrónica e integración en Moodle:** Grabe un audio o video breve (de 2 a 3 minutos) narrando paso a paso su simulación en Visualgo o su diagrama de Draw.io y explicando con claridad por qué intercambiar pila y cola dañó la experiencia de compradores y médicos en *FarmaRápida*. Adjunte la grabación (o su enlace reproducible) y los registros secuenciales de diálogo en Moodle (si el docente habilitó intercambio entre pares) dentro del mismo expediente.
- ENTREGABLE_EVIDENCIA:
  Un único expediente digital integrado (por ejemplo "Apellido_Nombre_Unidad2_Practica2.docx" o ".pdf", o paquete comprimido si adjunta el audio/video directamente), que contenga:
  - Definición del registro compuesto con campos tipificados y distinción explícita entre dato, información y representación binaria/lógica.
  - Tablas de traza estado por estado, capturas de Visualgo.net y diagramas de flujo o estructura en Draw.io para las secuencias de cola FIFO, pila LIFO y recorrido de lista, incluyendo las tres condiciones probadas.
  - Cuadro justificativo de selección estructural según acceso y persistencia, junto con la grabación asincrónica (audio o video de 2 a 3 minutos) y eventuales registros secuenciales de retroalimentación en Moodle.
- FORMA_ENTREGA_EVALUACION:
  En la semana 3 se revisan formativamente en Moodle la definición de registros y las primeras trazas de pila y cola; al cierre de la semana 4 se sube la versión única y definitiva al espacio del Trabajo Práctico-Experimental 2. Será evaluada mediante la rúbrica analítica presentada a continuación y la lista de cotejo correspondiente dentro del esquema de calificación vigente en Moodle para Desarrollo de Software.
- AUTOEVALUACION_REFLEXION:
  Al concluir su trabajo, responda brevemente en un párrafo: ¿qué error concreto observó al simular el manejo de una estructura vacía (desbordamiento inferior) y por qué en aplicaciones reales es obligatorio verificar si la pila o cola está vacía antes de retirar un elemento? ¿Qué aportó explicar oralmente la traza paso a paso respecto a solo dibujar una figura estática?

#### RÚBRICA ANALÍTICA SUGERIDA
| CRITERIO | EXCELENTE_4 | BUENO_3 | EN_PROCESO_2 | INSUFICIENTE_1 | PUNTAJE |
| --- | --- | --- | --- | --- | --- |
| Pertinencia del análisis | Diagnostica con precisión por qué fallaban despacho y botón Deshacer en *FarmaRápida*, tipifica el registro completo y justifica cada elección por acceso y persistencia. | Diagnostica ambos módulos y tipifica el registro con omisiones menores al justificar criterios de persistencia. | Identifica qué estructura corresponde a cada módulo sin detallar tipos primitivos ni justificar el impacto operativo. | Mantiene invertidas las estructuras pila y cola o define campos sin relación con el caso. | /4 |
| Aplicación conceptual | Traza sin errores todas las operaciones de cola FIFO, pila LIFO y recorrido de lista en Visualgo/Draw.io, comprobando las tres condiciones incluido estado vacío. | Ejecuta correctamente las trazas principales con algún error menor en un paso intermedio o en la condición de error controlado. | Presenta trazas incompletas de las secuencias o confunde frente/final con cima al simular retiros sucesivos. | No ejecuta simulaciones paso a paso ni distingue el orden de salida entre pilas y colas. | /4 |
| Calidad del entregable | Integra registros, tablas de estado, capturas nítidas de simulación, diagramas en Draw.io y explicación oral asincrónica clara en un solo envío ordenado. | Cumple los diagramas, tablas y grabación asincrónica con detalles menores de legibilidad o formato. | Omite la grabación oral asincrónica o presenta diagramas estáticos sin evidenciar el estado tras cada operación. | Entrega texto suelto sin diagramas, capturas de simulación ni explicación oral asincrónica. | /4 |
| Uso de fuentes y referencias | Respalda definiciones de estructuras de datos con fuentes consultadas, declara herramientas digitales empleadas y aplica normas de citación y referencias de la Asociación Americana de Psicología (séptima edición). | Cita las fuentes utilizadas con leves errores de orden o puntuación en la lista de referencias. | Menciona definiciones sin citar fuentes reales consultadas ni declarar el uso de simuladores o asistentes. | Presenta referencias inventadas o reproduce material externo sin reconocimiento autoral. | /4 |

### PRÁCTICA 3: Modelado del esquema de tablas relacionales para tienda virtual
- PRACTICA_UNIDAD:
  Práctica 3 — Correspondiente al Trabajo Práctico-Experimental de la Unidad 3. Antes de modelar la base de datos, repase claves primarias, claves foráneas, cardinalidades, integridad referencial y normalización en Primera Forma Normal (1FN), Segunda Forma Normal (2FN) y Tercera Forma Normal (3FN) en la [Guía Didáctica, Unidad 3](../03_Guias_Didacticas_V2/GD_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md) y avance su Trabajo Autónomo 3.
- RESULTADOS_APRENDIZAJE:
  Diseña tablas identificando campos, dominios de datos y claves primarias para garantizar la unicidad de registros; establece relaciones de cardinalidad uno a uno (1:1) y uno a muchos (1:N) vinculando tablas mediante claves foráneas; preserva la integridad referencial y de dominio en las relaciones estructuradas entre entidades; y aplica las formas normales fundamentales (1FN, 2FN y 3FN) para mitigar anomalías de inserción, actualización y borrado.
- OBJETIVO_PRACTICA:
  Transformar un registro plano con redundancias y anomalías en un esquema relacional normalizado hasta tercera forma normal para una tienda virtual en línea, definiendo tipos de datos, claves primarias, claves foráneas y reglas comprobadas de integridad referencial.
- TIEMPO_ESTIMADO:
  12 horas de aprendizaje práctico-experimental asincrónico distribuidas en las semanas 5 y 6. Dedicación sugerida: auditoría de anomalías en la tabla plana inicial y definición de entidades y claves primarias (2 horas), descomposición progresiva en Primera, Segunda y Tercera Forma Normal y modelado visual de relaciones (6 horas), pruebas de inserción, actualización, borrado e integridad referencial con filas de ensayo (2 horas y 30 minutos), e integración del diccionario de datos y entrega final en Moodle (1 hora y 30 minutos). Suma total: 12 horas. Las lecturas y el diagrama entidad-relación del Trabajo Autónomo 3 permanecen dentro de sus 12 horas de aprendizaje autónomo.
- RECURSOS_DIGITALES_MATERIALES:
  Equipo informático con conexión a internet; aula virtual en Moodle (para seguimiento, intercambio asincrónico de discusión sobre esquemas relacionales si aplica y envío único); herramientas gratuitas de diseño relacional en línea o locales (dbdiagram.io, Draw.io o MySQL Workbench en modo de diseño lógico); procesador de textos u hoja de cálculo para validar filas de ensayo; y, opcionalmente con declaración ética, consultas a inteligencia artificial (IA) para contrastar dependencias funcionales o cardinalidades antes de comprobarlas por cuenta propia.
- CASO_SITUACION_PROBLEMA:
  La tienda virtual ficticia *MercadoSierra en Línea* (caso simulado exclusivamente con fines formativos) lleva el control de sus pedidos y del Impuesto al Valor Agregado (IVA) en la siguiente tabla única sin normalizar, donde ya han ocurrido fallos graves de consistencia de datos:

  | ID_Pedido | Fecha | Nombre_Cliente | Correo_Cliente | Direccion_Envio | Productos_Comprados | Cantidades | Categoria | Tarifa_IVA | Precio_Unitario |
  | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
  | 501 | 2026-04-02 | Valeria Méndez | valeria@correo.test | Av. Amazonas 120, Quito | Teclado mecánico, Ratón óptico | 1, 2 | Periféricos | 15 % | 45.00, 18.00 |
  | 502 | 2026-04-03 | Carlos Paredes | carlos@correo.test | Calle Larga 45, Cuenca | Monitor con pantalla de diodos emisores de luz (LED) de 24 pulgadas | 1 | Pantallas | 15 % | 190.00 |
  | 503 | 2026-04-05 | Valeria Méndez | valeria.m@correo.test | Av. Amazonas 120, Quito | Ratón óptico | 1 | Periféricos | 15 % | 18.00 |
  | 504 | 2026-04-06 | Elena Torres | elena@correo.test | Av. 9 de Octubre 80, Guayaquil | Cable de interfaz multimedia de alta definición (HDMI), Adaptador de bus serie universal (USB) | 2, 1 | Accesorios | 15 % | 9.50, 14.00 |

  Observe los problemas visibles en los cuatro registros ficticios: el pedido 501 y el 504 amontonan varios productos y precios en listas separadas por comas; Valeria Méndez aparece dos veces con distinto correo electrónico (inconsistencia por redundancia); no se puede registrar un nuevo producto en catálogo si nadie lo ha comprado todavía; el nombre de la categoría determina la tarifa de impuesto y no depende del pedido; y si se elimina el pedido 502, desaparece por completo el cliente Carlos Paredes del sistema. Durante las semanas 5 y 6 usted diseñará el esquema relacional normalizado completo para *MercadoSierra en Línea*.
- ACTIVIDADES_PREVIAS:
  Repase en la Guía Didáctica las reglas de Primera, Segunda y Tercera Forma Normal y el ejemplo de la relación entre Pedido y Cliente mediante clave foránea. Abra dbdiagram.io o Draw.io para confirmar que puede exportar su diagrama relacional como imagen nítida o archivo en formato de documento portátil (PDF).
- PROCEDIMIENTO_PASO_A_PASO:
  1. **Diagnóstico inicial de anomalías (semana 5):** Documente en una lista concreta cuatro problemas reales observables en la tabla plana de *MercadoSierra en Línea*, clasificándolos explícitamente en violación de atomicidad y en anomalías de **inserción**, **actualización** y **borrado**.
  2. **Identificación de entidades y claves primarias estables:** Defina las entidades independientes necesarias para el modelo de la tienda virtual (por ejemplo: Clientes, Perfil_Facturacion_Cliente o Direcciones, Categorias, Productos, Pedidos y Detalle_Pedido). Asigne a cada tabla una **clave primaria** única, obligatoria e inmutable (como "id_cliente", "id_producto", "id_categoria", "id_pedido"), explicando por qué no debe usarse el correo electrónico o el nombre como clave primaria.
  3. **Normalización progresiva hasta Tercera Forma Normal (semana 6):** Muestre paso a paso cómo evoluciona la tabla original:
     - En **Primera Forma Normal (1FN):** elimine las listas separadas por comas ("Teclado mecánico, Ratón óptico") logrando que cada celda guarde un único valor atómico y cada línea de compra tenga su propio registro.
     - En **Segunda Forma Normal (2FN):** resuelva la relación muchos a muchos (N:M) entre Pedidos y Productos mediante una tabla intermedia Detalle_Pedido (con clave primaria compuesta o identificador propio más claves foráneas "id_pedido" e "id_producto", cantidad y precio aplicado en la compra), eliminando dependencias parciales como el nombre del producto o el nombre del cliente respecto a una clave compuesta.
     - En **Tercera Forma Normal (3FN):** elimine dependencias transitivas separando Categorias (con "id_categoria", "nombre_categoria" y "tarifa_iva") respecto a Productos, y asegurando que los datos del cliente vivan una sola vez en Clientes.
  4. **Definición de claves foráneas, cardinalidades y dominios en dbdiagram.io o Draw.io:** Construya el diagrama relacional completo especificando en cada tabla el nombre exacto de columna, tipo y dominio de dato (entero, cadena de longitud limitada, decimal exacto para precios, fecha), marcando claves primarias, claves foráneas e incorporando al menos una relación **uno a muchos (1:N)** (por ejemplo, Cliente realiza muchos Pedidos) y una relación **uno a uno (1:1)** justificada (por ejemplo, entre Cliente y Perfil_Facturacion o entre Pedido y Comprobante_Electronico).
  5. **Diccionario de datos y comprobación de tres escenarios de integridad referencial:** Elabore un breve diccionario de datos y simule mediante tablas de prueba con filas concretas (tomando los datos reales de Valeria, Carlos y Elena ya corregidos) tres comprobaciones obligatorias: (a) **condición normal**, registrar un nuevo pedido para un cliente existente comprobando cómo se llenan Pedidos y Detalle_Pedido; (b) **condición límite de actualización o borrado**, actualizar el correo electrónico de Valeria Méndez en una sola celda de Clientes y verificar cómo se refleja en sus pedidos 501 y 503 sin duplicar datos, además de explicar qué política de integridad ("RESTRICT" o impedimento de borrado) evita borrar a Carlos si tiene el pedido 502 activo; y (c) **condición errónea**, intentar insertar un pedido con un "id_cliente" inexistente demostrando que la restricción de clave foránea rechaza la operación para impedir pedidos huérfanos.
  6. **Revisión colaborativa e integración final:** Si el docente habilita foro o discusión asincrónica en Moodle sobre decisiones de normalización, documente brevemente su aporte o ajuste realizado tras comparar su esquema y consolide todo en un único expediente.
- ENTREGABLE_EVIDENCIA:
  Un único archivo organizado en formato editable o en formato de documento portátil (PDF), por ejemplo "Apellido_Nombre_Unidad3_Practica3.docx" o ".pdf", que integre:
  - Diagnóstico de las anomalías en la tabla inicial de *MercadoSierra en Línea* y explicación paso a paso de la transformación en Primera, Segunda y Tercera Forma Normal.
  - Diagrama relacional nítido elaborado en dbdiagram.io, Draw.io o herramienta equivalente, mostrando todas las tablas, tipos de datos, cardinalidades (1:1 y 1:N), claves primarias y claves foráneas (adjunte también el código fuente de dbdiagram o descripción textual accesible del diagrama).
  - Diccionario de datos y tablas de prueba con las filas simuladas que comprueban los tres escenarios de inserción, actualización/borrado e integridad referencial.
- FORMA_ENTREGA_EVALUACION:
  En la semana 5 recibirá devolución formativa en Moodle sobre las entidades, dominios y claves primarias definidas; al cierre de la semana 6 entregará el único documento integrado en el espacio del Trabajo Práctico-Experimental 3. Será evaluado con la rúbrica analítica presentada a continuación y la lista de cotejo correspondiente dentro del esquema de calificación vigente en Moodle para Desarrollo de Software.
- AUTOEVALUACION_REFLEXION:
  Al cierre de su informe, responda brevemente en un párrafo: ¿qué inconsistencia concreta de los datos de Valeria Méndez desapareció al aplicar la Segunda y Tercera Forma Normal? ¿Por qué una clave foránea entre Pedidos y Clientes protege la confiabilidad del sistema mejor que confiar en que el programador revise manualmente si el cliente existe?

#### RÚBRICA ANALÍTICA SUGERIDA
| CRITERIO | EXCELENTE_4 | BUENO_3 | EN_PROCESO_2 | INSUFICIENTE_1 | PUNTAJE |
| --- | --- | --- | --- | --- | --- |
| Pertinencia del análisis | Diagnostica todas las anomalías de la tabla plana de *MercadoSierra en Línea* y comprueba con filas reales la solución a inserción, actualización y borrado. | Identifica las principales anomalías y realiza pruebas con filas de ensayo con omisiones menores en un escenario límite. | Menciona anomalías de forma teórica sin demostrarlas sobre los datos concretos del caso. | Mantiene la tabla plana sin diagnosticar redundancias ni pérdidas de integridad. | /4 |
| Aplicación conceptual | Normaliza con exactitud hasta Tercera Forma Normal, define claves primarias estables, establece relaciones 1:1 y 1:N con claves foráneas y prueba la restricción de integridad. | Cumple la normalización y relaciones principales con leves imprecisiones en dominios de datos o en la relación 1:1. | Deja grupos repetidos o dependencias transitivas sin resolver, o confunde claves primarias con claves foráneas. | Diseña tablas aisladas sin claves primarias válidas ni vínculos referenciales coherentes. | /4 |
| Calidad del entregable | Presenta evolución 1FN-2FN-3FN, diagrama legible de dbdiagram.io o Draw.io, diccionario de datos y tablas de prueba integrados en un solo envío. | Integra diagrama, diccionario y pruebas con pequeños detalles visuales en cardinalidades o legibilidad. | Omite el diccionario de datos o la demostración con filas simuladas de los tres escenarios. | Entrega únicamente una lista informal de tablas sin diagrama ni pruebas de integridad. | /4 |
| Uso de fuentes y referencias | Fundamenta reglas de normalización e integridad con literatura consultada, declara herramientas empleadas y cita según normas de citación y referencias de la Asociación Americana de Psicología (séptima edición). | Cita las fuentes utilizadas con errores menores de puntuación o formato de citación y referencias en la lista bibliográfica. | Omite precisar fuentes reales consultadas o el uso de asistentes de apoyo. | Presenta citas inventadas o atribuye material técnico externo sin reconocimiento autoral. | /4 |

### PRÁCTICA 4: Ejecución interactiva de consultas y filtrado de datos con lenguaje de consulta estructurado (SQL)
- PRACTICA_UNIDAD:
  Práctica 4 — Correspondiente al Trabajo Práctico-Experimental de la Unidad 4. Antes de ejecutar sus sentencias, repase la proyección SELECT y FROM, filtros compuestos con WHERE, precedencia de AND frente a OR, BETWEEN, LIKE, ORDER BY y COUNT en la [Guía Didáctica, Unidad 4](../03_Guias_Didacticas_V2/GD_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md) y avance su Trabajo Autónomo 4.
- RESULTADOS_APRENDIZAJE:
  Formula sentencias SELECT y FROM para proyectar columnas específicas a partir de tablas relacionales; aplica cláusulas WHERE combinando operadores lógicos y relacionales (AND, OR, NOT, BETWEEN, LIKE) para filtrar registros; ordena conjuntos de resultados mediante ORDER BY de forma ascendente y descendente bajo múltiples criterios; y emplea funciones de conteo y agregación básica (COUNT) para generar resúmenes informativos de la base de datos.
- OBJETIVO_PRACTICA:
  Ejecutar consultas reales de proyección, filtrado lógico compuesto, ordenamiento multicriterio y conteo sobre una base de datos relacional en PostgreSQL, SQLite o un entorno interactivo de lenguaje de consulta estructurado (SQL), verificando resultados esperados frente a obtenidos y aplicando buenas prácticas de gestión segura de datos.
- TIEMPO_ESTIMADO:
  12 horas de aprendizaje práctico-experimental asincrónico distribuidas en las semanas 7 y 8. Dedicación sugerida: preparación del motor SQL o entorno web y carga de las tablas de prueba (2 horas), diseño y ejecución interactiva de las seis consultas de proyección, filtrado compuesto, ordenamiento y conteo (6 horas), comprobación de casos límite, diagnóstico del error de precedencia sin paréntesis y verificación segura antes de modificar registros (2 horas y 30 minutos), e integración del script comentado, capturas de resultados y entrega final en Moodle (1 hora y 30 minutos). Suma total: 12 horas. Las lecturas y las diez consultas del Trabajo Autónomo 4 permanecen dentro de sus 12 horas de aprendizaje autónomo.
- RECURSOS_DIGITALES_MATERIALES:
  Equipo informático con conexión a internet; aula virtual en Moodle; motor relacional gratuito SQLite (mediante DB Browser for SQLite o DBeaver) o PostgreSQL (con pgAdmin o DBeaver), o bien un entorno interactivo de ejecución en navegador web (DB Fiddle, SQLFiddle o editor SQL de W3Schools); editor de texto plano para guardar scripts con extensión ".sql"; y, de forma opcional y declarada, un asistente de inteligencia artificial (IA) para interpretar mensajes de error sintáctico antes de probar la corrección en el motor real. Si utiliza la base preconfigurada que habilite su docente en Moodle o el conjunto de tablas del caso presentado abajo, conserve evidencia real de las filas devueltas.
- CASO_SITUACION_PROBLEMA:
  La librería digital ficticia *LecturaViva* (caso simulado exclusivamente con fines formativos) necesita emitir seis reportes operativos desde su base de datos de ensayo, después de descubrir que un analista anterior cometió errores graves al olvidar paréntesis entre operadores AND y OR, usar comillas incorrectas en literales de texto y no validar los valores nulos. Si su docente habilita un archivo preconfigurado en Moodle utilice ese esquema; de lo contrario, cree y ejecute directamente en SQLite, PostgreSQL o DB Fiddle las tres tablas ficticias siguientes con sus datos exactos:

  **Tabla "clientes":**
  | id_cliente | nombre | ciudad | correo | telefono | activo |
  | --- | --- | --- | --- | --- | --- |
  | 1 | Ana Paredes | Quito | ana@lectura.test | 0991112233 | 1 |
  | 2 | Luis Gómez | Cuenca | luis@lectura.test | 0982223344 | 1 |
  | 3 | Sofía León | Quito | sofia@lectura.test | NULL | 0 |
  | 4 | Pedro Silva | Loja | pedro@lectura.test | 0973334455 | 1 |
  | 5 | Carla Ruiz | Cuenca | carla@lectura.test | NULL | 0 |
  | 6 | Mateo Vega | Quito | mateo@lectura.test | 0964445566 | 1 |

  **Tabla "libros":**
  | id_libro | titulo | categoria | precio | existencias |
  | --- | --- | --- | --- | --- |
  | 10 | Lógica para Programadores | Tecnología | 18.50 | 12 |
  | 11 | Diseño de Bases de Datos | Tecnología | 28.00 | 7 |
  | 12 | SQL Práctico desde Cero | Tecnología | 22.00 | 15 |
  | 13 | Relatos de la Sierra | Literatura | 12.00 | 20 |
  | 14 | Arquitectura Moderna | Ingeniería | 35.00 | 4 |
  | 15 | Manual de Redacción Técnica | Comunicación | 14.50 | 9 |

  **Tabla "pedidos":**
  | id_pedido | id_cliente | id_libro | fecha_pedido | cantidad | estado |
  | --- | --- | --- | --- | --- | --- |
  | 101 | 1 | 10 | 2026-03-05 | 1 | Entregado |
  | 102 | 2 | 12 | 2026-03-08 | 2 | Entregado |
  | 103 | 1 | 11 | 2026-03-12 | 1 | Pendiente |
  | 104 | 4 | 13 | 2026-03-14 | 3 | Entregado |
  | 105 | 6 | 12 | 2026-03-18 | 1 | Cancelado |
  | 106 | 2 | 15 | 2026-03-20 | 2 | Entregado |
  | 107 | 6 | 10 | 2026-03-24 | 1 | Pendiente |
  | 108 | 4 | 14 | 2026-03-29 | 1 | Entregado |

- ACTIVIDADES_PREVIAS:
  Repase en la Guía Didáctica las reglas de precedencia entre AND y OR, los límites inclusivos de BETWEEN, los comodines de LIKE, la comprobación de nulos con IS NULL y el formato de literales entre comillas simples en lenguaje de consulta estructurado (SQL). Prepare una copia de respaldo del script inicial de creación e inserción de tablas antes de probar cualquier cambio.
- PROCEDIMIENTO_PASO_A_PASO:
  1. **Preparación de la base de ensayo en SQLite, PostgreSQL o sandbox web (semana 7):** Cree las tablas "clientes", "libros" y "pedidos" respetando claves primarias ("id_cliente", "id_libro", "id_pedido") y claves foráneas en "pedidos", e inserte exactamente los registros indicados (o cargue el archivo preconfigurado provisto por su docente). Verifique mediante consultas simples que las tres tablas contienen 6, 6 y 8 filas respectivamente.
  2. **Proyección y selección básica con sintaxis válida de literales:** Ejecute la consulta de comprobación proyectando columnas específicas: SELECT nombre, ciudad FROM clientes WHERE ciudad = 'Quito'; Observe que en SQL los literales de texto usan comillas simples y confirme que aparecen exactamente tres clientes (Ana Paredes, Sofía León y Mateo Vega). Explique qué error sintáctico ocurre si se omiten comillas o si se usan comillas dobles en motores estrictos como PostgreSQL.
  3. **Consultas de rango inclusivo y patrones de texto (semana 8):** Escriba y ejecute dos nuevas consultas reales:
     - **Consulta de rango (BETWEEN):** liste título, categoría y precio de los libros cuyo precio esté entre 14,50 y 28,00 dólares (ordenados de menor a mayor precio), confirmando que BETWEEN incluye exactamente ambos extremos (14.50 y 28.00).
     - **Consulta por patrón y negación (LIKE y NOT):** liste identificador, título y categoría de todos los libros cuyo título contenga la palabra 'SQL' o comience con 'Lógica' (usando LIKE con comodín "%") y que NO pertenezcan a la categoría 'Literatura'.
  4. **Diagnóstico de precedencia compuesta (AND frente a OR) con tres condiciones de prueba:** Ejecute y compare estas dos versiones para obtener los **clientes activos de Quito o Cuenca**:
     - **(a) Condición errónea sin paréntesis:** SELECT id_cliente, nombre, ciudad, activo FROM clientes WHERE ciudad = 'Quito' OR ciudad = 'Cuenca' AND activo = 1;
     - **(b) Condición normal corregida con paréntesis:** SELECT id_cliente, nombre, ciudad, activo FROM clientes WHERE (ciudad = 'Quito' OR ciudad = 'Cuenca') AND activo = 1 ORDER BY ciudad ASC, nombre ASC;
     - **(c) Condición límite con valores nulos:** liste los clientes que no tienen teléfono registrado usando SELECT id_cliente, nombre FROM clientes WHERE telefono IS NULL; y compárelo con escribir "= NULL", demostrando con captura real por qué "= NULL" devuelve cero filas.
  5. **Ordenamiento multicriterio y agregación básica con COUNT:** Formule y ejecute dos consultas analíticas sobre "pedidos":
     - Liste id_pedido, id_cliente, fecha_pedido, cantidad y estado de los pedidos con estado distinto de 'Cancelado', ordenados primero por estado ascendente y luego por fecha_pedido descendente.
     - Calcule mediante COUNT(id_pedido) cuántos pedidos en total existen registrados, cuántos tienen estado 'Entregado' y cuántos se realizaron entre el 2026-03-10 y el 2026-03-31.
  6. **Protocolo de buenas prácticas antes de modificar datos:** Sobre una copia controlada de su base de prueba, muestre cómo redactar primero un SELECT previo de comprobación antes de simular una actualización segura de estado (por ejemplo, pasar el pedido 103 de 'Pendiente' a 'Entregado' filtrando únicamente por su clave primaria id_pedido = 103), y documente en tres líneas por qué los parámetros ingresados por un usuario jamás deben concatenarse manualmente dentro de cadenas SQL.
- ENTREGABLE_EVIDENCIA:
  Un único expediente digital (por ejemplo "Apellido_Nombre_Unidad4_Practica4.docx" o ".pdf", junto con el archivo ".sql" adjunto o integrado), que contenga:
  - Script SQL completo, ordenado y comentado (creación de tablas e inserción de ensayo si la armó desde cero, más todas las consultas ejecutadas).
  - Tabla de verificación por cada consulta ejecutada mostrando: sentencia SQL exacta, filas esperadas manualmente, captura legible de las filas reales devueltas por PostgreSQL, SQLite o el sandbox web y análisis breve de la salida.
  - Evidencia explícita de las tres condiciones de comprobación (consulta correcta con paréntesis, diagnóstico de error sin paréntesis y prueba límite con IS NULL frente a "= NULL") más el protocolo seguro de respaldo y consulta previa antes de UPDATE.
- FORMA_ENTREGA_EVALUACION:
  En la semana 7 se revisan formativamente en Moodle la carga de la base de prueba y las primeras consultas de proyección y selección; al cierre de la semana 8 se sube el expediente definitivo único al espacio del Trabajo Práctico-Experimental 4. Será calificado mediante la rúbrica analítica adjunta y la lista de cotejo correspondiente dentro del esquema de calificación vigente en Moodle para la carrera Desarrollo de Software.
- AUTOEVALUACION_REFLEXION:
  Al finalizar su informe, responda brevemente en un párrafo: ¿qué cliente inactivo apareció indebidamente al ejecutar la consulta sin paréntesis entre OR y AND, y qué lección práctica deja esto para programar filtros de búsqueda? ¿Por qué verificar un SELECT antes de ejecutar UPDATE o DELETE evita pérdidas irreversibles de información?

#### RÚBRICA ANALÍTICA SUGERIDA
| CRITERIO | EXCELENTE_4 | BUENO_3 | EN_PROCESO_2 | INSUFICIENTE_1 | PUNTAJE |
| --- | --- | --- | --- | --- | --- |
| Pertinencia del análisis | Contrasta filas esperadas frente a obtenidas en cada consulta, explica con claridad el error de precedencia AND/OR y aplica buenas prácticas seguras antes de modificar datos. | Contrasta resultados y diagnostica el error de precedencia con omisiones menores en la explicación del protocolo seguro previo a actualización. | Presenta las consultas sin comparar filas esperadas ni explicar por qué fallan consultas sin paréntesis o con "= NULL". | Escribe consultas desconectadas de los requerimientos de *LecturaViva* o interpreta erróneamente los datos devueltos. | /4 |
| Aplicación conceptual | Ejecuta con sintaxis correcta SELECT, FROM, WHERE compuesto (AND, OR, NOT, BETWEEN, LIKE), IS NULL, ORDER BY multicriterio y COUNT sobre datos reales. | Ejecuta adecuadamente la mayoría de sentencias SQL con algún error puntual en comodines de LIKE, ordenamiento doble o extremos de BETWEEN. | Ejecuta solo consultas simples de una condición sin combinar filtros compuestos ni ordenamiento ni conteo. | Presenta errores graves de sintaxis que impiden ejecutar las sentencias en el motor relacional. | /4 |
| Calidad del entregable | Integra el script SQL comentado y reproducible, capturas legibles de salida real y las tres comprobaciones (normal, error de precedencia y límite nulo) en un solo envío. | Integra script y capturas de salida real con detalles menores de organización visual o comentarios. | Adjunta únicamente código SQL escrito sin capturas ni evidencia real de ejecución sobre la base de ensayo. | Entrega texto incompleto sin script reproducible ni resultados comprobables. | /4 |
| Uso de fuentes y referencias | Respalda sintaxis SQL y buenas prácticas de seguridad en documentación oficial (como PostgreSQL o textos del curso), declara asistentes digitales y cita en normas de citación y referencias de la Asociación Americana de Psicología (séptima edición). | Documenta las fuentes consultadas con imprecisiones menores en formato de citación y referencias o orden de la lista de referencias. | Omite citar documentación de referencia o aclarar si empleó asistentes digitales de revisión sintáctica. | Presenta referencias inventadas o atribuye scripts externos sin reconocimiento autoral. | /4 |

## 4. REFERENCIAS BIBLIOGRÁFICAS EN FORMATO APA

### BIBLIOGRAFIA_BASICA
- Levin, O. (2024). *Discrete Mathematics: An Open Introduction* (4.ª ed.). University of Northern Colorado / Open Access Textbooks. https://discrete.openmathbooks.org/pdfs/dmoi4-tablet.pdf
- Watt, A. y Eng, N. (2023). *Database Design* (2.ª ed.). BCcampus Open Education. https://opentextbc.ca/dbdesign01/
- Doerr, A. y Levasseur, K. (2024). *Applied Discrete Structures* (Versión 3.10). UMass Lowell / Open Access Books. https://discretemath.org/ads/ads.pdf

### BIBLIOGRAFIA_COMPLEMENTARIA
- DeBarros, A. (2022). *Practical SQL: A Beginner’s Guide to Storytelling with Data* (2.ª ed.). No Starch Press.
- Stephens, R. (2023). *Beginning Database Design Solutions: Understanding and Implementing Database Design Concepts for the Cloud and Beyond* (2.ª ed.). Wiley.
- PostgreSQL Global Development Group (2024). *Documentación oficial de PostgreSQL en español*. https://www.postgresql.org/docs/
