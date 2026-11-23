# GUÍA DIDÁCTICA — MODALIDAD EN LÍNEA

## INTRODUCCIÓN
Esta guía didáctica acompaña su aprendizaje en la asignatura Lógica Matemática y Gestión de Datos de la carrera Desarrollo de Software, organizada en cuatro unidades temáticas de dos semanas cada una (ocho semanas en total). Su propósito es brindarle explicaciones claras, ejemplos resueltos paso a paso y orientaciones prácticas para estudiar de manera autónoma en el aula virtual de Moodle.

En cada unidad desarrollará dos trabajos asincrónicos integrados: un Trabajo Autónomo orientado a la formalización lógica, el modelado de datos y el diseño de consultas, y un Trabajo Práctico-Experimental que llevará esos conceptos a simuladores lógicos, diagramadores relacionales y motores de bases de datos. El caso aplicado se introduce al final de cada unidad en esta guía y se ejecuta paso a paso en su pareja, la Guía de Prácticas.

En ambas guías dispone de las definiciones, casos resueltos, tablas de ejemplo y procedimientos necesarios para completar sus actividades sin requerir la compra de textos adicionales. Las obras listadas al final corresponden a las referencias del Programa de Estudio de la Asignatura y su consulta complementaria dependerá de los recursos que su docente habilite en el aula virtual.

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
- NUMERO_UNIDADES: 4 unidades temáticas

## 2. PROPÓSITO DE LA GUÍA DIDÁCTICA
Aplicar los principios de la lógica proposicional y las estructuras básicas de datos para modelar tablas relacionales y ejecutar consultas de gestión de información en el desarrollo de software.

Esta guía organiza el desarrollo conceptual y prepara el Trabajo Autónomo de cada unidad, de modo que usted llegue con bases sólidas al Trabajo Práctico-Experimental correspondiente. Cada lectura guiada, ejercicio de comprobación y autoevaluación forma parte de esos mismos dos trabajos por unidad y no añade tareas independientes ni horas adicionales fuera de la malla curricular.

## 3. ORIENTACIONES GENERALES PARA EL ESTUDIO EN LÍNEA
- Planifique su estudio en bloques de dos semanas por unidad (semanas 1 y 2, semanas 3 y 4, semanas 5 y 6, semanas 7 y 8), equilibrando las 12 horas de aprendizaje en contacto con el docente, 12 horas de aprendizaje práctico-experimental y 12 horas de aprendizaje autónomo previstas por unidad en el Syllabus.
- Utilice el aula virtual en Moodle como espacio oficial para consultar materiales, recibir retroalimentación y subir sus dos productos por unidad dentro de los plazos comunicados por su docente.
- Participe, cuando lo necesite, en las sesiones semanales de tutoría virtual opcionales (una hora por semana entre las 20:00 y las 00:00, hora de Ecuador, en el horario que anuncie el docente); su asistencia no es obligatoria ni condiciona sus calificaciones.
- Conserve siempre el esquema de dos trabajos integrados por unidad (un Trabajo Autónomo y un Trabajo Práctico-Experimental): en la primera semana de cada unidad avanzará su borrador con retroalimentación formativa y en la segunda semana entregará la versión final corregida.
- Compruebe sus resultados paso a paso antes de darlos por correctos: verifique todas las filas de cada tabla de verdad, trace cada inserción o retiro en pilas y colas, pruebe restricciones de claves con registros de ensayo y ejecute siempre sus consultas sobre bases de prueba.
- Respete la integridad académica y cuide la accesibilidad: cite según las normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) las fuentes que consulte, declare con honestidad cualquier apoyo de herramientas de inteligencia artificial (IA), describa brevemente los diagramas que adjunte y conserve archivos editables de respaldo.

## 4. DESARROLLO DE LAS UNIDADES

### UNIDAD 1: Lógica proposicional, operadores y razonamiento lógico
- RESULTADOS_APRENDIZAJE:
  Aplica principios de lógica matemática para resolver problemas básicos relacionados con el desarrollo de software. Específicamente: identifica proposiciones simples y compuestas asignando valores de verdad según operadores booleanos; construye tablas de verdad para determinar si una proposición constituye una tautología, contingencia o contradicción; simplifica expresiones lógicas complejas utilizando leyes de De Morgan y equivalencias fundamentales; y traduce especificaciones de requerimientos en condiciones booleanas equivalentes aplicables al control de flujo en código.
- OBJETIVO_UNIDAD:
  Resolver proposiciones y tablas de verdad aplicando operadores lógicos para estructurar razonamientos válidos en programación.
- CONTENIDOS:
  - **Semana 1: Proposiciones simples y compuestas y operadores lógicos fundamentales.**
    1.1 Proposiciones simples y compuestas: valores de verdad.
    1.2 Operadores lógicos fundamentales: negación, conjunción, disyunción, condicional y bicondicional.
  - **Semana 2: Construcción y evaluación de tablas de verdad, equivalencias y razonamiento aplicado.**
    1.3 Construcción y evaluación de tablas de verdad.
    1.4 Tautologías, contradicciones, equivalencias lógicas y razonamiento aplicado al software.

  **Desarrollo conceptual.** En programación, cada decisión condicional ("si ocurre tal requisito, entonces ejecuta esta acción") descansa sobre la **lógica proposicional**. Una **proposición lógica** es una afirmación declarativa de la que tiene sentido decidir si es **verdadera** o **falsa**, nunca ambas cosas a la vez (por ejemplo, *"el saldo es mayor o igual que cero"* es una proposición; en cambio, una pregunta o una orden no lo son). Cuando asignamos variables simbólicas como *p*, *q* o *r* a proposiciones simples, podemos combinarlas en proposiciones compuestas mediante cinco **operadores lógicos fundamentales**:
  - **Negación (NO / NOT):** invierte el valor de verdad; si *p* es verdadero, NOT *p* es falso.
  - **Conjunción (Y / AND):** *p* AND *q* es verdadero únicamente cuando *p* y *q* son verdaderos al mismo tiempo.
  - **Disyunción inclusiva (O / OR):** *p* OR *q* es verdadero cuando al menos una de las dos proposiciones es verdadera.
  - **Condicional o implicación ("si *p*, entonces *q*"):** solo resulta falso cuando el antecedente (*p*) es verdadero y el consecuente (*q*) es falso; en programación equivale a verificar si una promesa o regla se incumplió.
  - **Bicondicional ("*p* si y solo si *q*"):** es verdadero únicamente cuando *p* y *q* tienen el mismo valor de verdad (ambos verdaderos o ambos falsos).

  Para analizar todas las combinaciones posibles sin omitir casos borde, se construye una **tabla de verdad**. Para *n* variables proposicionales distintas existen exactamente *2 elevado a n* filas (4 filas para 2 variables; 8 filas para 3 variables). Si la columna final arroja verdadero en todas las filas, la expresión es una **tautología** (como *p* OR NOT *p*); si da falso en todas, es una **contradicción** (como *p* AND NOT *p*); y si mezcla verdaderos y falsos, es una **contingencia**.

  En el diseño de software resulta frecuente negar condiciones compuestas o simplificar condicionales enredados. Para hacerlo sin errores se aplican **equivalencias lógicas** y, en especial, las **leyes de De Morgan**:
  - Negar una conjunción equivale a la disyunción de las negaciones: NOT (*p* AND *q*) es equivalente a (NOT *p*) OR (NOT *q*).
  - Negar una disyunción equivale a la conjunción de las negaciones: NOT (*p* OR *q*) es equivalente a (NOT *p*) AND (NOT *q*).

  **Ejemplo didáctico resuelto (caso ficticio).** Considere la regla de un sistema escolar ficticio: *"Un estudiante puede ver el acta si tiene sesión iniciada (p) y tiene rol de docente (q)"*, es decir, la condición de permiso es (*p* AND *q*). Un programador novato quiere escribir la condición inversa para **bloquear el acceso** y escribe erróneamente (NOT *p*) AND (NOT *q*).
  - *Comprobación con tabla de verdad:* Cuando *p* es verdadero (inició sesión) y *q* es falso (es estudiante, no docente), la expresión (*p* AND *q*) es falsa (no debería pasar). Sin embargo, el bloqueo erróneo (NOT *p*) AND (NOT *q*) evalúa Falso AND Verdadero = **Falso**, ¡así que no lo bloquea!
  - *Simplificación correcta con De Morgan:* Negar (*p* AND *q*) da **(NOT *p*) OR (NOT *q*)**. Con *p* verdadero y *q* falso, evalúa Falso OR Verdadero = **Verdadero**, bloqueando correctamente el acceso no autorizado. Al mismo tiempo, para *p* = verdadero y *q* = falso se verifica que *p* AND *q* es falso, *p* OR *q* es verdadero y *p* OR (NOT *p*) resulta verdadero en todas las filas (tautología).

  **Ejercicio guiado para preparar el Trabajo Autónomo.** Antes de resolver su guía de ejercicios en el Trabajo Autónomo 1, tome un requisito redactado en lenguaje cotidiano de su entorno (por ejemplo, una regla de descuento o validación de formulario), identifique sus variables atómicas *p* y *q*, trace las cuatro filas de la tabla de verdad completa y compruebe qué cambia al negar toda la expresión con De Morgan.
- METODOLOGIA_EN_LINEA:
  Semanas 1 y 2. Dedicación prevista: 12 horas de aprendizaje en contacto con el docente, 12 horas de aprendizaje práctico-experimental y 12 horas de aprendizaje autónomo (36 horas en total). Combina aula invertida sobre lógica proposicional en Moodle, resolución de problemas formales paso a paso y comprobación de equivalencias en simuladores lógicos en línea, con retroalimentación docente asincrónica.
- ACTIVIDADES_APRENDIZAJE:
  1. **Trabajo Autónomo de la Unidad 1 (100 % asincrónico):** Resolución de una guía de ejercicios de formalización proposicional, evaluación de operadores lógicos, construcción de tablas de verdad y aplicación de equivalencias lógicas a decisiones algorítmicas. En la semana 1 formalizará proposiciones simples y compuestas y evaluará los cinco operadores básicos; en la semana 2 completará tablas de verdad, identificará tautologías y contradicciones y simplificará condiciones mediante leyes de De Morgan, entregando un único documento consolidado en Moodle al cierre de la semana 2.
  2. **Trabajo Práctico-Experimental de la Unidad 1 (100 % asincrónico):** Taller guiado en simuladores lógicos web de construcción de tablas de verdad completas y simplificación paso a paso de expresiones booleanas complejas derivadas de reglas de negocio de software. Su procedimiento completo figura en la Práctica 1 de la Guía de Prácticas y se entrega al cierre de la semana 2.
- RECURSOS_MEDIACION_TECNOLOGICA:
  Aula virtual en Moodle (repositorios teóricos, orientaciones docentes y entregas), equipo informático con conexión a internet, simuladores interactivos de tablas booleanas y compuertas lógicas en línea, simuladores lógicos web (como Wolfram Alpha o Logic Friday), editor de diagramas y procesadores de texto, y asistentes de inteligencia artificial (IA) utilizados de forma ética para contrastar demostraciones de equivalencia lógica (verificando siempre fila por fila la tabla completa por cuenta propia).
- EVALUACION_UNIDAD:
  - **Semana 1 (evaluación formativa):** Revisión preliminar en Moodle de la formalización de variables y tablas iniciales de los dos trabajos de la unidad, con comentarios orientadores del docente para corregir errores en condicionales o agrupaciones antes de simplificar.
  - **Semana 2 (evaluación sumativa de la unidad):** Entrega única en Moodle de los dos productos integrados (Trabajo Autónomo 1 y Trabajo Práctico-Experimental 1), valorados mediante rúbrica analítica y lista de cotejo según correspondencia con los resultados de aprendizaje de la unidad, exactitud de las tablas de verdad completas, rigor algebraico en la simplificación y validación funcional en simulador, dentro del esquema de calificación vigente en Moodle.
- CASO_PRACTICO_INTRODUCTORIO:
  En la plataforma financiera ficticia *PagoAndes*, el equipo detectó un fallo crítico en su regla automática de aprobación de microcréditos: un programador tradujo mal un requerimiento y escribió una expresión booleana con tres negaciones anidadas que aprueba solicitudes fuera de límite mientras rechaza a clientes con historial limpio. Usted asumirá la auditoría formal de las reglas del negocio, construirá las tablas de verdad completas, aplicará las leyes de De Morgan para simplificar el criterio y validará la equivalencia lógica en un simulador web.
- REDIRECCION_GUIA_PRACTICAS:
  Una vez dominados los operadores lógicos y avanzado su Trabajo Autónomo, continúe con la ejecución guiada en simuladores en la [Guía de Prácticas, Unidad 1, Práctica 1: Construcción de tablas de verdad y simplificación de expresiones lógicas](../04_Guias_Practicas_V2/GP_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md).

### UNIDAD 2: Datos, información y estructuras de datos fundamentales
- RESULTADOS_APRENDIZAJE:
  Utiliza estructuras básicas de datos para organizar información en entornos digitales. Específicamente: diferencia datos de información relacionando su representación digital con tipos de datos primitivos; estructura colecciones de datos compuestas mediante registros, tuplas y campos tipificados; modela el comportamiento operativo de listas, pilas bajo el principio último en entrar, primero en salir (LIFO) y colas bajo el principio primero en entrar, primero en salir (FIFO) según las reglas de acceso a elementos; y selecciona la estructura de datos más eficiente considerando el tipo de acceso y persistencia requerida en el problema.
- OBJETIVO_UNIDAD:
  Clasificar y manipular estructuras de datos lineales y registros para representar colecciones de información en entornos digitales.
- CONTENIDOS:
  - **Semana 3: Dato, información, representación binaria y tipos de datos.**
    2.1 Concepto de dato, información y su representación binaria y digital.
    2.2 Tipos de datos primitivos y compuestos.
  - **Semana 4: Estructuras lineales de datos y estructuras de registros y tuplas.**
    2.3 Estructuras lineales de datos: listas, pilas de tipo último en entrar, primero en salir (LIFO) y colas de tipo primero en entrar, primero en salir (FIFO).
    2.4 Estructuras de registros, campos y tuplas de datos.

  **Desarrollo conceptual.** En computación, un **dato** es un símbolo o valor aislado sin contexto (por ejemplo, "18.50" o "01000001"), mientras que la **información** surge cuando ese dato recibe significado, estructura y contexto (*"Precio unitario de venta: 18,50 dólares"* o *"Carácter 'A' codificado en texto estándar"*). Toda información se almacena finalmente como secuencias de ceros y unos en **representación binaria**, por lo que una misma secuencia de bits puede interpretarse como número entero, letra o valor lógico según el **tipo de dato** asignado. Los **tipos de datos primitivos** representan unidades elementales (números enteros, números decimales o flotantes, valores booleanos verdadero/falso y caracteres o cadenas de texto), mientras que los **tipos compuestos** agrupan múltiples valores en unidades estructuradas.

  Entre los tipos compuestos esenciales destacan el **registro** (estructura que reúne varios **campos tipificados** que describen una misma entidad, por ejemplo un producto con código de texto, precio decimal y existencias enteras) y la **tupla** (colección ordenada de valores que representa una fila o conjunto estructurado de campos). Cuando necesitamos almacenar múltiples registros o elementos en secuencia, elegimos entre tres **estructuras lineales fundamentales** según cómo deben entrar y salir los datos:
  - **Lista:** colección ordenada que permite recorrer elementos secuencialmente, acceder por posición e insertar o eliminar en puntos definidos.
  - **Pila (LIFO: último en entrar, primero en salir):** solo permite insertar (**apilar**) y extraer (**desapilar**) por un único extremo superior llamado cima. Es la estructura natural para el historial "Deshacer" de un editor, la navegación "Atrás" de un navegador o la pila de llamadas de funciones.
  - **Cola (FIFO: primero en entrar, primero en salir):** inserta nuevos elementos al final (**encolar**) y retira siempre al elemento más antiguo por el frente (**desencolar**). Modela con exactitud turnos de atención, colas de impresión y despacho de pedidos por orden de llegada.

  Elegir mal entre una pila y una cola no es un simple detalle de dibujo: altera por completo el comportamiento de una aplicación y puede perjudicar gravemente a los usuarios finales.

  **Ejemplo didáctico resuelto (caso ficticio).** Considere la siguiente secuencia exacta de operaciones: ingresar "A", luego ingresar "B", luego ingresar "C", ejecutar un retiro, ingresar "D" y ejecutar un segundo retiro.
  - *Comportamiento en una pila (LIFO):* Tras ingresar A, B y C, la cima contiene "C". El primer retiro devuelve **"C"** (el último en llegar), dejando a "B" en la cima. Al ingresar "D", este queda encima; el segundo retiro devuelve **"D"**.
  - *Comportamiento en una cola (FIFO):* Tras ingresar A, B y C, el frente conserva a "A". El primer retiro devuelve **"A"** (el primero en llegar), avanzando "B" al frente. Al ingresar "D" al final, el segundo retiro devuelve **"B"**.
  - *Modelado con registro tipificado:* Si cada elemento representa un pedido en espera, se define como un registro con campos claros: identificador (entero), cliente (texto), monto (decimal) y urgente (booleano).

  **Ejercicio guiado para preparar el Trabajo Autónomo.** Al diseñar el catálogo de productos y los flujos de su Trabajo Autónomo 2, defina primero el tipo exacto de cada campo (entero, decimal, texto o booleano) para evitar operar texto como número, y trace manualmente el estado paso a paso tras cuatro operaciones seguidas en pila y cuatro en cola antes de pasar al simulador.
- METODOLOGIA_EN_LINEA:
  Semanas 3 y 4. Dedicación prevista: 12 horas de aprendizaje en contacto con el docente, 12 horas de aprendizaje práctico-experimental y 12 horas de aprendizaje autónomo (36 horas en total). Integra aprendizaje basado en modelado paso a paso, visualización interactiva de algoritmos en plataformas web (como Visualgo), diagramación estructurada y sustentación oral asincrónica con retroalimentación docente en Moodle.
- ACTIVIDADES_APRENDIZAJE:
  1. **Trabajo Autónomo de la Unidad 2 (100 % asincrónico):** Modelado estructurado de un catálogo de productos empleando registros con campos y tipos bien definidos, acompañado de la representación analítica de flujos en pilas (LIFO) y colas (FIFO) y la justificación técnica de qué estructura conviene según tipo de acceso y persistencia. En la semana 3 diseñará la especificación binaria, tipos primitivos y registros del catálogo; en la semana 4 incorporará los flujos lineales y criterios de selección, entregando un único documento en Moodle al cierre de la semana 4.
  2. **Trabajo Práctico-Experimental de la Unidad 2 (100 % asincrónico):** Representación gráfica y simulación paso a paso de operaciones de apilado, encolado y recorrido de elementos en listas, pilas, colas y registros mediante herramientas visuales interactivas, integrando una breve sustentación oral en audio o video asincrónico (o intercambio secuencial documentado) dentro del mismo expediente. Su desarrollo completo figura en la Práctica 2 de la Guía de Prácticas y se entrega al cierre de la semana 4.
- RECURSOS_MEDIACION_TECNOLOGICA:
  Aula virtual en Moodle (espacio de seguimiento y entrega), equipo informático con conexión a internet, plataformas web gratuitas de simulación de estructuras de datos (como Visualgo.net), editores de diagramas de flujo y estructuras (como Draw.io), grabadora de audio o video para la explicación oral asincrónica, y asistentes de inteligencia artificial (IA) usados de manera ética para generar casos de prueba paso a paso sobre pilas y colas y contrastar trazas manuales.
- EVALUACION_UNIDAD:
  - **Semana 3 (evaluación formativa):** Revisión en Moodle de la definición tipificada de registros y los primeros esquemas de flujo del Trabajo Autónomo 2 y la Práctica 2, con devolución docente para corregir tipos incompatibles o errores de orden antes de la entrega definitiva.
  - **Semana 4 (evaluación sumativa de la unidad):** Entrega única en Moodle de ambos productos (Trabajo Autónomo 2 y Trabajo Práctico-Experimental 2), evaluados con rúbrica analítica y lista de cotejo según distinción entre dato e información, tipificación correcta de registros, exactitud paso a paso en simulaciones de pila, cola y lista, justificación de eficiencia y claridad de la explicación oral asincrónica.
- CASO_PRACTICO_INTRODUCTORIO:
  En la aplicación ficticia de farmacia y logística *FarmaRápida*, el equipo de desarrollo cometió un error estructural grave: almacenó los pedidos en línea de los clientes en una pila (LIFO) y el historial de acciones "Deshacer" del editor de recetas en una cola (FIFO). Como consecuencia, los primeros compradores quedan esperando indefinidamente mientras se despachan los pedidos más recientes, y al presionar "Deshacer" se borra la corrección más antigua en lugar del último error digitado. Usted simulará, corregirá y explicará la reestructuración completa de estos flujos.
- REDIRECCION_GUIA_PRACTICAS:
  Con los tipos de datos y reglas de acceso claras y su Trabajo Autónomo encaminado, pase a simular y diagramar el caso completo en la [Guía de Prácticas, Unidad 2, Práctica 2: Diagramación y simulación paso a paso de pilas, colas y recorridos](../04_Guias_Practicas_V2/GP_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md).

### UNIDAD 3: Organización de datos en tablas y relaciones del modelo relacional
- RESULTADOS_APRENDIZAJE:
  Diseña esquemas de bases de datos relacionales asegurando la integridad referencial y reduciendo redundancias mediante normalización básica. Específicamente: diseña tablas identificando campos, dominios de datos y claves primarias para garantizar la unicidad de registros; establece relaciones de cardinalidad uno a uno (1:1) y uno a muchos (1:N) vinculando tablas mediante claves foráneas; preserva la integridad referencial y de dominio en las relaciones estructuradas entre entidades; y aplica las formas normales fundamentales —Primera Forma Normal (1FN), Segunda Forma Normal (2FN) y Tercera Forma Normal (3FN)— para mitigar anomalías de inserción, actualización y borrado.
- OBJETIVO_UNIDAD:
  Diseñar modelos de tablas y relaciones lógicas aplicando conceptos de claves primarias, claves foráneas e integridad referencial.
- CONTENIDOS:
  - **Semana 5: Conceptos del modelo relacional e identificadores únicos (claves primarias).**
    3.1 Conceptos del modelo relacional: tablas, filas (registros) y columnas (campos).
    3.2 Identificadores únicos y claves primarias (Primary Key).
  - **Semana 6: Claves foráneas, integridad referencial y normalización básica.**
    3.3 Integridad de datos y relaciones entre tablas mediante claves foráneas (Foreign Key).
    3.4 Nociones de normalización básica —Primera Forma Normal (1FN), Segunda Forma Normal (2FN) y Tercera Forma Normal (3FN)— para evitar redundancias.

  **Desarrollo conceptual.** Cuando los datos de un sistema deben persistir de forma segura y compartida por múltiples usuarios, el **modelo relacional** los organiza en **tablas** interconectadas. Cada tabla representa una entidad (por ejemplo, Clientes o Pedidos); cada **fila o registro** corresponde a una instancia concreta y cada **columna o campo** almacena un atributo con un **dominio de datos** definido (tipo entero, texto de longitud máxima, fecha o monto decimal).

  Para garantizar que ningún registro se confunda con otro ni quede duplicado ambiguamente, toda tabla requiere una **clave primaria**: uno o más campos que identifican de manera **única y obligatoria (no nula)** a cada fila. Conviene elegir claves primarias estables (como un identificador numérico o código interno de cliente) y no atributos que cambian con el tiempo, como un número telefónico o una dirección de correo electrónico. Para enlazar dos tablas manteniendo la consistencia del sistema se utiliza la **clave foránea**: un campo en la tabla hija que apunta exactamente hacia la clave primaria de la tabla padre, garantizando la **integridad referencial** (es decir, impidiendo registrar un pedido perteneciente a un cliente inexistente o borrar un cliente dejando pedidos huérfanos sin control).

  Según las reglas del negocio, las tablas se vinculan mediante **cardinalidades**: **uno a uno (1:1)** (por ejemplo, un empleado y su ficha médica confidencial), **uno a muchos (1:N)** (un cliente puede realizar muchos pedidos, pero cada pedido pertenece a un solo cliente) y **muchos a muchos (N:M)** (un pedido incluye varios productos y un producto aparece en varios pedidos), la cual se resuelve creando una tabla intermedia (como Detalle_Pedido).

  Finalmente, diseñar buenas tablas evita **anomalías de inserción, actualización y borrado** aplicando de manera ordenada las tres formas normales básicas:
  - **Primera Forma Normal (1FN):** cada celda debe guardar un solo valor atómico; nunca mezcle varios productos separados por comas en una misma columna ni repita columnas numeradas como "producto_1, producto_2".
  - **Segunda Forma Normal (2FN):** estando en Primera Forma Normal, todo atributo no clave debe depender de toda la clave primaria completa (si la clave de Detalle_Pedido es compuesta por código de pedido y código de producto, la descripción del producto no depende del pedido, sino únicamente del producto, así que debe vivir en la tabla Productos).
  - **Tercera Forma Normal (3FN):** estando en Segunda Forma Normal, ningún campo no clave debe depender transitivamente de otro campo no clave (por ejemplo, si el nombre de la provincia o la tarifa de impuesto depende del código de ciudad y no directamente del pedido, se separa en su propia tabla de referencia).

  **Ejemplo didáctico resuelto (caso ficticio).** Considere una tabla desordenada llamada "Ventas_Planas" con las columnas: id_pedido, fecha, nombre_cliente, telefono_cliente, productos_comprados y ciudad_cliente. Una fila registra: "101 | 2026-03-10 | Sofía Pérez | 0991234567 | Cuaderno, Lápiz | Quito".
  - *Anomalías detectadas:* No cumple Primera Forma Normal porque "productos_comprados" mezcla dos ítems en una sola celda; si Sofía cambia de teléfono habrá que actualizar decenas de filas (anomalía de actualización); si se borra el pedido 101 desaparece todo rastro del cliente (anomalía de borrado); y no es posible registrar un producto nuevo si nadie lo ha comprado aún (anomalía de inserción).
  - *Modelo relacional normalizado:* Se separa en cuatro tablas claras: **Clientes** (id_cliente como clave primaria, nombre, teléfono, id_ciudad como clave foránea), **Ciudades** (id_ciudad, nombre_ciudad), **Productos** (id_producto, nombre_producto, precio_unitario) y **Pedidos** (id_pedido como clave primaria, fecha, id_cliente como clave foránea que apunta a Clientes), más **Detalle_Pedido** (id_pedido e id_producto como claves foráneas y cantidad). Al aplicar la clave foránea en Pedidos, el sistema bloquea automáticamente cualquier intento de insertar un pedido con un id_cliente que no exista en Clientes.

  **Ejercicio guiado para preparar el Trabajo Autónomo.** Al diseñar el diagrama entidad-relación lógico en su Trabajo Autónomo 3, ponga a prueba su esquema con tres filas ficticias e intente responder: si cambia el correo del cliente, ¿en cuántas tablas debe modificarlo? Si solo cambia en una celda, su normalización va por buen camino.
- METODOLOGIA_EN_LINEA:
  Semanas 5 y 6. Dedicación prevista: 12 horas de aprendizaje en contacto con el docente, 12 horas de aprendizaje práctico-experimental y 12 horas de aprendizaje autónomo (36 horas en total). Combina estudio conceptual del modelo relacional, análisis de anomalías en casos reales, diseño lógico en herramientas web de modelado (como dbdiagram.io o Draw.io) e intercambio técnico asincrónico en Moodle sobre decisiones de normalización.
- ACTIVIDADES_APRENDIZAJE:
  1. **Trabajo Autónomo de la Unidad 3 (100 % asincrónico):** Diseño del diagrama entidad-relación lógico para un caso práctico de gestión académica o comercial, especificando entidades, atributos, tipos de datos, claves primarias, claves foráneas, cardinalidades y justificación de normalización hasta tercera forma normal. En la semana 5 modelará entidades, atributos y claves primarias; en la semana 6 integrará relaciones, restricciones de integridad referencial y normalización, entregando un único documento consolidado en Moodle al cierre de la semana 6.
  2. **Trabajo Práctico-Experimental de la Unidad 3 (100 % asincrónico):** Construcción paso a paso del esquema relacional normalizado de tablas para una tienda virtual en línea (definiendo dominios, claves primarias, claves foráneas y verificación con datos de prueba frente a anomalías de inserción, actualización y borrado). Su desarrollo íntegro figura en la Práctica 3 de la Guía de Prácticas y se entrega al cierre de la semana 6.
- RECURSOS_MEDIACION_TECNOLOGICA:
  Aula virtual en Moodle (repositorios, foros o espacios de intercambio técnico sobre esquemas relacionales y entrega de trabajos), equipo informático con conexión a internet, herramientas gratuitas de diseño relacional en línea o locales (dbdiagram.io, Draw.io, MySQL Workbench o equivalentes), procesadores de texto y consultas éticas a inteligencia artificial (IA) para contrastar cardinalidades (uno a muchos frente a muchos a muchos) y verificar dependencias funcionales antes de validar el esquema propio con datos de ensayo.
- EVALUACION_UNIDAD:
  - **Semana 5 (evaluación formativa):** Revisión en Moodle del listado de entidades, dominios y claves primarias propuestas en el Trabajo Autónomo 3 y la Práctica 3, con observaciones del docente para corregir claves inestables o columnas multivaluadas antes de normalizar.
  - **Semana 6 (evaluación sumativa de la unidad):** Entrega única en Moodle de ambos trabajos de la unidad (Trabajo Autónomo 3 y Trabajo Práctico-Experimental 3), valorados mediante rúbrica analítica y lista de cotejo considerando unicidad de claves primarias, precisión de cardinalidades y claves foráneas, aplicación correcta de Primera, Segunda y Tercera Forma Normal y comprobación con filas de ensayo.
- CASO_PRACTICO_INTRODUCTORIO:
  La tienda virtual ficticia *MercadoSierra en Línea* administra actualmente todos sus pedidos en una única tabla plana donde cada fila amontona nombres de productos separados por comas, duplica el correo y la dirección del cliente en cada compra y mezcla el porcentaje de impuesto por categoría dentro del detalle de venta. Como resultado, al corregir el precio de un artículo o eliminar un pedido cancelado, se corrompen reportes y se pierden datos de clientes. Usted rediseñará y normalizará por completo el esquema relacional de la tienda.
- REDIRECCION_GUIA_PRACTICAS:
  Una vez definidas las entidades y las reglas de normalización en su Trabajo Autónomo, construya y valide el esquema relacional completo de la tienda virtual en la [Guía de Prácticas, Unidad 3, Práctica 3: Modelado del esquema de tablas relacionales para tienda virtual](../04_Guias_Practicas_V2/GP_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md).

### UNIDAD 4: Fundamentos de consultas y gestión de datos con SQL
- RESULTADOS_APRENDIZAJE:
  Construye consultas en lenguaje de consulta estructurado (SQL) para la extracción, filtrado y ordenamiento de información en bases de datos relacionales. Específicamente: formula sentencias SELECT y FROM para proyectar columnas específicas a partir de tablas relacionales; aplica cláusulas WHERE combinando operadores lógicos y relacionales (AND, OR, NOT, BETWEEN, LIKE) para filtrar registros; ordena conjuntos de resultados mediante ORDER BY de forma ascendente y descendente bajo múltiples criterios; y emplea funciones de conteo y agregación básica (COUNT) para generar resúmenes informativos de la base de datos.
- OBJETIVO_UNIDAD:
  Formular consultas de selección, filtrado y agregación de datos mediante lenguaje SQL básico para la gestión efectiva de la información.
- CONTENIDOS:
  - **Semana 7: Motores de bases de datos relacionales y operaciones fundamentales en SQL.**
    4.1 Introducción a los motores de base de datos relacionales y lenguaje de consulta estructurado (SQL).
    4.2 Operaciones fundamentales: proyección y selección con SELECT y FROM.
  - **Semana 8: Filtrado compuesto, ordenamiento, conteo básico y buenas prácticas.**
    4.3 Filtrado de datos con condiciones compuestas (WHERE, AND, OR, NOT, BETWEEN, LIKE).
    4.4 Ordenamiento (ORDER BY), conteo básico (COUNT) y buenas prácticas en la gestión de datos.

  **Desarrollo conceptual.** Una vez que los datos viven ordenados en tablas normalizadas, necesitamos consultarlos de forma exacta y segura. Un **motor de base de datos relacional** (como PostgreSQL o SQLite) gestiona el almacenamiento físico, valida los tipos y claves y responde a instrucciones escritas en **lenguaje de consulta estructurado (SQL)**. Toda consulta de lectura combina bloques con significado lógico preciso, heredado directamente de la Unidad 1:
  - **SELECT y FROM:** la cláusula FROM indica de qué tabla se extraen los datos y SELECT **proyecta** únicamente las columnas necesarias (por ejemplo: SELECT nombre, ciudad FROM clientes). Evitar pedir columnas innecesarias mejora claridad y rendimiento.
  - **WHERE con operadores relacionales y booleanos:** filtra fila por fila conservando solo las que evalúan verdadero ante la condición dada. Además de comparaciones numéricas o de texto ("=", "<>", ">", "<="), permite combinar criterios con **AND**, **OR** y **NOT**, especificar rangos inclusivos con **BETWEEN** (por ejemplo, precio BETWEEN 10 AND 30 incluye tanto 10 como 30) y buscar patrones de texto con **LIKE** usando "%" para cualquier secuencia de caracteres y "_" para un solo carácter. Recuerde una regla crítica de precedencia: **AND tiene mayor prioridad que OR**, por lo que siempre debe usar **paréntesis** cuando mezcle ambos operadores para no alterar el sentido lógico de su consulta. Además, la ausencia de dato se representa con el marcador especial NULL y se comprueba con **IS NULL** o **IS NOT NULL** (nunca con "= NULL").
  - **ORDER BY y COUNT:** la cláusula **ORDER BY** ordena los resultados devueltos en sentido ascendente (**ASC**, predeterminado) o descendente (**DESC**), pudiendo encadenar varios criterios (por ejemplo, primero por ciudad ascendente y luego por monto descendente). La función de agregación **COUNT(columna)** devuelve la cantidad de filas con valor no nulo en dicha columna, permitiendo resúmenes rápidos y confiables.

  En la gestión responsable de datos rigen tres **buenas prácticas** indispensables: (1) verifique la sintaxis exacta de comillas simples para literales de texto según el motor utilizado (por ejemplo, WHERE ciudad = 'Quito'); (2) antes de ejecutar instrucciones que modifican información (INSERT, UPDATE o DELETE), trabaje sobre una copia de respaldo y pruebe previamente el filtro con un SELECT para comprobar qué filas exactas serán afectadas; y (3) trate siempre los datos ingresados por usuarios como parámetros separados y nunca los concatene directamente como texto dentro de comandos SQL.

  **Ejemplo didáctico resuelto (caso ficticio).** Considere una tabla ficticia "clientes" con cinco filas: (1) Ana, Quito, activo = 1; (2) Luis, Cuenca, activo = 1; (3) Sofía, Quito, activo = 0; (4) Pedro, Loja, activo = 1; (5) Carla, Cuenca, activo = 0. Un reporte pide *"clientes activos que vivan en Quito o en Cuenca"*.
  - *Consulta defectuosa (sin paréntesis):* SELECT id_cliente, nombre, ciudad FROM clientes WHERE ciudad = 'Quito' OR ciudad = 'Cuenca' AND activo = 1;
    Debido a que AND se evalúa primero que OR, el motor interpreta "todos los de Quito (activos o inactivos), o bien los de Cuenca que estén activos", devolviendo erróneamente a Sofía (Quito, inactiva).
  - *Consulta correcta (con paréntesis explícitos):* SELECT id_cliente, nombre, ciudad FROM clientes WHERE (ciudad = 'Quito' OR ciudad = 'Cuenca') AND activo = 1 ORDER BY ciudad ASC, nombre ASC;
    Ahora devuelve exactamente dos filas válidas: Luis (Cuenca) y Ana (Quito). Asimismo, una consulta simple como SELECT nombre FROM clientes WHERE ciudad = 'Quito' devolverá a Ana y Sofía mientras coincidan exactamente las comillas simples y mayúsculas del literal.

  **Ejercicio guiado para preparar el Trabajo Autónomo.** Antes de escribir su script de diez requerimientos en el Trabajo Autónomo 4, anote al lado de cada consulta qué filas espera ver antes de ejecutarla en SQLite o PostgreSQL; si el resultado obtenido en pantalla difiere del esperado, revise paréntesis, rangos BETWEEN o valores nulos.
- METODOLOGIA_EN_LINEA:
  Semanas 7 y 8. Dedicación prevista: 12 horas de aprendizaje en contacto con el docente, 12 horas de aprendizaje práctico-experimental y 12 horas de aprendizaje autónomo (36 horas en total). Combina estudio conceptual de sintaxis SQL, experimentación directa en motores reales (PostgreSQL o SQLite) o entornos interactivos en la nube, verificación de resultados esperados frente a obtenidos y retroalimentación continua en Moodle.
- ACTIVIDADES_APRENDIZAJE:
  1. **Trabajo Autónomo de la Unidad 4 (100 % asincrónico):** Elaboración de un script SQL comentado y documentado que resuelva diez requerimientos concretos de extracción, filtrado compuesto, ordenamiento multicriterio y conteo básico sobre una base de datos de prueba, comparando filas esperadas frente a resultados ejecutados. En la semana 7 diseñará y probará consultas de proyección SELECT, FROM y filtros simples; en la semana 8 completará filtros compuestos, ordenamiento, conteo y buenas prácticas de seguridad, entregando el expediente único en Moodle al cierre de la semana 8.
  2. **Trabajo Práctico-Experimental de la Unidad 4 (100 % asincrónico):** Laboratorio práctico de ejecución interactiva de sentencias SQL de consulta, filtrado lógico compuesto, ordenamiento y conteo sobre una base de datos relacional de prueba en PostgreSQL, SQLite o entorno interactivo en la nube, verificando condiciones normales, límites y errores de precedencia. Su desarrollo paso a paso figura en la Práctica 4 de la Guía de Prácticas y se entrega al cierre de la semana 8.
- RECURSOS_MEDIACION_TECNOLOGICA:
  Aula virtual en Moodle, equipo informático con conexión a internet, motores de bases de datos gratuitos (SQLite o PostgreSQL), clientes SQL libres (DBeaver, DB Browser for SQLite o pgAdmin), entornos interactivos de ejecución SQL en navegador web (como DB Fiddle, SQLFiddle o el editor SQL de W3Schools) y asistentes de inteligencia artificial (IA) consultados éticamente para explicar errores de sintaxis o analizar planes lógicos de filtrado (probando siempre cada consulta en el motor real y adjuntando la evidencia obtenida).
- EVALUACION_UNIDAD:
  - **Semana 7 (evaluación formativa):** Revisión en Moodle de la configuración del entorno SQL de prueba y las primeras consultas de proyección y selección del Trabajo Autónomo 4 y la Práctica 4, con devolución docente orientadora.
  - **Semana 8 (evaluación sumativa de la unidad):** Entrega única en Moodle de los dos productos finales de la unidad (Trabajo Autónomo 4 y Trabajo Práctico-Experimental 4), evaluados mediante rúbrica analítica y lista de cotejo según corrección sintáctica en SQL, uso exacto de operadores y paréntesis, verificación de resultados ejecutados en la base de ensayo y aplicación de buenas prácticas de gestión segura de datos.
- CASO_PRACTICO_INTRODUCTORIO:
  En la librería digital ficticia *LecturaViva*, el área comercial necesita extraer seis reportes confiables sobre su base de datos de clientes, libros y pedidos, después de que consultas anteriores sin paréntesis reportaran clientes inactivos como vigentes y fallaran al filtrar rangos de fechas y patrones de texto. Usted cargará la base de prueba en PostgreSQL, SQLite o un entorno SQL web, ejecutará las consultas corregidas, comprobará filas límite y documentará evidencias reales de salida.
- REDIRECCION_GUIA_PRACTICAS:
  Una vez diseñadas sus consultas en el Trabajo Autónomo, culmine la asignatura ejecutando y verificando el laboratorio SQL completo en la [Guía de Prácticas, Unidad 4, Práctica 4: Ejecución interactiva de consultas y filtrado de datos con SQL](../04_Guias_Practicas_V2/GP_DSOF-B1-03_Logica_Matematica_y_Gestion_de_Datos_V2.md).

## 5. REFERENCIAS BIBLIOGRÁFICAS EN FORMATO APA

### BIBLIOGRAFIA_BASICA
- Levin, O. (2024). *Discrete Mathematics: An Open Introduction* (4.ª ed.). University of Northern Colorado / Open Access Textbooks. https://discrete.openmathbooks.org/pdfs/dmoi4-tablet.pdf
- Watt, A. y Eng, N. (2023). *Database Design* (2.ª ed.). BCcampus Open Education. https://opentextbc.ca/dbdesign01/
- Doerr, A. y Levasseur, K. (2024). *Applied Discrete Structures* (Versión 3.10). UMass Lowell / Open Access Books. https://discretemath.org/ads/ads.pdf

### BIBLIOGRAFIA_COMPLEMENTARIA
- DeBarros, A. (2022). *Practical SQL: A Beginner’s Guide to Storytelling with Data* (2.ª ed.). No Starch Press.
- Stephens, R. (2023). *Beginning Database Design Solutions: Understanding and Implementing Database Design Concepts for the Cloud and Beyond* (2.ª ed.). Wiley.
- PostgreSQL Global Development Group (2024). *Documentación oficial de PostgreSQL en español*. https://www.postgresql.org/docs/
