# Análisis de datos en Investigación

Material educativo para estudiantes de **Ventas Digitales**.

**Fuentes curriculares.** [PEA V2](../../01_PEAs_V2/PEA_VENDIG-B3-13_AnalisisDatosInvestigacion_V2.md) · [Syllabus V2](../../02_Silabos_V2/SYL_VENDIG-B3-13_AnalisisDatosInvestigacion_V2.md) · [Guía didáctica V1](../../03_Guias_Didacticas_V1/GD_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md) · [Guía de prácticas V1](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md)

Análisis de datos en Investigación es una asignatura de la Unidad Básica de carácter práctico-teórico. Desarrolla competencias para preparar, depurar, analizar y visualizar datos comerciales mediante herramientas ofimáticas avanzadas y asistentes de inteligencia artificial, facilitando la toma de decisiones basada en evidencias. Aborda limpieza de datos, estadística descriptiva aplicada al comercio, visualización en gráficos interactivos y técnicas básicas de clasificación y segmentación de información. Mediante talleres guiados en hojas de cálculo y resolución de problemas con datos reales de ventas, el estudiante transforma bases de datos desorganizadas en reportes e indicadores ejecutivos comprensibles, con rigor analítico, principios de integridad y responsabilidad profesional.

## Contenido del material

- [Unidad 1. Preparación, limpieza y organización de datos](#unidad-1)
- [Unidad 2. Análisis descriptivo de información](#unidad-2)
- [Unidad 3. Visualización e interpretación para la toma de decisiones](#unidad-3)
- [Unidad 4. IA, clasificación y segmentación de información](#unidad-4)

<a id="unidad-1"></a>

## Unidad 1: Preparación, limpieza y organización de datos

![Análisis de datos en Investigación · Unidad 1. Datos originales. Tipos y formatos. Duplicados y atípicos. Bitácora de cambios. Resultado: Una copia limpia con historial de cambios](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 01/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Crea una escena de depuración de una base comercial con una tabla de origen y una versión revisada. Diferencia columnas de categorías, recuentos e importes; resalta una fecha mal formada, un duplicado, una celda vacía y un valor atípico. Conecta los cambios con una bitácora visible y usa identificadores anónimos en los ejemplos. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Un dato aislado (como la cifra "45,80") carece de significado hasta que se organiza en una tabla con definición clara de variable, unidad de medida, escala y periodo. Antes de calcular indicadores de ventas, resulta indispensable clasificar cada columna: las **variables cualitativas nominales** identifican categorías sin orden jerárquico (como ciudad o canal de compra); las **variables ordinales** expresan rango o nivel (como escala de satisfacción del 1 al 5); y las **variables cuantitativas** miden cantidades o montos en dólares estadounidenses (USD) que admiten medias y sumas.

El caso de la unidad guía este recorrido: **Entrada → Clasificación → Depuración → Bitácora**.

### Resultados de aprendizaje

El estudiante depura una base de datos comercial eliminando errores de formato, valores atípicos y registros duplicados con trazabilidad.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Estructura de datos y tipos de variables en ventas | Variables cualitativas y cuantitativas<br>escalas de medición<br>formatos de fecha, moneda y texto. |
| 2. Técnicas de depuración y tratamiento de valores ausentes | Detección de duplicados<br>filtros avanzados<br>manejo de celdas vacías y errores comunes (#N/A, #¡VALOR!). |

### Caso inicial

La empresa ecuatoriana ficticia *AndesMarket Comercio Digital* (caso simulado disponible en su versión de comercio minorista o servicios digitales) consolidó en un solo archivo las ventas recientes de seis meses procedentes de su tienda web, mensajería directa y asesores comerciales. Al revisar las **200 transacciones comerciales** y la lista de clientes, el área administrativa descubrió nombres personales sin anonimizar, fechas escritas en tres formatos distintos, montos mezclados con texto, celdas vacías, registros repetidos y errores de búsqueda en fórmulas. Antes de calcular métricas confiables, usted deberá organizar, anonimizar y depurar íntegramente la base dejando rastro de cada cambio.

### Tema 1: Estructura de datos y tipos de variables en ventas

#### 1.1. Variables cualitativas y cuantitativas

**Desarrollo técnico y aplicación.** Un tipo primitivo representa un valor básico y uno compuesto organiza varios. La elección afecta operaciones y validaciones. Un importe expresado como texto no se suma del mismo modo que un número; una conversión aceptada por el lenguaje puede seguir siendo inválida para el negocio. Valide tipo, dominio y relación con otros campos por separado.

Clasifica variables antes de operar con ellas. Un medio de pago es cualitativo y una cantidad de pedidos, cuantitativa. Una categoría codificada como número conserva su carácter categórico.

**Fundamento y alcance.** Una variable representa un atributo de la unidad observada. Su tipo condiciona qué recuentos, comparaciones o cálculos se pueden interpretar válidamente.

**Caso aplicado.** Una tabla guarda medio de pago con códigos 1, 2 y 3.

**Resolución.** Clasifica como nominal y usa el código para contar casos por categoría.

**Error frecuente y cómo detectarlo.** Promediar el código no describe un medio de pago típico.

**Comprueba tu comprensión.** ¿Qué resumen tiene sentido para medios de pago?

**Respuesta comentada.** Frecuencias y porcentajes por categoría, con una base explícita.

![Cualitativa. El medio de pago admite un recuento por categoría. Ordinal. Un nivel de satisfacción permite ordenar respuestas. Cuantitativa. El monto en dólares permite comparar magnitudes. Un código numérico puede representar una categoría.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 01/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Variables cualitativas y cuantitativas». Para el primer panel usa esta situación. Una tabla guarda medio de pago con códigos 1, 2 y 3. En el segundo, representa esta acción. Clasifica como nominal y usa el código para contar casos por categoría. En el último, incorpora esta comprobación. Frecuencias y porcentajes por categoría, con una base explícita. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. escalas de medición

**Desarrollo técnico y aplicación.** Las escalas determinan operaciones interpretables. Los códigos de categorías no se promedian por estar escritos con números y una escala ordinal no garantiza distancias iguales entre opciones. Identifique qué significa comparar, ordenar o restar en la variable del caso. La apariencia de una columna no sustituye definir su significado antes de seleccionar una medida descriptiva.

Las escalas nominales distinguen clases y las ordinales incorporan orden. Las medidas cuantitativas permiten operaciones según la escala. Identifica qué cálculo tiene sentido antes de interpretar promedios y proporciones.

**Fundamento y alcance.** La escala nominal distingue categorías; la ordinal agrega orden; las medidas cuantitativas permiten comparar magnitudes bajo una unidad. Los códigos deben conservar el significado original.

**Caso aplicado.** La satisfacción se registra en tres niveles ordenados y el monto en dólares.

**Resolución.** Compara posiciones para la primera variable y distancias para el monto.

**Error frecuente y cómo detectarlo.** El orden entre niveles no garantiza que los saltos sean iguales.

**Comprueba tu comprensión.** ¿Puedes restar dos niveles ordinales como si fueran dólares?

**Respuesta comentada.** Puedes ordenar niveles; una diferencia numérica exige justificar distancias.

#### 1.3. formatos de fecha, moneda y texto.

**Desarrollo técnico y aplicación.** CSV conserva una estructura tabular bajo convenciones de separadores y formatos; JSON permite estructuras anidadas y Parquet organiza datos bajo otro formato de almacenamiento. La elección afecta tipos y lectura. Exportar puede cambiar fechas o identificadores si no se especifican convenciones. Después de convertir, compruebe filas, columnas, tipos y algunos valores críticos antes de utilizar el archivo como equivalente.

Normaliza fecha, moneda y texto en una copia. Documenta el formato de salida y conserva el valor de origen. Comprueba que la tabla ordene fechas cronológicamente y sume importes como números.

**Fundamento y alcance.** La normalización unifica presentación y tipos de datos sin alterar lo que cada registro mide. Verifica formatos de fecha, texto y moneda antes de usar el conjunto en fórmulas.

**Caso aplicado.** La fecha 04/05 se interpreta de dos maneras al importar.

**Resolución.** Confirma el formato de origen y convierte una muestra antes de aplicar a la columna.

**Error frecuente y cómo detectarlo.** Una fecha válida para el programa puede ser errónea para el reporte.

**Comprueba tu comprensión.** ¿Qué prueba detecta la inversión de día y mes?

**Respuesta comentada.** Compara registros conocidos con el documento original después de importar.

### Tema 2: Técnicas de depuración y tratamiento de valores ausentes

#### 2.1. Detección de duplicados

**Desarrollo técnico y aplicación.** El perfilado identifica tipos, valores distintos, rangos, ausencias y patrones de formato. Sus resultados orientan revisión y no prueban calidad completa. Un identificador puede parecer numérico y necesitar texto para conservar ceros. Examine una muestra de registros y explique qué reglas detectaron cada problema. Una sugerencia automática necesita contrastarse con el significado de la variable.

Identifica duplicados por clave del evento y confirma con campos de origen. Dos pedidos de igual importe de un mismo cliente pueden ser distintos. Registra el motivo de cada exclusión y el total de filas afectadas.

**Fundamento y alcance.** Un duplicado repite la misma observación según una clave y reglas de negocio. Su tratamiento debe poder reconstruirse con la fuente y una bitácora de ajustes.

**Caso aplicado.** Dos filas con la clave A tienen igual monto y canal.

**Resolución.** Contrasta ambos registros con el respaldo y deja identificada la fila excluida.

**Error frecuente y cómo detectarlo.** Una clave repetida puede corresponder a una corrección y requiere revisar el historial.

**Comprueba tu comprensión.** ¿Qué conserva la bitácora de un duplicado?

**Respuesta comentada.** Clave, fila evaluada, criterio, respaldo y decisión.

#### 2.2. filtros avanzados

**Desarrollo técnico y aplicación.** Un filtro selecciona registros bajo condiciones y puede ocultar parte del conjunto sin eliminarla. Guarde criterio y base inicial para interpretar totales. Combine condiciones con paréntesis cuando existan alternativas. Antes de concluir que faltan ventas, revise qué filas quedaron excluidas y si las categorías contienen variantes de escritura o tipos incompatibles.

Los filtros avanzados aíslan registros para inspección. Filtra por condición, cuenta resultados y conserva la vista original. Si ajustas un punto atípico, explica si era un error o un caso válido.

**Fundamento y alcance.** Un filtro selecciona filas bajo criterios explícitos. Es útil para investigar registros extremos, condiciones inválidas y posibles duplicados sin alterar inmediatamente la base.

**Caso aplicado.** Se filtran pedidos con importe inferior a cero.

**Resolución.** Separa devoluciones válidas de errores y registra el criterio para cada grupo.

**Error frecuente y cómo detectarlo.** Un filtro oculta filas y no modifica automáticamente su validez.

**Comprueba tu comprensión.** ¿Qué harías con un negativo justificado?

**Respuesta comentada.** Consérvalo como devolución bajo la regla establecida.

#### 2.3. manejo de celdas vacías y errores comunes (#N/A, #¡VALOR!).

**Desarrollo técnico y aplicación.** La imputación incorpora valores bajo una regla y debe distinguirse de observaciones reales. Un vacío no es cero. Analice cantidad y origen posible de ausencias y registre el tratamiento. Una normalización de escala puede facilitar comparaciones y también alterar el peso de variables en una distancia. Explique su finalidad y conserve la posibilidad de reconstruir el conjunto previo.

Una celda vacía puede indicar que el dato falta. Un cero expresa un valor observado. Para errores de búsqueda o tipo de valor, revisa claves y formatos antes de sustituir resultados. Preserva el significado en la base final.

**Fundamento y alcance.** Los valores ausentes y los errores de fórmula tienen significados diferentes. Identifica el origen antes de imputar, excluir o etiquetar un resultado como pendiente.

**Caso aplicado.** Una fórmula de búsqueda devuelve no disponible para algunos pedidos.

**Resolución.** Revisa formato y coincidencia de la clave y conserva el estado pendiente si el dato falta.

**Error frecuente y cómo detectarlo.** Sustituir el error por cero puede convertir una ausencia en una venta nula.

**Comprueba tu comprensión.** ¿Qué significa una celda sin valor?

**Respuesta comentada.** Informará ausencia hasta identificar por qué falta el dato.

![Identifica. Revisa si falta el dato o si falló una búsqueda. Contrasta. Comprueba clave, formato y respaldo de origen. Decide. Conserva el estado pendiente cuando falta evidencia. Un valor ausente y un cero registrado tienen usos distintos.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 01/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «manejo de celdas vacías y errores comunes (#N/A, #¡VALOR!)». Para el primer panel usa esta situación. Una fórmula de búsqueda devuelve no disponible para algunos pedidos. En el segundo, representa esta acción. Revisa formato y coincidencia de la clave y conserva el estado pendiente si el dato falta. En el último, incorpora esta comprobación. Informará ausencia hasta identificar por qué falta el dato. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

Una regla técnica clave en análisis de datos es que un **código numérico que representa una categoría** (por ejemplo, código "1 = Quito, 2 = Guayaquil") nunca debe promediarse como si fuera una cantidad monetaria. Asimismo, toda base comercial cruda suele presentar anomalías: fechas registradas en formatos mezclados, símbolos monetarios combinados con texto, espacios sobrantes al inicio o final de una palabra, identificadores repetidos por doble carga y datos personales sensibles que deben **anonimizarse** (sustituyendo nombres o cédulas por códigos de cliente) antes de analizar o consultar herramientas externas.

Para resolver inconsistencias sin perder rigor, conserve siempre una copia intocable de la base original y realice la limpieza sobre una pestaña aparte documentando cada regla en una **bitácora de depuración** (indicando fila o columna afectada, error detectado, regla o fórmula aplicada y resultado). Recuerde además que una **celda vacía no equivale a cero**: si falta el monto de un pedido o la edad de un comprador, asignar un cero artificial distorsiona el promedio y la dispersión.

### Ejemplo aplicado y resuelto

**Situación simulada.** En una tabla hay dos apariciones del pedido A y una fecha en formato distinto. Compara los registros duplicados con el original y conserva una sola fila si corresponden al mismo evento. Normaliza la fecha y registra el cambio. Si una venta atípica tiene respaldo, describe su efecto antes de decidir el tratamiento analítico.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Formato | Fecha inconsistente | Normalización reproducible |
| Duplicado | Pedido A repetido | Verificación por identificador |
| Valor atípico | Venta alta con respaldo | Documentación del efecto |

**Ejemplo complementario de la guía didáctica.**

Suponga que revisa la columna de edad de cuatro compradores y encuentra: 28, 34, "sin respuesta" y 31; y en otra tabla de ventas individuales de accesorios encuentra un pedido de 1.850 dólares frente a tickets habituales entre 15 y 45 dólares.
- *Procedimiento erróneo:* Reemplazar "sin respuesta" por 0 y borrar sin investigar el pedido de 1.850 dólares. El cero bajaría falsamente la edad promedio a 23,25 años, y borrar el pedido alto ocultaría una venta corporativa real o un error de digitación.
- *Procedimiento riguroso:* Mantener la celda de edad como dato ausente documentado (calculando el promedio sobre las 3 respuestas válidas = 31 años) y verificar el pedido de 1.850 dólares contra el comprobante o la columna de unidades antes de clasificarlo como compra mayorista o error de punto decimal.

**Advertencia y error frecuente.** Al cambiar formatos, verifica que el programa no invirtió mes y día. Mantén una copia de referencia para reproducir cada modificación.

### Profundización técnica de la unidad

#### Tipos de variable y limpieza con significado

Las variables cualitativas identifican categorías; las cuantitativas expresan cantidades. Las escalas condicionan qué operaciones son interpretables. Un código de cliente compuesto por dígitos sigue siendo identificador y no una cantidad que deba promediarse. El formato visual de moneda o fecha no garantiza que el valor esté almacenado correctamente.

**Ejemplo resuelto.** Los códigos `001` y `010` se conservan como texto para mantener su forma. Los importes «20,50» y «20.50» necesitan interpretarse según la convención del archivo antes de sumarse. Una conversión incorrecta puede producir texto o cantidades alteradas sin ser evidente en la tabla.

Los duplicados se detectan mediante la clave de la unidad de registro. Las celdas vacías no se reemplazan automáticamente por cero. Los errores de búsqueda pueden indicar una clave ausente o un tipo incompatible; esconderlos con una fórmula que siempre devuelva cero impide detectar el problema. **Reflexión:** ¿qué cambio de tipo permitiría calcular y cuál destruiría información necesaria para identificar registros?

#### Datos y condiciones para estudiar el caso en detalle

La empresa ecuatoriana ficticia *AndesMarket Comercio Digital* (caso comercial simulado exclusivamente con fines formativos) descargó de su sistema de facturación y hojas auxiliares una base de **200 transacciones comerciales** acompañada de un directorio de clientes. Al inspeccionar el archivo habilitado en Moodle, aparecen inconsistencias típicas que impiden calcular ventas confiables:
- Fechas mezcladas entre texto y distintos órdenes de día, mes y año.
- Valores monetarios en dólares estadounidenses (USD) escritos con símbolos distintos o comas decimales dispares.
- Espacios sobrantes y diferencias de mayúsculas en ciudades y categorías, así como códigos numéricos categóricos que no deben promediarse.
- Registros duplicados, celdas vacías (incluyendo textos como "sin respuesta" que jamás deben convertirse en cero), errores de fórmula por dato no disponible o tipo incompatible y un valor atípico extremo que exige revisión documental.
- Nombres personales y correos ficticios expuestos en la tabla de clientes que requieren anonimización previa antes de cualquier análisis.

Para guiar su revisión inicial antes de abrir el archivo completo de 200 transacciones disponible en Moodle, observe la siguiente **muestra ilustrativa de estructura e incidencias típicas** (diez filas representativas):

| ID_Transaccion | Fecha_Venta | Codigo_Cliente | Cliente_Referencia | Ciudad | Categoria | Monto_USD | Unidades | Edad_Cliente |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR-001 | 2026-01-05 | CL-01 | Datos personales simulados 1 | Quito | Hogar | 45.50 | 2 | 29 |
| TR-002 | 06/01/2026 | CL-02 | Datos personales simulados 2 | quito  | Tecnología | $120,00 | 1 | sin respuesta |
| TR-003 | 2026/01/07 | CL-03 | Datos personales simulados 3 | GUAYAQUIL | accesorios | 32.00 | 3 | 34 |
| TR-003 | 2026/01/07 | CL-03 | Datos personales simulados 3 | GUAYAQUIL | accesorios | 32.00 | 3 | 34 |
| TR-004 | 08-01-2026 | CL-04 | Datos personales simulados 4 | Cuenca | Hogar |  | 1 | 41 |
| TR-005 | 2026-01-09 | CL-05 | Datos personales simulados 5 |  Ambato | Oficina | 1850.00 | 40 | 37 |

Durante las semanas 1 y 2, usted ejecutará la normalización de las 200 transacciones y la limpieza integral de la base de clientes dejando total trazabilidad de cada decisión.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Resguardo intangible y diccionario de variables (semana 1):** Copie los datos descargados en 01_Base_Original sin modificar ninguna celda y trabaje en 02_Transacciones_Depuradas. Elabore al inicio de su bitácora un diccionario breve de columnas indicando tipo de variable (nominal, ordinal o numérica), unidad de medida y valores válidos permitidos.
2. **Normalización de fechas, monedas y texto (Parte 1):** Utilice funciones de texto y conversión (como ESPACIOS, NOMPROPIO, FECHA o herramienta de texto en columnas y Power Query) para estandarizar todas las fechas al formato único año-mes-día, convertir textos de ciudad y categoría a escritura uniforme y dejar toda la columna de montos en formato numérico decimal puro sin símbolos mezclados.
3. **Anonimización y limpieza integral de la base de clientes (Parte 2, semana 2):** En la pestaña 03_Clientes_Anonimizados, elimine o sustituya identificadores personales (nombres completos, teléfonos, correos) conservando únicamente el código anónimo de cliente (por ejemplo, CL-001) y variables sociodemográficas válidas para análisis.
4. **Control de duplicados, fórmulas lógicas y errores:** Aplique la función CONTAR.SI y filtros avanzados para detectar códigos de transacción duplicados (verificando si es una repetición exacta como TR-003 en el ejemplo ilustrativo o un error de numeración entre dos compras reales). Emplee fórmulas condicionales (SI) y de cruce (BUSCARV o BUSCARX envueltas en control de errores como SI.ERROR) para cruzar clientes y detectar inconsistencias sin dejar errores de fórmula visibles en las celdas.
5. **Tratamiento riguroso de celdas vacías y valores atípicos:** Mantenga explícitamente las celdas sin dato (como "sin respuesta" en edad o montos vacíos) como valores ausentes documentados, jamás reemplazados por cero. Identifique los valores extremos (por ejemplo, una compra corporativa muy superior al promedio) contrastando monto frente a unidades antes de decidir si se conserva como segmento mayorista o se marca como error de digitación.
6. **Consolidación de bitácora y verificación final:** Documente en 04_Bitacora_Limpieza el conteo inicial de filas frente al conteo final válido tras eliminar duplicados exactos, justificando cada variación. Suba el archivo consolidado en Moodle al cierre de la semana 2.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 1](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Una tabla comercial original. Entrada → Clasificación → Depuración → Bitácora. Una copia limpia con historial de cambios](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 01/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Una tabla comercial original | Entrada → Clasificación → Depuración → Bitácora | Una copia limpia con historial de cambios |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Preparación, limpieza y organización de datos». Muestra a la izquierda la información de partida (una tabla comercial original), en el centro los pasos «Entrada → Clasificación → Depuración → Bitácora» y a la derecha el resultado (una copia limpia con historial de cambios). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Cómo explicarías a otra persona por qué un valor alto puede conservarse en la base?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

La hoja registra fechas como texto, dos filas con una misma clave y un valor alto que sí corresponde a una compra corporativa.

Prueba la normalización en registros conocidos, compara el duplicado con el respaldo y documenta por qué el valor alto se conserva. Guarda una copia original.

La bitácora debe distinguir formato, identidad y tratamiento analítico. Esa separación permite revisar una decisión sin revertir las demás ni cambiar el significado de los datos.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 1 (100 % asincrónico):** En la semana 1, lectura comprensiva del capítulo 1 de Lafuente Blasco (2025) (apoyada con criterios de validación del capítulo 2 y lineamientos éticos de Núñez Portilla y Guerrero Zambrano, 2025, páginas 3625 a 3634 según recursos del aula) para resolver un **cuestionario sobre tipos de variables y escalas**; en la semana 2, diseño de una **bitácora modelo de limpieza** documentando criterios de depuración, anonimización y manejo de errores, integrando ambos productos en Moodle al cierre de la semana 2.
2. **Trabajo Práctico-Experimental de la Unidad 1 (100 % asincrónico):** Taller de normalización de formatos sobre una base simulada de 200 transacciones comerciales y práctica de laboratorio de depuración integral de una base de clientes aplicando fórmulas lógicas (SI, BUSCARV o BUSCARX, CONTAR.SI), filtros avanzados, control de duplicados y anonimización. Los pasos completos constan en la Práctica 1 de la Guía de Prácticas y se entregan como archivo único al cierre de la semana 2.

**Evidencia del práctico según la guía de prácticas.** Un único archivo editable en hoja de cálculo en Moodle (Apellido_Nombre_Unidad1_Practica1.xlsx, acompañado de una breve síntesis en formato portátil de documento PDF si lo solicita la docente en el aula) que contenga:

- Pestaña 01_Base_Original intacta y pestaña 02_Transacciones_Depuradas con las 200 transacciones completamente normalizadas y libres de errores de fórmula.
- Pestaña 03_Clientes_Anonimizados debidamente vinculada con fórmulas lógicas y sin datos personales identificables expuestos.
- Pestaña 04_Bitacora_Limpieza con el diccionario de variables, registro de duplicados, manejo de celdas vacías, análisis del valor atípico y comparación de filas antes y después.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 1: Normalización y limpieza de base de 200 transacciones comerciales](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Una corrección justificada es reproducible y conserva suficiente información para explicar qué se trató.

#### Mensaje de reflexión

¿Cómo explicarías a otra persona por qué un valor alto puede conservarse en la base?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Lafuente Blasco, M. (2025). *Estadística descriptiva en investigación social con Excel* (1.ª ed., caps. 1-5, pp. 1-56). Servicio de Publicaciones, Universidad de Zaragoza. Lectura prevista: Caps. 1-2
- Núñez Portilla, J. E., & Guerrero Zambrano, M. F. (2025). Inteligencia artificial en la investigación científica: Una revisión crítica de las herramientas de análisis. *LATAM Revista Latinoamericana, 6*(4), 3623-3637. Lectura prevista: pp. 3625-3634

<a id="unidad-2"></a>

## Unidad 2: Análisis descriptivo de información

![Análisis de datos en Investigación · Unidad 2. Frecuencias. Porcentajes. Media, mediana y moda. Dispersión. Resultado: Un análisis de nivel habitual y dispersión](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 02/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Muestra a una estudiante que transforma ventas de ejemplo en una tabla de frecuencias y un resumen por categoría. Presenta el conjunto válido con pictogramas repetidos para ver la base del porcentaje. En un gráfico de puntos, distingue media, mediana y moda con guías visuales y muestra cómo un importe atípico cambia la media y amplía la dispersión. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Una vez depurada la base comercial, la **estadística descriptiva** permite resumir cientos de transacciones en cifras claras para la gerencia. El primer paso son las **tablas de frecuencia** y **tablas dinámicas**: la *frecuencia absoluta* cuenta cuántas veces ocurre una categoría o venta, mientras la *frecuencia relativa* divide ese conteo para el total de casos válidos (expresándose como porcentaje al multiplicar por 100). Al informar porcentajes, indique siempre cuántos registros se analizaron (*denominador válido*) y cuántos se excluyeron por dato ausente, diferenciando además pequeñas variaciones por redondeo (como sumar 99,9 % frente a 100,0 %) de errores reales de clasificación.

El caso de la unidad guía este recorrido: **Base válida → Cálculo → Resumen → Lectura**.

### Resultados de aprendizaje

El estudiante calcula medias, medianas, modas, desviaciones y porcentajes de ventas, interpretando su significado comercial en un informe breve.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Distribución de frecuencias y tablas de resumen | Frecuencias absolutas y relativas<br>tablas dinámicas para agregación de ventas por categoría o asesor. |
| 2. Medidas de tendencia central y dispersión aplicadas a ventas | Media aritmética, mediana y moda del ticket de venta<br>desviación estándar y rango de variabilidad. |

### Caso inicial

Con la base de *AndesMarket Comercio Digital* ya depurada y anonimizada en la Unidad 1, la coordinación comercial necesita conocer con precisión cuánto vende cada línea de producto y cada asesor mensualmente, cuál es el ticket típico real sin dejarse engañar por compras corporativas aisladas y qué tan variables son las órdenes de su comercio electrónico. Usted construirá las tablas dinámicas de resumen y calculará las medidas descriptivas y de dispersión necesarias para responder con cifras verificadas.

### Tema 1: Distribución de frecuencias y tablas de resumen

#### 1.1. Frecuencias absolutas y relativas

**Desarrollo técnico y aplicación.** La tabulación relaciona frecuencias con una base explícita. Si nueve de quince respuestas válidas mencionan una dificultad, la proporción es 60 %, aunque existan veinte registros totales. Indique ausencias y denominador. Una media necesita variable cuantitativa y unidad. Revise si varios registros de la misma persona introducen una ponderación no prevista al describir el conjunto.

La frecuencia absoluta cuenta casos y la relativa los divide por la base válida. Con seis respuestas de diez para un canal, la frecuencia relativa es 60 %. Reporta los ausentes y el criterio de redondeo.

**Fundamento y alcance.** El conteo describe cuántos casos pertenecen a cada categoría. El porcentaje relaciona ese conteo con una base identificada, por lo que debe acompañarse del denominador.

**Caso aplicado.** De diez respuestas válidas, seis corresponden al canal web.

**Resolución.** Reporta seis casos y 60 % y documenta si existían respuestas faltantes.

**Error frecuente y cómo detectarlo.** Dividir por todos los formularios cambia el significado si algunos no respondieron.

**Comprueba tu comprensión.** ¿Qué ocurre con un formulario sin respuesta?

**Respuesta comentada.** Identifícalo como faltante y usa la base válida según el criterio.

![Base. Hay diez respuestas válidas en el periodo. Frecuencia. Seis corresponden al canal web. Porcentaje. 6 ÷ 10 = 60 % del total válido. El recuento describe cantidad. El porcentaje añade contexto.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 02/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Frecuencias absolutas y relativas». Para el primer panel usa esta situación. De diez respuestas válidas, seis corresponden al canal web. En el segundo, representa esta acción. Reporta seis casos y 60 % y documenta si existían respuestas faltantes. En el último, incorpora esta comprobación. Identifícalo como faltante y usa la base válida según el criterio. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. tablas dinámicas para agregación de ventas por categoría o asesor.

**Desarrollo técnico y aplicación.** Una tabla dinámica necesita una unidad de registro coherente. Sumar importe de cabecera después de combinarlo con varias líneas puede duplicar ventas. Compruebe función, campos y filtros y concilie el total. Agrupar por asesor describe asignación registrada; no demuestra desempeño comparable si las carteras, oportunidades o periodos son diferentes.

Una tabla dinámica resume un conjunto por categorías o responsables. Comprueba que el campo de filas sea la categoría correcta y que el campo de valores use suma o conteo según el indicador.

**Fundamento y alcance.** Una tabla dinámica agrega registros por dimensiones. Elige qué representa cada fila y columna y confirma si el cálculo resume importes, casos o proporciones.

**Caso aplicado.** Dos asesores registran pedidos en categorías distintas.

**Resolución.** Arma una tabla dinámica con filas por asesor y columnas por categoría y verifica sumas.

**Error frecuente y cómo detectarlo.** Confundir recuento de pedidos con total monetario cambia la pregunta que responde la tabla.

**Comprueba tu comprensión.** ¿Cómo compruebas una tabla dinámica?

**Respuesta comentada.** Reproduce una celda desde las filas que la componen.

### Tema 2: Medidas de tendencia central y dispersión aplicadas a ventas

#### 2.1. Media aritmética, mediana y moda del ticket de venta

**Desarrollo técnico y aplicación.** La media utiliza magnitudes y la mediana posiciones; la moda identifica frecuencia. La dispersión describe cuánto varían observaciones respecto del resumen. Aclare si la varianza se calcula como descripción poblacional o estimación muestral. Un resultado central sin distribución puede ocultar extremos y grupos distintos. Compruebe cálculos con un conjunto pequeño y conserve la unidad al interpretar.

La media suma importes y divide por el número de observaciones. La mediana ocupa la posición central y la moda es el valor más frecuente. Para 10, 10, 20 y 60, la media es 25, la mediana 15 y la moda 10.

**Fundamento y alcance.** Las medidas del centro responden a preguntas distintas sobre una distribución. Compara una estimación del promedio, el valor central por posición y los valores repetidos.

**Caso aplicado.** Los tickets son 10, 10, 20 y 60 dólares.

**Resolución.** Calcula media 25, mediana 15 y moda 10 y explica el efecto del ticket alto.

**Error frecuente y cómo detectarlo.** Una sola medida central oculta qué valores son habituales en una distribución asimétrica.

**Comprueba tu comprensión.** ¿Qué medida del ejemplo reacciona más al ticket alto?

**Respuesta comentada.** La media, porque incorpora su magnitud en la suma.

#### 2.2. desviación estándar y rango de variabilidad.

**Desarrollo técnico y aplicación.** El rango utiliza extremos y la desviación estándar resume dispersión respecto de la media. Una misma media puede acompañar variaciones muy distintas. Identifique unidad y fórmula poblacional o muestral. Un valor alto requiere interpretar distribución y contexto; no significa automáticamente error. Examine registros extremos antes de convertir una medida de variabilidad en juicio sobre calidad.

El rango es máximo menos mínimo y la desviación estándar expresa dispersión en la unidad original. Para tickets de USD 10 a USD 60, el rango es USD 50. Indica si la desviación se calcula para toda la base o una muestra.

**Fundamento y alcance.** La dispersión indica qué tan separados están los datos. El rango usa solo extremos; la desviación estándar incorpora distancias al promedio y conserva la unidad original.

**Caso aplicado.** Cuatro tickets presentan un mínimo de USD 10 y un máximo de USD 60.

**Resolución.** Calcula el rango de USD 50 y una desviación poblacional cercana a USD 20,62.

**Error frecuente y cómo detectarlo.** La desviación muestral usa otro divisor y debe identificarse al reportar.

**Comprueba tu comprensión.** ¿Cuándo divides por cuatro en la varianza?

**Respuesta comentada.** Cuando los cuatro tickets son toda la población descrita.

![Datos. Los tickets son USD 10, 10, 20 y 60. Rango. USD 60 menos USD 10 da USD 50. Desviación. La desviación poblacional es aproximadamente USD 20,62. El rango usa los extremos. La desviación incorpora todos los valores.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 02/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «desviación estándar y rango de variabilidad». Para el primer panel usa esta situación. Cuatro tickets presentan un mínimo de USD 10 y un máximo de USD 60. En el segundo, representa esta acción. Calcula el rango de USD 50 y una desviación poblacional cercana a USD 20,62. En el último, incorpora esta comprobación. Cuando los cuatro tickets son toda la población descrita. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

En segundo lugar, al medir el valor típico de compra (*ticket de venta*), no basta con calcular un único promedio. La **media aritmética** suma todos los valores y divide para el total, por lo que resulta muy sensible a compras inusualmente altas; la **mediana** representa el valor central al ordenar todos los pedidos de menor a mayor, mostrando mejor lo que gasta el cliente típico cuando hay pedidos extremos; y la **moda** señala el precio o cantidad más repetido. Para comprender cuán estables o dispersas son las ventas, combine estas medidas con el **rango** (diferencia entre el pedido máximo y el mínimo) y la **desviación estándar** (que indica cuánto se alejan en promedio las ventas respecto a la media).

Finalmente, mantenga la **transparencia y eficiencia digital**: nunca oculte valores atípicos para maquillar el ticket promedio, y optimice el peso de sus hojas de cálculo eliminando filas vacías con formato innecesario, evitando fórmulas repetidas sobre columnas enteras y documentando con exactitud cada tabla de resumen.

### Ejemplo aplicado y resuelto

**Situación simulada.** En los tickets 10, 10, 20 y 60, la media es USD 25, la mediana USD 15 y la moda USD 10. El rango es USD 50 y la desviación poblacional es aproximadamente USD 20,62. Los dos pedidos de USD 10 representan 50 % de los cuatro registros. La distancia entre media y mediana ayuda a reconocer el efecto del ticket más alto.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Centro | Media, mediana y moda | USD 25, USD 15 y USD 10 |
| Dispersión | Rango y desviación poblacional | USD 50 y USD 20,62 |
| Frecuencia | Dos tickets de USD 10 sobre cuatro | 50 % |

**Ejemplo complementario de la guía didáctica.**

Imagine cuatro tickets válidos de compra en una tarde: **12 dólares, 15 dólares, 15 dólares y 78 dólares** (una compra corporativa excepcional de varios artículos).
- *Media aritmética:* (12 + 15 + 15 + 78) dividido para 4 = **30,00 dólares**.
- *Mediana:* Al ordenar los cuatro valores, los dos centrales son 15 y 15, por lo que la mediana es **15,00 dólares** (y la moda también es **15,00 dólares**).
- *Lectura comercial rigurosa:* Si el equipo comercial solo reportara *"el cliente promedio gasta 30 dólares"*, fijaría metas o promociones equivocadas. Informar conjuntamente media (30,00 dólares) y mediana (15,00 dólares), explicando la presencia del pedido mayorista de 78,00 dólares, brinda una lectura transparente y útil para decidir.

**Advertencia y error frecuente.** Indica el cálculo de dispersión y el conjunto de observaciones. El divisor cambia entre la desviación estándar poblacional y la muestral.

### Profundización técnica de la unidad

#### Resúmenes descriptivos y control del denominador

La frecuencia absoluta cuenta observaciones; la relativa divide por la base seleccionada. Una tabla dinámica agrega según campos y funciones, por lo que se debe comprobar si suma, cuenta o promedia. Los filtros cambian la población incluida y deben quedar visibles al interpretar resultados.

**Ejemplo resuelto.** Tickets de USD 10, 10, 20 y 60: total 100, media 25 y mediana 15. La moda es 10. El rango es 50. Cada medida informa algo diferente; usar la media como «compra típica» requiere considerar la asimetría que introduce el ticket de 60.

Si se compara por asesor, revise número de pedidos y tipo de cartera. Una suma mayor no demuestra mejor desempeño cuando las oportunidades son distintas. La desviación estándar aporta dispersión, pero necesita aclarar si describe el conjunto o se usa una fórmula muestral. **Reflexión:** ¿qué medida ayudaría a explicar por qué el promedio no coincide con la mayoría de compras observadas?

#### Datos y condiciones para estudiar el caso en detalle

Con la base de *AndesMarket Comercio Digital* (caso ficticio diseñado exclusivamente con fines formativos) ya depurada y anonimizada en la Práctica 1, la coordinación comercial necesita preparar el cierre descriptivo del semestre durante las semanas 3 y 4. Un reporte anterior confundió al directorio al informar únicamente un promedio inflado por compras corporativas atípicas, sin desagregar cuánto vendió cada asesor ni qué producto concentró la demanda mensual. Asimismo, los libros de cálculo anteriores pesaban demasiado por contener miles de filas vacías formateadas y fórmulas repetidas. Su tarea consiste en elaborar tablas dinámicas limpias, calcular tendencia central y dispersión del ticket de compra en el comercio electrónico (e-commerce) e interpretar con transparencia su significado comercial.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Tablas de frecuencia y resumen mensual mediante tablas dinámicas (Parte 1, semana 3):** A partir de la pestaña depurada, genere al menos dos **tablas dinámicas** en una hoja nueva llamada 01_Resumen_Mensual: una agregando ventas mensuales en dólares estadounidenses (USD) y porcentajes sobre el total por **categoría de producto o servicio**, y otra comparando las ventas mensuales y número de órdenes por **asesor comercial**. Añada un campo calculado o columna de ticket promedio por grupo y verifique que las frecuencias relativas sumen 100 % (aclarando cualquier variación mínima por redondeo).
2. **Cálculo analítico de tendencia central y dispersión (Parte 2, semana 4):** En una segunda pestaña (02_Estadistica_Ticket), utilice las funciones analíticas de la hoja de cálculo (PROMEDIO, MEDIANA, MODA.UNO o MODA, MIN, MAX, DESVEST.M y Herramientas para Análisis de Datos si están activadas) para calcular sobre los tickets válidos: media aritmética, mediana, moda, rango, varianza y desviación estándar, acompañadas de un histograma o diagrama de caja y bigotes (boxplot) exploratorio.
3. **Comprobación manual y contraste ante valores atípicos:** Tome una muestra pequeña de cinco o diez pedidos (o compare dos categorías: una estable y otra con un pedido mayorista muy alto) y demuestre con cálculo paso a paso por qué la media supera a la mediana cuando existe asimetría positiva. Presente ambos valores sin ocultar ni borrar el pedido atípico real.
4. **Interpretación comercial en informe breve:** Redacte un informe ejecutivo breve (en una pestaña dedicada o documento adjunto dentro de la misma entrega) respondiendo tres preguntas gerenciales: qué producto y qué asesor lideran las ventas, cuál es el gasto típico real del comprador frente a la dispersión de pedidos y qué riesgo tendría fijar metas de ventas basadas solo en la media aritmética.
5. **Optimización técnica y eficiencia energética del libro:** Revise su archivo eliminando columnas y filas vacías con formato residual, evitando fórmulas que recorran millones de filas innecesarias y comprobando que el libro guarde un peso ligero y abra con rapidez sin errores de cálculo.
6. **Integración y entrega única en Moodle:** Verifique la correspondencia exacta de todas las cifras entre las tablas dinámicas y su texto interpretativo, incorpore sus referencias en normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) y suba el expediente en Moodle al cierre de la semana 4.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 2](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Tickets y categorías verificables. Base válida → Cálculo → Resumen → Lectura. Un análisis de nivel habitual y dispersión](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 02/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Tickets y categorías verificables | Base válida → Cálculo → Resumen → Lectura | Un análisis de nivel habitual y dispersión |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Análisis descriptivo de información». Muestra a la izquierda la información de partida (tickets y categorías verificables), en el centro los pasos «Base válida → Cálculo → Resumen → Lectura» y a la derecha el resultado (un análisis de nivel habitual y dispersión). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Qué medida presentarías primero si quieres describir un ticket representativo y por qué?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

El análisis de cuatro tickets da una media de USD 25 y una mediana de USD 15. El equipo espera saber cuánto compra habitualmente una persona.

Explica cómo el ticket de USD 60 afecta media y dispersión. Incluye la mediana para describir el centro por posición y añade frecuencia de los importes repetidos.

Una cifra describe una parte de la distribución. Señala tamaño de la base y criterio de cálculo para que el reporte pueda interpretarse o verificarse.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 2 (100 % asincrónico):** En la semana 3, lectura comprensiva de los capítulos 2 y 3 de Lafuente Blasco (2025) (junto con los criterios de análisis descriptivo de Muñetón Santa, 2025, páginas 16 a 24) y resolución de **ejercicios prácticos de tablas de frecuencia**; en la semana 4, redacción de un **resumen ejecutivo breve** que explique el significado comercial de las medidas de tendencia central y dispersión calculadas, entregando un único producto consolidado en Moodle al cierre de la semana 4.
2. **Trabajo Práctico-Experimental de la Unidad 2 (100 % asincrónico):** Práctica de creación de tablas de resumen de ventas mensuales agrupadas por producto y asesor mediante tablas dinámicas, junto con un taller de cálculo e interpretación de métricas de dispersión del ticket promedio en un comercio electrónico (e-commerce), cuidando la eficiencia del archivo. El detalle completo figura en la Práctica 2 de la Guía de Prácticas y se entrega al cierre de la semana 4.

**Evidencia del práctico según la guía de prácticas.** Un único expediente en Moodle (Apellido_Nombre_Unidad2_Practica2.xlsx con el informe interpretativo integrado en pestaña dedicada o en formato portátil de documento PDF adjunto en el mismo envío) que contenga:

- Tablas dinámicas funcionales de resumen mensual por producto/servicio y por asesor comercial con frecuencias absolutas, relativas y campo calculado.
- Pestaña de análisis descriptivo del ticket promedio con media, mediana, moda, rango, desviación estándar y gráfico de distribución (histograma o diagrama de caja y bigotes).
- Informe breve transparente con la interpretación comercial de las métricas, comparación ante valores atípicos y constancia de optimización del archivo.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 2: Tablas de resumen mensual y análisis descriptivo de ventas](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Interpretar una medida requiere conocer el tamaño de la base y cómo afectan los valores extremos.

#### Mensaje de reflexión

¿Qué medida presentarías primero si quieres describir un ticket representativo y por qué?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Muñetón Santa, G. (2025). Navegando la investigación social en la era digital: Una guía práctica para el análisis cualitativo y cuantitativo con apoyo de inteligencia artificial. *Documentos de Trabajo INER, 1*(1), 14-41. Lectura prevista: pp. 16-24

<a id="unidad-3"></a>

## Unidad 3: Visualización e interpretación para la toma de decisiones

![Análisis de datos en Investigación · Unidad 3. Tablero de ventas. Periodo y canal. Comparación de productos. Evolución temporal. Decisión comercial. Resultado: Un tablero de comparación legible](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 03/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Crea un panel de ventas de dos zonas, con líneas para la evolución temporal y barras para comparar productos o canales. Destaca un selector de periodo y otro de canal para mostrar cómo responden ambos gráficos al filtro. Usa escalas legibles y comienza el gráfico de barras en cero; una inspección visual conecta una variación con una pregunta comercial. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Un buen gráfico permite percibir patrones comerciales en segundos sin deformar la realidad. La elección depende directamente de la pregunta analítica: utilice **gráficos de columnas o barras** cuando compare magnitudes entre categorías (por ejemplo, ventas por ciudad o por asesor); **gráficos de líneas** para visualizar la evolución temporal semana a semana o mes a mes; y **gráficos de dispersión** para explorar la relación o posible asociación entre dos variables cuantitativas (como el porcentaje de descuento aplicado frente a las unidades vendidas, añadiendo una línea de tendencia solo cuando exista relación lógica y aclarando siempre que correlación no implica causalidad).

El caso de la unidad guía este recorrido: **Pregunta → Gráfico → Filtro → Validación**.

### Resultados de aprendizaje

El estudiante diseña gráficos interactivos adecuados para representar la evolución temporal y distribución de ventas por producto o canal.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Selección y diseño de gráficos comerciales efectivos | Gráficos de columnas, líneas, barras y dispersión<br>principios de diseño visual y legibilidad de datos. |
| 2. Construcción de tableros de control visual (Dashboards) | Integración de gráficos con segmentadores interactivos<br>visualización de KPIs de ventas en un solo panel. |

### Caso inicial

Para la reunión bimestral de resultados de *AndesMarket Comercio Digital*, un analista junior elaboró gráficos tridimensionales con ejes recortados que hacían parecer desastrosas las ventas de una categoría y exageraban los resultados de otra. La gerencia solicita corregir esas visualizaciones engañosas creando tres gráficos limpios con contexto completo e integrándolos en un **tablero de control visual interactivo** con cuatro métricas clave y filtros por canal y periodo.

### Tema 1: Selección y diseño de gráficos comerciales efectivos

#### 1.1. Gráficos de columnas, líneas, barras y dispersión

**Desarrollo técnico y aplicación.** La visualización relaciona tipo de variable y pregunta. Las barras comparan categorías y una dispersión relaciona pares numéricos. Una línea requiere orden significativo. No elija un gráfico porque parezca avanzado: compruebe que permite reconocer la diferencia de interés y conserva unidad, base y periodo. Un título claro comunica qué se representa sin atribuir causas no demostradas.

Usa columnas o barras para comparar categorías, líneas para series de tiempo y dispersión para pares numéricos. Escoge el gráfico que responda a la pregunta y conserva en la vista las unidades.

**Fundamento y alcance.** Un gráfico de dispersión relaciona pares numéricos; las líneas muestran evolución ordenada; las barras son comparaciones discretas. Define la lectura que esperas antes de elegir formato.

**Caso aplicado.** La pregunta compara los pedidos de tres canales a lo largo de meses.

**Resolución.** Usa líneas para evolución y barras por canal si deseas una comparación acumulada.

**Error frecuente y cómo detectarlo.** Ordenar meses por volumen rompe la secuencia temporal.

**Comprueba tu comprensión.** ¿Qué gráfico elegirías para devoluciones frente a pedidos?

**Respuesta comentada.** Dispersión si cada observación contiene ambas magnitudes numéricas.

![Barras o columnas. Compara categorías como productos, sedes o canales. Líneas. Muestra cómo cambia un indicador con el tiempo. Dispersión. Explora la relación entre dos medidas numéricas. Escoge el gráfico por la pregunta antes de diseñarlo.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 03/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Gráficos de columnas, líneas, barras y dispersión». Para el primer panel usa esta situación. La pregunta compara los pedidos de tres canales a lo largo de meses. En el segundo, representa esta acción. Usa líneas para evolución y barras por canal si deseas una comparación acumulada. En el último, incorpora esta comprobación. Dispersión si cada observación contiene ambas magnitudes numéricas. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. principios de diseño visual y legibilidad de datos.

**Desarrollo técnico y aplicación.** La distribución y el objetivo orientan el gráfico. Un histograma agrupa valores continuos y depende de intervalos; una barra representa categorías. Una elección inadecuada puede sugerir continuidad o concentración inexistente. Muestre unidad, tamaño del conjunto y condiciones de selección. La visualización facilita reconocer patrones, pero no demuestra automáticamente que una diferencia sea causal o generalizable.

La legibilidad requiere etiquetas claras, contraste y escalas defendibles. En barras, parte de cero para mantener proporciones. Una línea de tendencia necesita una escala explícita y un periodo comparable.

**Fundamento y alcance.** La escala determina cuánto espacio ocupa una diferencia. Mantén un criterio adecuado al tipo de gráfico y conserva etiquetas, periodos y unidades visibles.

**Caso aplicado.** Dos barras empiezan en 90 y muestran valores de 96 y 100.

**Resolución.** Restablece una base cero y conserva etiquetas y unidad para interpretar magnitudes.

**Error frecuente y cómo detectarlo.** Una diferencia pequeña puede parecer varias veces mayor con una escala truncada.

**Comprueba tu comprensión.** ¿Por qué iniciar las barras en cero?

**Respuesta comentada.** Su longitud representa magnitud y una base truncada distorsiona la comparación.

### Tema 2: Construcción de tableros de control visual (Dashboards)

#### 2.1. Integración de gráficos con segmentadores interactivos

**Desarrollo técnico y aplicación.** El tablero interactivo mantiene consistencia entre filtros, tarjetas y gráficos. Muestre contexto activo y permita interpretar qué cambió al seleccionar una categoría. Una tarjeta anual junto a un gráfico mensual puede inducir comparaciones inválidas. El relato de datos conecta pregunta, evidencia y decisión: no sustituye el análisis por una secuencia estética de indicadores sin relación con el objetivo.

Los segmentadores interactivos permiten examinar partes de la base. Vincula la misma selección a las vistas pertinentes y verifica el total filtrado con un conteo manual.

**Fundamento y alcance.** Los segmentadores permiten seleccionar subconjuntos sin rehacer manualmente el tablero. Especifica si un indicador ofrece una referencia global o debe responder junto con las demás vistas.

**Caso aplicado.** Un filtro por canal modifica las barras y deja la serie sin filtrar.

**Resolución.** Prueba el filtro con un subconjunto cuyo total conozcas y señala ambas bases si fueran distintas.

**Error frecuente y cómo detectarlo.** La interacción aparente en una vista no confirma que todo el panel se haya filtrado.

**Comprueba tu comprensión.** ¿Qué identifica un total que se mantuvo global?

**Respuesta comentada.** Una etiqueta de alcance y un control al cambiar el filtro.

#### 2.2. visualización de KPIs de ventas en un solo panel.

**Desarrollo técnico y aplicación.** Un KPI de panel mantiene nombre, fórmula, unidad, periodo y base. Si cambia un filtro, todos los elementos relacionados deben responder de forma coherente. Una tarjeta sin contexto puede compararse erróneamente con otro periodo. Verifique el cálculo contra registros y diferencie cantidades, tasas y puntos porcentuales para que el lector no interprete magnitudes incompatibles.

Un panel útil reúne indicadores que sirven a una decisión. Junto a ventas, muestra periodo, recuento y una comparación. Separa patrones visuales de conclusiones causales.

**Fundamento y alcance.** Los KPI de ventas sintetizan magnitud, variación o cumplimiento de objetivos. Un panel funcional reúne indicadores accionables y permite comprender sus condiciones de cálculo.

**Caso aplicado.** El panel muestra ventas y devoluciones pero omite el periodo.

**Resolución.** Agrupa cifras de alcance compartido y documenta fechas y criterio de venta válida.

**Error frecuente y cómo detectarlo.** Comparar métricas con filtros ocultos produce conclusiones ambiguas.

**Comprueba tu comprensión.** ¿Qué falta para comparar dos KPI del mismo tablero?

**Respuesta comentada.** Periodo, unidad, regla de cálculo y filtros visibles.

![Indicadores. Elige pocas medidas útiles para la decisión. Alcance. Indica periodo, unidad y filtros activos. Verificación. Reproduce un total desde la tabla de origen. Un panel claro permite saber exactamente qué datos está mostrando.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 03/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «visualización de KPIs de ventas en un solo panel». Para el primer panel usa esta situación. El panel muestra ventas y devoluciones pero omite el periodo. En el segundo, representa esta acción. Agrupa cifras de alcance compartido y documenta fechas y criterio de venta válida. En el último, incorpora esta comprobación. Periodo, unidad, regla de cálculo y filtros visibles. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

Por transparencia y rigor profesional, evite errores habituales que distorsionan decisiones: nunca utilice **gráficos tridimensionales (3D)** ni barras inclinadas que alteran visualmente la proporción de los valores; inicie siempre el eje vertical en **cero** en gráficos de barras o columnas para no exagerar diferencias pequeñas; y mantenga títulos claros que indiquen qué variable se mide, en qué unidad, en qué periodo y sobre cuántos registros válidos.

Al integrar varias vistas en un **tablero de control visual (dashboard)**, incorpore **segmentadores de datos interactivos** (filtros por canal, mes o categoría) y defina con precisión cada **indicador clave de desempeño (KPI)** mostrando valores observados separados de metas proyectadas. Cuando explore además si existe asociación entre variables con distintas escalas (por ejemplo, comparar montos en miles de dólares frente a frecuencia en pocos pedidos), explique claramente la unidad de cada eje antes de comparar o agrupar registros.

### Ejemplo aplicado y resuelto

**Situación simulada.** Construye una línea por mes y barras por canal para la misma base. Al filtrar «web», comprueba que en los dos gráficos solo aparezcan ventas de ese canal. Si el recuento manual del mes arroja 15 pedidos y el panel informa 19, corrige el filtro o la conexión de datos antes de interpretar.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Evolución | Pedidos por mes | Línea |
| Comparación | Pedidos por canal | Barras |
| Interacción | Selección de canal | Comprobar actualización de ambas vistas |

**Ejemplo complementario de la guía didáctica.**

Suponga que las ventas mensuales de dos canales fueron **10.200 dólares** en *Tienda web* y **10.600 dólares** en *WhatsApp Business* (apenas una diferencia del 3,9 %).
- *Gráfico engañoso:* Un gráfico de barras tridimensional cuyo eje vertical comienza en 10.000 dólares hace parecer que *WhatsApp Business* vende tres veces más que la *Tienda web*.
- *Visualización ética y precisa:* Un gráfico plano de barras horizontales o columnas con el eje vertical empezando en cero, etiquetas exactas en dólares y un subtítulo claro (*"Diferencia de 400 dólares equivalente al 3,9 % entre canales durante el trimestre"*), permitiendo al comité comercial tomar una decisión realista.

**Advertencia y error frecuente.** Etiquetas y escalas deben permanecer visibles al filtrar. Si una vista cambia de base, identifica el filtro antes de usar el panel en una decisión.

### Profundización técnica de la unidad

#### Gráficos y paneles que respetan la pregunta

Las barras comparan categorías; las líneas suelen mostrar evolución ordenada; la dispersión examina pares de variables. La elección depende de la relación que se quiere observar. Las escalas, unidades y filtros influyen en la lectura, por lo que deben mantenerse explícitos.

**Ejemplo resuelto.** Un gráfico muestra 90 y 100 pedidos con un eje que comienza en 89. La diferencia puede parecer enorme frente a una representación desde cero. En barras, la longitud codifica magnitud y exige especial cuidado con ese punto de partida. Una línea temporal también necesita distinguir periodos sin datos de periodos con valor cero.

Un segmentador interactivo debe actualizar los elementos relacionados del panel con una base coherente. Si una tarjeta muestra ventas de un mes y otra permanece en el total anual, la comparación induce a error. Un título útil indica medida y periodo, y una explicación conecta el gráfico con una decisión posible. **Reflexión:** ¿qué filtro o escala podría hacer que dos lectores interpreten de manera distinta el mismo conjunto?

#### Datos y condiciones para estudiar el caso en detalle

De cara al comité bimestral de *AndesMarket Comercio Digital* (caso ficticio diseñado exclusivamente con fines formativos), el equipo recibió un borrador de presentación lleno de fallas visuales: incluía un gráfico circular con doce categorías imposibles de leer, barras tridimensionales (3D) con perspectiva inclinada y un gráfico de columnas cuyo eje vertical iniciaba en 5.000 dólares para exagerar diferencias mínimas entre meses. Durante las semanas 5 y 6, usted deberá transformar las tablas resumen depuradas en **tres gráficos éticos y legibles** y un **tablero de control visual interactivo** con cuatro indicadores clave de desempeño (KPI) y filtros por canal o periodo, explorando además si existe asociación entre descuento o precio y volumen vendido.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Conversión de tablas en 3 gráficos claros y éticos (Parte 1, semana 5):** A partir de sus tablas dinámicas cruzadas y porcentajes sobre totales, construya en una pestaña dedicada tres gráficos limpios y planos (nunca en formato tridimensional):
   - **Gráfico 1 (evolución temporal):** Gráfico de líneas mostrando la evolución mensual de ventas válidas con etiquetas claras de periodo.
   - **Gráfico 2 (distribución comparativa):** Gráfico de barras o columnas ordenadas de mayor a menor para ventas o participación por producto o canal, con eje numérico iniciando estrictamente en **cero**.
   - **Gráfico 3 (asociación entre variables):** Gráfico de dispersión relacionando dos variables cuantitativas (por ejemplo, descuento aplicado o precio unitario frente a unidades compradas o monto de orden), calculando el coeficiente de correlación lineal (COEF.DE.CORREL) y añadiendo una línea de tendencia comentada.
2. **Incorporación de títulos ejecutivos e indicadores de contexto:** Asigne a cada gráfico un título que comunique el hallazgo o pregunta central, subtítulo con la unidad de medida, periodo analizado y base válida exacta (por ejemplo: *Ventas netas en dólares estadounidenses, enero a junio, n = ... transacciones válidas*) y elimine elementos visuales distractores (bordes gruesos o fondos recargados).
3. **Construcción del tablero de control visual interactivo (Parte 2, semana 6):** Cree una pestaña principal llamada Tablero_Control integrando en un solo panel ordenado sin desplazamiento excesivo: cuatro tarjetas numéricas dinámicas para sus **cuatro indicadores clave de desempeño (KPI)** (por ejemplo: ventas totales netas, número de órdenes válidas, ticket mediano o promedio y porcentaje de cumplimiento o participación del canal líder) junto con los gráficos dinámicos enlazados.
4. **Inserción de segmentadores interactivos y pruebas de respuesta:** Conecte al menos dos **segmentadores de datos** (por ejemplo, por *Mes* y por *Canal* o *Ciudad*) a todas las tablas dinámicas y gráficos del tablero, comprobando que al seleccionar un filtro las cuatro métricas y los gráficos se actualicen simultáneamente sin mostrar errores de división o celdas desbordadas.
5. **Verificación de escalas y lectura honesta de correlación:** Redacte debajo del tablero un análisis breve explicando qué indica realmente el coeficiente de correlación obtenido (recordando que una asociación entre dos variables no demuestra automáticamente causalidad) y comparando cómo la corrección de ejes desde cero evita decisiones erróneas.
6. **Revisión estética, referencias e integración única en Moodle:** Verifique la legibilidad en pantalla, incluya sus citas en normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) (Lafuente Blasco, 2025) y entregue el libro de cálculo consolidado en Moodle al cierre de la semana 6.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 3](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Series de tiempo y totales por categoría. Pregunta → Gráfico → Filtro → Validación. Un tablero de comparación legible](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 03/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Series de tiempo y totales por categoría | Pregunta → Gráfico → Filtro → Validación | Un tablero de comparación legible |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Visualización e interpretación para la toma de decisiones». Muestra a la izquierda la información de partida (series de tiempo y totales por categoría), en el centro los pasos «Pregunta → Gráfico → Filtro → Validación» y a la derecha el resultado (un tablero de comparación legible). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿En qué parte del panel dejarías constancia del filtro activo para evitar comparaciones equivocadas?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Tras seleccionar un canal, el gráfico temporal se actualiza y el indicador de ingresos sigue mostrando el total general.

Comprueba la conexión del filtro con cada vista y revisa sus cifras usando un conjunto controlado. Si conservas el indicador global, identifícalo claramente.

Combinar contexto general y datos filtrados puede ser útil cuando el alcance de cada vista está visible. Una comparación entre bases ocultas conduce a lecturas equivocadas.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 3 (100 % asincrónico):** En la semana 5, lectura comprensiva de los capítulos 4 y 5 de Lafuente Blasco (2025) sobre representación gráfica y cruce de variables junto con un **análisis crítico de visualizaciones comerciales** (corrigiendo casos con escalas distorsionadas); en la semana 6, **ajuste de formato, jerarquía visual y presentación estética** del tablero comercial, entregando un solo documento o archivo integrado al cierre de la semana 6 en Moodle.
2. **Trabajo Práctico-Experimental de la Unidad 3 (100 % asincrónico):** Taller de conversión de tablas estadísticas en 3 gráficos claros con títulos e indicadores de contexto, seguido de un proyecto práctico de elaboración de un tablero de control visual (dashboard) interactivo con 4 métricas clave, segmentadores y análisis básico de correlación o asociación. El detalle completo figura en la Práctica 3 de la Guía de Prácticas y se entrega al cierre de la semana 6.

**Evidencia del práctico según la guía de prácticas.** Un único expediente editable en Moodle (Apellido_Nombre_Unidad3_Practica3.xlsx, con capturas o síntesis en formato portátil de documento PDF si lo solicita la docente dentro del mismo envío) que incluya:

- Pestaña con los 3 gráficos claros y éticos (líneas, barras/columnas con eje desde cero y dispersión con coeficiente de correlación) y sus tablas dinámicas cruzadas vinculadas.
- Pestaña Tablero_Control con el panel interactivo funcional, 4 métricas clave visibles en tarjetas enlazadas por fórmulas y al menos 2 segmentadores operativos conectados.
- Breve comentario analítico interpretando las tendencias, la asociación observada (sin falacias causales) y las correcciones visuales aplicadas.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 3: Conversión de tablas estadísticas en tres gráficos de decisión](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

La visualización orienta decisiones cuando escalas, filtros y alcances permiten reconstruir el dato.

#### Mensaje de reflexión

¿En qué parte del panel dejarías constancia del filtro activo para evitar comparaciones equivocadas?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Lafuente Blasco, M. (2025). *Estadística descriptiva en investigación social con Excel* (1.ª ed., caps. 1-5, pp. 1-56). Servicio de Publicaciones, Universidad de Zaragoza. Lectura prevista: Caps. 4-5

<a id="unidad-4"></a>

## Unidad 4: IA, clasificación y segmentación de información

![Análisis de datos en Investigación · Unidad 4. Historial de compra. Segmentos RFM. Resumen asistido. Ajuste comercial validado. Resultado: Una recomendación vinculada con patrones observados](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 04/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Ilustra a una analista que agrupa tarjetas anónimas de clientes según recencia, frecuencia y valor monetario. Muestra dos agrupaciones visibles y un resumen sugerido por IA que se comprueba contra las fichas originales. Relaciona cada ajuste comercial propuesto con la evidencia del segmento y marca como provisional una explicación causal sin comprobar. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

En la etapa final del análisis comercial, los asistentes de **inteligencia artificial (IA)** ayudan a agilizar la interpretación de tablas resumen, proponer fórmulas condicionales complejas y redactar borradores de resúmenes ejecutivos. Sin embargo, la inteligencia artificial jamás reemplaza el juicio estadístico ni la verificación humana: cada cifra citada por un asistente debe contrastarse contra la hoja de cálculo, y los datos cargados en cualquier consulta deben permanecer estrictamente anonimizados.

El caso de la unidad guía este recorrido: **Comportamiento → Segmento → Revisión → Acción**.

### Resultados de aprendizaje

El estudiante analiza segmentos de clientes identificados en los datos y propone ajustes comerciales fundamentados en la evidencia analítica.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Asistencia de IA en el análisis de datos comerciales | Uso de asistentes inteligentes para resumir hallazgos, sugerir fórmulas y detectar anomalías en datos. |
| 2. Segmentación de clientes basada en datos e informe final | Concepto de agrupación de clientes según valor y frecuencia (RFM básico)<br>informe final con recomendaciones. |

### Caso inicial

Culminada la limpieza, cálculo estadístico y diseño del tablero visual en las unidades previas, el directorio de *AndesMarket Comercio Digital* solicita identificar los perfiles reales de su clientela para decidir dónde optimizar compras de inventario y campañas de retención sin malgastar presupuesto. Usted aplicará una segmentación práctica por recencia, frecuencia y valor monetario (RFM), contrastará resúmenes generados con asistencia de inteligencia artificial frente a las cifras exactas de su tablero y presentará el informe analítico final con recomendaciones sustentadas.

### Tema 1: Asistencia de IA en el análisis de datos comerciales

#### 1.1. Uso de asistentes inteligentes para resumir hallazgos, sugerir fórmulas y detectar anomalías en datos.

**Desarrollo técnico y aplicación.** Un prompt analítico especifica pregunta, columnas permitidas, periodo y formato de respuesta. Exija distinguir cálculo, observación e interpretación. Si el conjunto no contiene inventario, no puede justificar una recomendación de stock como resultado observado. Valide totales e identificadores y compruebe que el resumen no altere denominadores, omita ausencias o invente categorías para completar el relato.

Un asistente puede sugerir una fórmula o resumir un patrón. Prueba la fórmula sobre filas con resultado conocido y compara el resumen con tu tabla. Una asociación entre dos indicadores invita a investigar qué otros factores cambiaron.

**Fundamento y alcance.** Un asistente puede sugerir fórmulas, anomalías o narrativas. La revisión humana comprueba cálculos, contexto y confianza antes de incorporar la sugerencia al informe.

**Caso aplicado.** El asistente sugiere una fórmula que incluye filas vacías.

**Resolución.** Prueba la fórmula con dos resultados conocidos y ajusta la base válida.

**Error frecuente y cómo detectarlo.** Una explicación convincente puede ocultar una selección incorrecta de celdas.

**Comprueba tu comprensión.** ¿Cómo evalúas una fórmula de IA?

**Respuesta comentada.** Prueba casos conocidos y explica el tratamiento de celdas vacías.

![Sugerencia. El asistente propone una fórmula para ventas. Prueba. Compárala en filas con resultado conocido y celdas vacías. Validación. Corrige base, fórmula o texto antes de integrar. La verificación humana precede al informe.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 04/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Uso de asistentes inteligentes para resumir hallazgos, sugerir fórmulas y detectar anomalías en datos». Para el primer panel usa esta situación. El asistente sugiere una fórmula que incluye filas vacías. En el segundo, representa esta acción. Prueba la fórmula con dos resultados conocidos y ajusta la base válida. En el último, incorpora esta comprobación. Prueba casos conocidos y explica el tratamiento de celdas vacías. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Tema 2: Segmentación de clientes basada en datos e informe final

#### 2.1. Concepto de agrupación de clientes según valor y frecuencia (RFM básico)

**Desarrollo técnico y aplicación.** RFM depende de fecha de corte, definición de compra y valor incluido. La recencia disminuye al acercarse la compra al corte; la frecuencia cuenta transacciones y no líneas por defecto. Las puntuaciones se asignan según una regla explícita. Un grupo de alto valor no garantiza respuesta a una oferta ni autoriza cualquier contacto automático.

RFM agrupa según tiempo desde la última compra, número de compras y monto dentro de una ventana. Define las reglas antes de asignar clientes y conserva los valores que sustentan cada grupo.

**Fundamento y alcance.** El modelo RFM distingue contacto reciente, volumen de compras e importe de relación. Definir umbrales ayuda a reproducir la clasificación y a revisar casos cercanos al límite.

**Caso aplicado.** Dos clientes compran tres veces y gastan USD 100, uno ayer y otro hace seis meses.

**Resolución.** Usa una misma fecha de corte para distinguir la recencia.

**Error frecuente y cómo detectarlo.** La misma frecuencia histórica no demuestra el mismo interés actual.

**Comprueba tu comprensión.** ¿Qué variable separa a los dos clientes del ejemplo?

**Respuesta comentada.** Recencia calculada desde la misma fecha de corte.

#### 2.2. informe final con recomendaciones.

**Desarrollo técnico y aplicación.** La conclusión identifica hallazgo, base y alcance. «Ocho de diez participantes completaron la tarea» conserva la evidencia; «el sistema funciona para toda la población» requiere otro sustento. La verificabilidad depende de registros y procedimiento, no de una expresión segura. Revise que cada conclusión tenga un resultado previo que la respalde y que no incorpore datos nuevos sin análisis.

Una recomendación fundamentada vincula segmento, evidencia, ajuste y forma de verificarlo. Si un grupo fue activo y dejó de comprar, plantea seguimiento y registra qué respuesta respaldaría el ajuste.

**Fundamento y alcance.** El informe conecta datos, agrupaciones y recomendaciones mediante criterios que el lector puede reconstruir. Define qué se probará y cuáles resultados justificarían un cambio de acción.

**Caso aplicado.** Un grupo de clientes dejó de comprar durante el último trimestre.

**Resolución.** Revisa si el segmento es estable y presenta una acción de seguimiento con indicador de respuesta.

**Error frecuente y cómo detectarlo.** Una asociación entre demora y pérdida de clientes no prueba que la demora sea la causa.

**Comprueba tu comprensión.** ¿Qué valida una acción propuesta para un segmento?

**Respuesta comentada.** Una necesidad observada y un indicador que permita revisar su respuesta.

![Hallazgo. Un grupo no compra desde hace varios meses. Acción. Prueba un seguimiento útil, sujeto a su preferencia de contacto. Revisión. Mide respuesta sobre el grupo elegible y explica sus límites. Cada propuesta debe rastrearse hasta un hallazgo.](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 04/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «informe final con recomendaciones». Para el primer panel usa esta situación. Un grupo de clientes dejó de comprar durante el último trimestre. En el segundo, representa esta acción. Revisa si el segmento es estable y presenta una acción de seguimiento con indicador de respuesta. En el último, incorpora esta comprobación. Una necesidad observada y un indicador que permita revisar su respuesta. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

Para transformar datos de ventas en acciones comerciales rentables y sostenibles se utiliza la **segmentación de clientes**. Un método muy accesible y potente en comercio digital es el **modelo de recencia, frecuencia y valor monetario (RFM)**, que evalúa cuán reciente fue la última compra del cliente (*recencia*), cuántas veces compró en el periodo (*frecuencia*) y cuánto dinero aportó (*valor monetario*). De forma complementaria, en análisis más avanzados existen métodos matemáticos de **agrupamiento (clustering)** sin etiquetas previas —como **k-medias (k-means)** y el **agrupamiento jerárquico**—, donde resulta fundamental estandarizar las escalas de las variables (para que el monto en cientos de dólares no anule la influencia de la frecuencia medida en unidades pequeñas) y comparar siempre los métodos sobre los mismos datos y criterios.

Al redactar el **informe analítico final** y formular recomendaciones para optimizar inventario o evitar gastos comerciales innecesarios, recuerde la regla de oro de interpretación: **observar una mayor compra promedio en un segmento no prueba que pertenecer a ese grupo cause el gasto**. Presente cada hallazgo con sus datos reales, formule hipótesis alternativas responsables y proponga ajustes comerciales medibles bajo criterios de gestión eficiente y sostenible de recursos.

### Ejemplo aplicado y resuelto

**Situación simulada.** Dos clientes realizaron tres compras y gastaron USD 100, pero uno compró ayer y el otro hace seis meses. Aunque comparten frecuencia y monto, se distinguen por recencia. Propón confirmar si el segundo grupo requiere información de reactivación y contrasta cualquier perfil sugerido por IA con los datos.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Recencia | Días desde la última compra | Distingue actividad reciente |
| Frecuencia | Pedidos en la ventana | Tres compras en cada caso |
| Valor monetario | Importe en la ventana | USD 100 en cada caso |

**Ejemplo complementario de la guía didáctica.**

En una base anonimizada de clientes, el segmento "Compradores recurrentes de alto valor" presenta un ticket promedio de 145 dólares frente a 42 dólares en "Compradores ocasionales".
- *Interpretación errónea:* "Enviar el boletín semanal a un cliente hace que gaste 145 dólares por orden, por lo tanto enviemos boletines diarios a todos". (Confunde asociación observada en un grupo con causalidad directa).
- *Interpretación rigurosa y acción sostenible:* "En los datos depurados del periodo, el segmento de alta frecuencia y recencia reciente concentra el mayor ticket promedio (145 dólares). Se recomienda diseñar una campaña piloto diferenciada de fidelización sin saturar de envíos ni gastar pauta en productos sin stock, midiendo la recompra real durante treinta días".

**Advertencia y error frecuente.** Define el periodo de frecuencia y valor monetario antes de asignar puntajes. Una segmentación pierde comparabilidad si cada registro usa una ventana distinta.

### Profundización técnica de la unidad

#### RFM y recomendaciones asistidas con reglas revisables

RFM organiza recencia, frecuencia y valor monetario bajo una ventana temporal. La recencia necesita fecha de corte; la frecuencia requiere definir compra; el valor monetario necesita aclarar qué importes incluye. Las puntuaciones de grupos dependen de reglas explícitas y no describen el valor humano de una persona.

**Ejemplo resuelto.** Al corte del día 30, un cliente compró el día 28 y otro el día 10. Sus recencias son dos y veinte días según la unidad del caso. Si ambos tienen tres compras y USD 120 acumulados, difieren en recencia, aunque coinciden en frecuencia y valor. Un puntaje combinado necesita explicar qué peso recibe cada componente.

La IA puede sugerir etiquetas o redactar hallazgos, pero cada afirmación debe rastrearse hasta esos cálculos. Una recomendación de reactivación no se ejecuta sin revisar condiciones del canal y pertinencia del contacto. **Reflexión:** ¿cómo cambia una clasificación si se amplía la ventana de compras de uno a tres meses?

#### Datos y condiciones para estudiar el caso en detalle

Culminadas la depuración (Práctica 1), estadística descriptiva (Práctica 2) y visualización interactiva (Práctica 3), el directorio de *AndesMarket Comercio Digital* (caso ficticio diseñado exclusivamente con fines formativos) necesita cerrar el proyecto analítico con dos entregables conectados durante las semanas 7 y 8: primero, aprovechar asistentes de inteligencia artificial para resumir tendencias de ventas con rapidez —evitando errores frecuentes como inventar porcentajes no presentes en la tabla o cargar datos no anonimizados—; y segundo, clasificar a los clientes anonimizados por **recencia, frecuencia y valor monetario (RFM)** para formular recomendaciones comerciales eficientes que eviten compras excesivas de inventario o gastos promocionales inútiles, listas para ser defendidas ante el directorio.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Construcción de tabla de segmentación de clientes por recencia, frecuencia y valor monetario (RFM) (semana 7):** En una pestaña nueva del libro (Segmentacion_RFM), consolide mediante tabla dinámica o fórmulas por cada código de cliente anonimizado: fecha de última compra (**recencia** medida en días desde la fecha de corte de la base), número de transacciones válidas (**frecuencia**) y gasto neto acumulado en dólares estadounidenses (**valor monetario**). Asigne puntajes simples (por ejemplo, del 1 al 3 o alto/medio/bajo usando terciles o percentiles) y clasifique a los compradores en segmentos claros (como *Clientes fieles de alto valor*, *Compradores frecuentes de ticket medio*, *Clientes recientes con potencial* y *Compradores ocasionales o inactivos*).
2. **Generación de resúmenes interpretativos asistidos por inteligencia artificial (Parte 1):** Exporte únicamente las **tablas agregadas anonimizadas** (totales por segmento RFM y métricas clave del tablero) junto con una instrucción estructurada clara hacia un asistente autorizado, solicitando un borrador de resumen interpretativo con variaciones clave y posibles anomalías por revisar. Guarde una copia fiel de la instrucción enviada y la respuesta obtenida.
3. **Auditoría humana rigurosa y contraste conceptual de agrupamiento:** Contraste cada cifra del resumen generado por el asistente frente a su hoja de cálculo marcando en una tabla de verificación qué cifras fueron exactas y cuáles corrigió usted. Añada además un breve apartado explicando por qué, si se aplicaran algoritmos matemáticos como agrupamiento por k-medias (k-means) o agrupamiento jerárquico, sería obligatorio estandarizar primero las escalas entre monto y frecuencia antes de medir distancias entre clientes.
4. **Formulación de recomendaciones comerciales viables y sostenibles (semana 8):** A partir de los segmentos encontrados, redacte al menos **tres recomendaciones operativas** orientadas a optimizar recursos y evitar desperdicios (por ejemplo: ajustar compras de inventario según demanda real por categoría, enfocar campañas de retención hacia segmentos de frecuencia media en lugar de descontar productos que ya se venden sin promoción, o reactivar compradores inactivos con costo controlado). Cuide expresamente no afirmar causalidades no demostradas por los datos.
5. **Integración del proyecto y reporte analítico final (Parte 2):** Consolide el informe técnico final integrando de manera coherente: objetivos, metodología de depuración (Práctica 1), resultados descriptivos (Práctica 2), visualizaciones clave del tablero (Práctica 3), segmentación de clientes y análisis asistido (Práctica 4), limitaciones metodológicas (carácter exploratorio y simulado), declaración de transparencia sobre el uso de inteligencia artificial y referencias bajo normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) (Lafuente Blasco, 2025; Muñetón Santa, 2025; Moreano Guerra y colaboradores, 2026; Núñez Portilla y Guerrero Zambrano, 2025).
6. **Integración con la preparación de sustentación y entrega única en Moodle:** Adjunte o enlace sus diapositivas ejecutivas preparadas en el Trabajo Autónomo (y grabación breve si así lo indica la docente en el aula para simular la defensa ante directorio) junto con el libro de cálculo y el informe final en un único expediente en Moodle al cierre de la semana 8.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 4](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Recencia, frecuencia y monto de clientes ficticios. Comportamiento → Segmento → Revisión → Acción. Una recomendación vinculada con patrones observados](<../03_Recursos_Visuales/10_VENDIG-B3-13_Analisis_de_datos_en_Investigacion/Unidad 04/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Recencia, frecuencia y monto de clientes ficticios | Comportamiento → Segmento → Revisión → Acción | Una recomendación vinculada con patrones observados |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «IA, clasificación y segmentación de información». Muestra a la izquierda la información de partida (recencia, frecuencia y monto de clientes ficticios), en el centro los pasos «Comportamiento → Segmento → Revisión → Acción» y a la derecha el resultado (una recomendación vinculada con patrones observados). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Qué decisión cambiaría si la fecha de última compra estuviera incompleta?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Dos grupos tienen igual valor total de compras, pero uno es reciente y el otro concentra actividad de meses anteriores.

Revisa los valores RFM con una fecha de corte común. Sustenta la acción propuesta con patrones observados y comprueba toda síntesis asistida con la tabla.

El hallazgo diferencia grupos según su actividad. Si sugieres reactivación, señala cómo medirías la respuesta y qué otras condiciones podrían explicar la falta de nuevas compras.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 4 (100 % asincrónico):** En la semana 7, lectura analítica de Muñetón Santa (2025, páginas 28 a 39), apoyada por los criterios de validación humana de Núñez Portilla y Guerrero Zambrano (2025) y conceptos comparativos de segmentación de Moreano Guerra y colaboradores (2026), elaborando una **síntesis de buenas prácticas de análisis con inteligencia artificial**; en la semana 8, preparación de la **sustentación técnica** (diapositivas ejecutivas claras y guion de hallazgos) del informe analítico comercial, entregando un producto único consolidado en Moodle al cierre de la semana 8.
2. **Trabajo Práctico-Experimental de la Unidad 4 (100 % asincrónico):** Práctica de generación de resúmenes interpretativos asistidos por inteligencia artificial y validados manualmente sobre el reporte de ventas, integrada con el proyecto final completo: segmentación básica de clientes con enfoque de recencia, frecuencia y valor monetario (RFM), reporte analítico consolidado con datos depurados, gráficos y recomendaciones comerciales eficientes y sustentación breve ante un directorio simulado. El procedimiento consta en la Práctica 4 de la Guía de Prácticas y se entrega al cierre de la semana 8.

**Evidencia del práctico según la guía de prácticas.** Un único expediente consolidado en Moodle (Apellido_Nombre_Unidad4_Practica4.docx o .pdf junto con el libro editable Apellido_Nombre_Proyecto_Final.xlsx y diapositivas ejecutivas integradas en el mismo envío) que contenga:

- Libro de cálculo actualizado con la pestaña Segmentacion_RFM (recencia, frecuencia, valor monetario y clasificación de clientes) y fórmulas auditables.
- Evidencia del resumen interpretativo asistido por inteligencia artificial, incluyendo la instrucción empleada y la tabla de verificación humana de cifras y supuestos.
- Reporte analítico final completo de *AndesMarket Comercio Digital* integrando hallazgos, gráficos del tablero, recomendaciones comerciales eficientes y citas en normas de citación y referencias de la Asociación Americana de Psicología (séptima edición), junto con la presentación ejecutiva de defensa ante directorio.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 4: Generación de resúmenes comerciales interpretativos asistidos por inteligencia artificial](../../04_Guias_Practicas_V1/GP_VENDIG-B3-13_Analisis_de_datos_en_Investigacion_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Las agrupaciones adquieren valor operativo al explicar qué diferencia a cada grupo y cómo se verificará una acción.

#### Mensaje de reflexión

¿Qué decisión cambiaría si la fecha de última compra estuviera incompleta?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Muñetón Santa, G. (2025). Navegando la investigación social en la era digital: Una guía práctica para el análisis cualitativo y cuantitativo con apoyo de inteligencia artificial. *Documentos de Trabajo INER, 1*(1), 14-41. Lectura prevista: pp. 28-39
- Moreano Guerra, C. B., Escobar Erazo, T. E., Herrera Moreno, L. F., & Escobar Cardenas, J. A. (2026). Evaluación comparativa del clustering jerárquico y k-means para la segmentación estratégica de clientes. *GADE: Revista Científica, 6*(1), 674-703. Lectura prevista: pp. 675-688
- Núñez Portilla, J. E., & Guerrero Zambrano, M. F. (2025). Inteligencia artificial en la investigación científica: Una revisión crítica de las herramientas de análisis. *LATAM Revista Latinoamericana, 6*(4), 3623-3637. Lectura prevista: pp. 3625-3634
