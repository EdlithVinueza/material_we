# CRM y Seguimiento de clientes II

Material educativo para estudiantes de **Ventas Digitales**.

**Fuentes curriculares.** [PEA V2](../../01_PEAs_V2/PEA_VENDIG-P3-16_CrmSeguimientoClientesIi_V2.md) · [Syllabus V2](../../02_Silabos_V2/SYL_VENDIG-P3-16_CrmSeguimientoClientesIi_V2.md) · [Guía didáctica V1](../../03_Guias_Didacticas_V1/GD_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md) · [Guía de prácticas V1](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md)

CRM y Seguimiento de clientes II es una asignatura de la Unidad Profesional de carácter teórico-práctico. Desarrolla competencias para gestionar flujos automatizados de seguimiento comercial, priorizar prospectos mediante puntuación de leads (lead scoring) y diseñar tácticas de fidelización multicanal utilizando herramientas CRM avanzadas. Aborda la automatización de la fuerza de ventas, integración de canales de mensajería comercial, análisis del comportamiento relacional del cliente y monitoreo de retención. Mediante simulaciones en entornos CRM, análisis de casos y diseño de secuencias de comunicación automatizada, el estudiante optimiza los tiempos de respuesta y la eficiencia de los canales de venta digital, con enfoque en ética de datos, calidad del servicio y continuidad operativa.

## Contenido del material

- [Unidad 1. Gestión avanzada de información de clientes en sistemas CRM](#unidad-1)
- [Unidad 2. Automatización del seguimiento comercial en CRM](#unidad-2)
- [Unidad 3. Inteligencia artificial, lead scoring y comportamiento del cliente](#unidad-3)
- [Unidad 4. Flujos automatizados de comunicación, decisión y fidelización](#unidad-4)

<a id="unidad-1"></a>

## Unidad 1: Gestión avanzada de información de clientes en sistemas CRM

![CRM y Seguimiento de clientes II · Unidad 1. Cuenta estratégica. Roles de contacto. Permisos de acceso. Historial omnicanal. Auditoría. Resultado: Una vista priorizada con interacciones trazables](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 01/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Muestra un CRM con dos cuentas empresariales ficticias y destaca la estratégica mediante un indicador de valor del cliente. Dentro de una cuenta, representa la jerarquía de sus contactos y los permisos de acceso. Consolida iconos de llamada, correo, reunión y soporte en una línea temporal y marca un vacío que requiere auditoría. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Una plataforma de gestión de relaciones con clientes (CRM) deja de ser una simple agenda telefónica cuando conecta de manera ordenada la estructura de cada cuenta con el historial completo de sus conversaciones. En el comercio entre empresas y en ventas consultivas de alto monto, una misma **cuenta clave (*Key Account*)** agrupa a varios interlocutores con roles distintos (por ejemplo, quien evalúa aspectos técnicos, quien aprueba presupuesto y quien coordina entregas). Por ello, organizar **jerarquías de contactos** y **campos avanzados personalizados** (como sector, volumen de compra proyectado y **valor del ciclo de vida del cliente (LTV)**, es decir, el ingreso neto estimado que aporta un cliente mientras mantiene relación comercial con la empresa) permite filtrar rápidamente qué cuentas requieren atención prioritaria y quién tiene permiso para visualizar datos comerciales sensibles, resguardando la confidencialidad de la información.

El caso de la unidad guía este recorrido: **Cuenta → Contactos → Historial → Auditoría**.

### Resultados de aprendizaje

El estudiante organiza bases de clientes categorizando cuentas estratégicas y analizando historiales de interacciones en un entorno CRM simulado.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Arquitectura avanzada de datos y segmentación de cuentas | Cuentas clave (Key Accounts)<br>jerarquías de contactos<br>personalización de campos avanzados y permisos. |
| 2. Historiales omnicanal y trazabilidad del contacto | Registro consolidado de llamadas, correos, reuniones y tickets<br>auditoría de interacciones. |

### Caso inicial

La empresa ecuatoriana ficticia *AndinaSoluciones Comerciales* (caso simulado exclusivamente con fines formativos), proveedora de equipamiento corporativo en Quito y Guayaquil, consolidó contactos de ferias, tienda en línea y llamadas en una sola base sin jerarquías ni permisos diferenciados. Como resultado, un cliente estratégico insatisfecho por un despacho retrasado recibió correos promocionales duplicados mientras dos asesores distintos le pedían los mismos datos. Usted deberá depurar su arquitectura de cuentas clave y reconstruir la trazabilidad del incidente.

### Tema 1: Arquitectura avanzada de datos y segmentación de cuentas

#### 1.1. Cuentas clave (Key Accounts)

**Desarrollo técnico y aplicación.** Una cuenta clave se define por criterios del negocio, no solo por tamaño o simpatía del contacto. Examine valor, dependencia, potencial y capacidad de atención con información disponible. Una clasificación debe ser revisable y no justificar privilegios sin condiciones. Identifique qué necesidad requiere gestión diferenciada y cómo se comprobará que aporta continuidad a la relación.

Una cuenta clave se identifica por valor y relación estratégica. Si usas LTV, declara la definición adoptada, el horizonte y los datos disponibles. Contrasta la prioridad con la capacidad real de atención.

**Fundamento y alcance.** Una cuenta estratégica se identifica con criterios de valor, continuidad y ajuste a la capacidad. El LTV es una estimación cuyo precio, horizonte y costos deben explicitarse.

**Caso aplicado.** Una cuenta compra con regularidad, pero el soporte consume recursos variables.

**Resolución.** Evalúa valor y relevancia con horizonte definido y explicita qué costos incluye el LTV.

**Error frecuente y cómo detectarlo.** Un alto volumen bruto puede convivir con un valor neto bajo.

**Comprueba tu comprensión.** ¿Por qué una venta alta puede tener LTV bajo?

**Respuesta comentada.** El costo de atención puede reducir el valor neto estimado.

![Perfil. Identifica clientes con encaje y continuidad. Valor. Estima LTV con horizonte, ingresos y costos explícitos. Capacidad. Contrasta la prioridad con la atención que puedes ofrecer. Un volumen alto es solo uno de los criterios de valor.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 01/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Cuentas clave (Key Accounts)». Para el primer panel usa esta situación. Una cuenta compra con regularidad, pero el soporte consume recursos variables. En el segundo, representa esta acción. Evalúa valor y relevancia con horizonte definido y explicita qué costos incluye el LTV. En el último, incorpora esta comprobación. El costo de atención puede reducir el valor neto estimado. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. jerarquías de contactos

**Desarrollo técnico y aplicación.** Una organización puede tener usuarios, influenciadores, decisores y compradores distintos. La jerarquía registra funciones confirmadas y no un organigrama inventado. Varias personas vinculadas a una cuenta no son necesariamente clientes independientes. Conserve relación e historial para coordinar mensajes y evitar que dos asesores atribuyan decisiones a quien solo transmitió una consulta.

Distingue cuenta, contacto y rol. Un comprador, un evaluador técnico y una persona de soporte pueden pertenecer a la misma empresa. Relaciona contactos a una cuenta única y conserva sus funciones.

**Fundamento y alcance.** La jerarquía indica quién toma decisiones y quién participa en la operación. El CRM puede representar esas relaciones y asignar responsables para mantener la cuenta actualizada.

**Caso aplicado.** Compras, operaciones y soporte hablan con la misma empresa.

**Resolución.** Asocia los contactos a la cuenta y registra su función y autorización.

**Error frecuente y cómo detectarlo.** Confundir un contacto con la cuenta completa fragmenta el historial.

**Comprueba tu comprensión.** ¿Cómo vinculas varios contactos de una empresa?

**Respuesta comentada.** Mediante una cuenta única y roles diferenciados.

#### 1.3. personalización de campos avanzados y permisos.

**Desarrollo técnico y aplicación.** Un campo se incorpora por utilidad y una regla de acceso por responsabilidad. Hacer obligatorio un dato desconocido puede inducir valores inventados. Defina opciones pendientes y validaciones. Los permisos deben permitir tarea sin exponer todo el historial a cualquier usuario. La configuración avanzada se evalúa por consistencia y protección, no por cantidad de campos.

Personaliza campos con un propósito verificable, como responsable de renovación. Limita el acceso a información confidencial según funciones y prueba qué puede consultar o editar cada rol.

**Fundamento y alcance.** Un campo personalizado debe responder a una necesidad operativa y contar con un permiso proporcional. Verifica acceso de lectura y edición según el perfil del usuario.

**Caso aplicado.** La ficha incluye descuentos que solo debe tratar el asesor asignado.

**Resolución.** Personaliza el campo y verifica en modo de prueba el acceso de cada rol.

**Error frecuente y cómo detectarlo.** Ocultarlo en una vista no siempre elimina el permiso de lectura subyacente.

**Comprueba tu comprensión.** ¿Qué compruebas al asignar permiso de descuento?

**Respuesta comentada.** Quién lo lee, quién lo edita y si la restricción es efectiva.

### Tema 2: Historiales omnicanal y trazabilidad del contacto

#### 2.1. Registro consolidado de llamadas, correos, reuniones y tickets

**Desarrollo técnico y aplicación.** El historial consolidado conserva canal, fecha, contenido pertinente y resultado. Una llamada planificada no se registra como realizada. Al unir registros, mantenga identificadores y evite duplicar interacciones. La continuidad depende de distinguir lo solicitado, lo informado y lo acordado, de modo que otro asesor pueda retomar sin repetir preguntas ni confirmar condiciones que nadie verificó.

El historial relaciona llamadas, correos, reuniones y tiquetes con la misma cuenta y fecha. Registra canal, resultado y próximo paso. Conservar la secuencia permite continuar sin repetir preguntas.

**Fundamento y alcance.** La trazabilidad conserva la secuencia de interacciones a través de canales. Una cronología útil reúne identificadores, marcas de tiempo, razones de contacto y resultados.

**Caso aplicado.** Un reclamo entra por teléfono y continúa por correo.

**Resolución.** Conserva canal, fecha y resultado de cada interacción bajo el mismo incidente.

**Error frecuente y cómo detectarlo.** Un relato sin orden temporal dificulta hallar el próximo paso.

**Comprueba tu comprensión.** ¿Qué une un correo y una llamada por el mismo reclamo?

**Respuesta comentada.** La cuenta y el identificador del incidente.

#### 2.2. auditoría de interacciones.

**Desarrollo técnico y aplicación.** La auditoría identifica quién cambió qué y cuándo, con el contexto necesario. Un estado final no explica por sí solo su origen. Revise diferencias entre actividad registrada y compromiso real. Conservar trazabilidad permite corregir sin borrar evidencia y reconocer si un problema procede de un dato inicial, una automatización o una modificación posterior.

Auditar implica comprobar identificadores, fechas, duplicados, permisos y responsables. Un reclamo seguido de una campaña general puede revelar una regla sin exclusión. Registra la causa y cómo verificarás la corrección.

**Fundamento y alcance.** Auditar implica cotejar el historial con reglas y eventos esperados. Documenta qué originó el problema, cómo se corrige y qué prueba confirmará el ajuste.

**Caso aplicado.** Una cuenta con reclamo recibió dos mensajes promocionales.

**Resolución.** Audita reglas de exclusión, fecha y campaña y asigna responsable de corregir la secuencia.

**Error frecuente y cómo detectarlo.** Identificar al último asesor no explica el solapamiento entre automatizaciones.

**Comprueba tu comprensión.** ¿Qué dato revela un solapamiento?

**Respuesta comentada.** Dos ejecuciones aplicables al mismo contacto durante el mismo periodo.

![Incidente. Una cuenta con reclamo recibió dos promociones. Contraste. Revisa identificador, fechas y reglas de exclusión. Corrección. Asigna responsable y prueba si se evita el solapamiento. La auditoría debe explicar qué ocurrió y cómo se corrigió.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 01/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «auditoría de interacciones». Para el primer panel usa esta situación. Una cuenta con reclamo recibió dos mensajes promocionales. En el segundo, representa esta acción. Audita reglas de exclusión, fecha y campaña y asigna responsable de corregir la secuencia. En el último, incorpora esta comprobación. Dos ejecuciones aplicables al mismo contacto durante el mismo periodo. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

En la segunda semana, el foco pasa a la **trazabilidad omnicanal**: un cliente actual escribe por mensajería instantánea, llama por teléfono, abre un correo y luego genera un tiquete de soporte. Si cada canal guarda información aislada o si dos filtros de segmentación se solapan sin control, distintos asesores envían mensajes repetidos o desconocen un reclamo abierto. Auditar el historial consiste en verificar que exista un identificador único por cuenta y contacto, fechas coherentes entre interacciones, etapas claras y un responsable definido para el siguiente paso comercial.

### Ejemplo aplicado y resuelto

**Situación simulada.** Una cuenta estratégica tiene dos contactos y un reclamo de entrega pendiente. Relaciona el reclamo con la cuenta y el contacto correcto. Crea una vista autorizada para el asesor responsable y excluye la cuenta temporalmente de promociones generales. Comprueba el historial antes de retomar el contacto comercial.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Cuenta | Identificador de la empresa | Historial único |
| Contacto | Persona y función dentro de la cuenta | Acceso por rol |
| Interacción | Canal, fecha y responsable | Próximo paso verificable |

**Ejemplo complementario de la guía didáctica.**

En una distribuidora simulada, el área de mercadotecnia crea el segmento *"Cuentas de la región Sierra"* y el área de posventa crea el segmento *"Clientes con compra superior a 1 000 dólares"*. Una empresa cliente ubicada en Quito con compras de 1 500 dólares aparece en ambas listas y recibe dos correos promocionales distintos el mismo día.
- *Diagnóstico de falla:* Las reglas de segmentación se solapan porque no existe un campo jerárquico de exclusión ni un registro único de campaña enviada en el historial.
- *Corrección técnica:* Incorporar un campo de categoría de cuenta clave y una regla de prioridad en la vista filtrada para que, si la cuenta ya pertenece al segmento estratégico, quede excluida de envíos masivos generales, conservando además permisos de solo lectura sobre descuentos especiales para asesores que no gestionan cuentas estratégicas.

**Advertencia y error frecuente.** Al consolidar el historial, verifica la relación entre cuenta y contacto y limita la visibilidad de campos sensibles antes de compartir la vista.

### Profundización técnica de la unidad

#### Modelo de información y responsabilidad sobre el registro

Una cuenta representa la organización o relación comercial y un contacto una persona vinculada. Las jerarquías ayudan a comprender funciones, pero deben basarse en información confirmada. Una cuenta clave se define por criterios del negocio y no solo por el volumen visible de mensajes.

**Ejemplo resuelto.** Una organización tiene una persona usuaria, una responsable técnica y una compradora. Registrar las tres como clientes independientes puede duplicar oportunidades y perder la relación entre necesidades y decisión. Vincular contactos a la cuenta conserva su función, con campos pendientes cuando no existe confirmación.

Los permisos limitan quién puede ver y modificar información. Un campo obligatorio debe justificar su utilidad y no forzar datos inventados. La auditoría distingue autor, fecha y cambio; una nota sin contexto no demuestra qué se comunicó. Revise duplicados conservando historial y criterios de unificación. **Reflexión:** ¿qué información debe poder consultar un asesor y cuál solo una función autorizada?

#### Datos y condiciones para estudiar el caso en detalle

La distribuidora ecuatoriana ficticia *AndinaSoluciones Comerciales* (caso simulado exclusivamente con fines formativos; no representa operaciones de empresas reales) gestiona cuentas corporativas en Quito, Guayaquil y Cuenca mediante formularios web, llamadas, correos y mensajería instantánea. Al revisar su plataforma, la dirección detecta tres fallas críticas: primero, no existen campos personalizados por valor del ciclo de vida del cliente (LTV) ni jerarquía entre empresa y contactos decisores; segundo, cualquier usuario interno puede descargar historiales comerciales confidenciales; y tercero, dos listas dinámicas (*"Clientes Sierra"* y *"Compras mayores a 1 000 dólares"*) se solaparon y enviaron campañas repetidas a la cuenta estratégica ficticia *Corporación Pacífico Sur*, cuyo gerente además reclama que reportó una entrega incompleta por mensajería y al día siguiente un asesor lo llamó desconociendo el tiquete abierto. Usted deberá ordenar la arquitectura de cuentas en la semana 1 y resolver la trazabilidad del reclamo en la semana 2.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Respaldo y auditoría de estructura base (semana 1):** Cree un modelo simulado con al menos ocho cuentas ficticias y doce contactos asociados (incluyendo a *Corporación Pacífico Sur* con tres contactos jerárquicos: comprador, gerente financiero y soporte). Conserve una copia intacta de la tabla inicial antes de aplicar cambios.
2. **Personalización de campos y permisos de confidencialidad:** Defina al menos tres campos avanzados en la estructura de cuentas (categoría de cuenta clave, valor anual proyectado o valor del ciclo de vida del cliente y estado de riesgo relacional) y documente una matriz de permisos por rol comercial (vendedor regional, gerente de cuentas estratégicas y soporte) que restrinja el acceso a historiales o condiciones comerciales sensibles.
3. **Configuración de filtros avanzados y vistas prioritarias:** Configure en el entorno CRM (o modele mediante filtros estructurados en hoja de cálculo si el acceso al simulador presenta restricciones técnicas) al menos dos vistas personalizadas: *"Cuentas estratégicas en riesgo"* y *"Cuentas clave por monto y última interacción"*. Incluya una regla explícita de exclusión mutua para evitar que las cuentas ubicadas en dos segmentos reciban mensajes duplicados.
4. **Reconstrucción cronológica del caso de cliente insatisfecho (semana 2):** Ordene en una línea de tiempo omnicanal todas las interacciones ficticias de *Corporación Pacífico Sur* (correo de cotización, compra, tiquete por entrega incompleta en mensajería, llamada sin registro previo y envío duplicado de promoción), señalando en qué punto exacto se rompió el registro único.
5. **Propuesta técnica de corrección y prueba límite:** Redacte el protocolo operativo de registro obligatorio tras cada contacto y compruebe sus filtros con un registro normal (cuenta estratégica activa), un registro límite (cuenta con monto en el umbral exacto de clasificación) y un registro erróneo (contacto duplicado sin cuenta padre asociada).
6. **Verificación ética, citas e integración única:** Revise que todas las capturas o tablas utilicen únicamente datos ficticios, incluya las referencias consultadas bajo normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) y suba todo en un único archivo ordenado en Moodle.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 1](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Datos comerciales y permisos por rol. Cuenta → Contactos → Historial → Auditoría. Una vista priorizada con interacciones trazables](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 01/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Datos comerciales y permisos por rol | Cuenta → Contactos → Historial → Auditoría | Una vista priorizada con interacciones trazables |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Gestión avanzada de información de clientes en sistemas CRM». Muestra a la izquierda la información de partida (datos comerciales y permisos por rol), en el centro los pasos «Cuenta → Contactos → Historial → Auditoría» y a la derecha el resultado (una vista priorizada con interacciones trazables). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Qué campo te permitiría reconstruir por qué dos personas contactaron al mismo cliente?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Una cuenta estratégica tiene un apoyo técnico abierto y recibe dos mensajes promocionales después de una llamada pendiente.

Reúne interacciones bajo la misma cuenta y caso. Comprueba permisos, reglas de segmentación y hora de envío antes de determinar qué produjo la duplicación.

La corrección puede requerir una exclusión operativa y un responsable claro. Verifica que la nueva vista conserve el historial y que la cuenta siga recibiendo atención.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 1 (100 % asincrónico):** Lectura comprensiva de los capítulos 3 y 4 de Prior, Buttle y Maklan (2024) en la semana 1 para analizar conceptualmente la arquitectura relacional de bases de clientes, complementada en la semana 2 con la redacción de un **informe de diagnóstico del historial de cliente en el sistema**, integrando ambos avances en un solo archivo en Moodle al cierre de la semana 2.
2. **Trabajo Práctico-Experimental de la Unidad 1 (100 % asincrónico):** Desarrollo integrado de una práctica de configuración de filtros avanzados, permisos y vistas personalizadas para cuentas prioritarias junto con un taller de auditoría de trazabilidad sobre un caso de cliente insatisfecho y su propuesta de corrección. Los pasos detallados figuran en la Práctica 1 de la Guía de Prácticas y se entregan como producto único al cierre de la semana 2.

**Evidencia del práctico según la guía de prácticas.** Un único documento en formato editable o en formato de documento portátil (PDF) identificado como Apellido_Nombre_Unidad1_Practica1 (acompañado del archivo editable de hoja de cálculo si modeló allí la matriz de gestión de cuentas estratégicas), que integre:

- Matriz de arquitectura de cuentas, jerarquías de contactos, campos avanzados y tabla de permisos por rol con justificación de confidencialidad.
- Capturas legibles o tabla verificable de las vistas personalizadas, filtros avanzados y regla aplicada para eliminar el solapamiento de segmentos.
- Reconstrucción de trazabilidad omnicanal del cliente insatisfecho ficticio, prueba con caso normal, límite y erróneo, y protocolo de corrección.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 1: Configuración de filtros avanzados y vistas para cuentas prioritarias](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Una cuenta estratégica requiere coordinación entre personas, registros completos y privacidad proporcional a cada función.

#### Mensaje de reflexión

¿Qué campo te permitiría reconstruir por qué dos personas contactaron al mismo cliente?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Prior, D. D., Buttle, F., & Maklan, S. (2024). *Customer relationship management: Concepts, applications and technologies* (5th ed.). Routledge. Lectura prevista: Caps. 3-4
- Fonseca Romero, G. N., Armijos Arcos, F. M., Urgilés Rodríguez, B. E., & Márquez Sañay, F. R. (2026). *CRM estratégico con insumos multivariantes: Claves para fidelizar clientes*. Religación Press. Lectura prevista: Cap. 2

<a id="unidad-2"></a>

## Unidad 2: Automatización del seguimiento comercial en CRM

![CRM y Seguimiento de clientes II · Unidad 2. Cambio de etapa. Regla de asignación. Zona y producto. Equipo especialista. Alerta de plazo. Resultado: Una secuencia que evita acciones repetidas](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 02/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Dibuja un flujo de CRM donde un cambio de etapa activa una regla y deriva el prospecto al especialista de su zona o producto. Señala un control de ejecución única y añade una alarma que se enciende cuando se aproxima el plazo de respuesta. Termina con el historial de la asignación y un único recordatorio. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

En ventas digitales, responder cinco minutos después frente a responder dos días más tarde suele definir si un prospecto avanza o elige a la competencia. La **automatización del seguimiento comercial** permite que el sistema ejecute tareas repetitivas de coordinación de manera inmediata y consistente. Todo flujo automatizado responde a cuatro piezas lógicas: un **disparador (*trigger*)**, que es el evento que inicia el proceso (por ejemplo, un prospecto completa un formulario o una oportunidad cambia a etapa *"Propuesta enviada"*); una **condición**, que filtra a quién sí y a quién no aplica la regla (como provincia, monto estimado o ausencia de tarea abierta); una **acción**, que puede asignar el prospecto a un asesor por especialidad, crear un recordatorio con fecha límite o enviar una alerta interna; y una **regla de salida o control de repetición**, que detiene el flujo si el cliente ya fue atendido o si el evento se disparó por error dos veces.

El caso de la unidad guía este recorrido: **Evento → Regla → Asignación → Alerta**.

### Resultados de aprendizaje

El estudiante configura secuencias automatizadas de seguimiento comercial con disparadores (triggers) y alertas operativas ante cambios de estado.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Reglas de asignación y automatización de tareas operativas | Disparadores basados en eventos<br>enrutamiento de prospectos por zona o especialidad<br>recordatorios automáticos. |

### Caso inicial

Continuando con el escenario simulado de *AndinaSoluciones Comerciales*, el equipo comercial integrado por tres asesores asincrónicos (uno para la región Sierra, otro para la región Costa y un especialista en cuentas corporativas) pierde oportunidades porque los prospectos nuevos se asignan manualmente y las cotizaciones enviadas quedan sin recordatorio. Además, un borrador anterior de automatización enviaba múltiples correos cada vez que un usuario descargaba dos fichas técnicas seguidas. Deberá diseñar tres reglas ordenadas, colaborativas y sin envíos redundantes.

### Tema 1: Reglas de asignación y automatización de tareas operativas

#### 1.1. Disparadores basados en eventos

**Desarrollo técnico y aplicación.** El disparador responde a un evento y necesita una condición precisa. «Interesado» debe traducirse a una señal registrada y no a impresión. Defina identidad de evento para evitar ejecutar dos veces un efecto. Un fallo parcial necesita un estado recuperable. Activar una regla no demuestra que todas sus acciones hayan terminado o que su resultado sea correcto.

Un disparador inicia el flujo cuando ocurre un evento relevante. Define si se activa al crear la ficha o al cambiar de estado. Añade una condición que verifique que el mismo evento todavía no se haya procesado.

**Fundamento y alcance.** Un evento activador marca un cambio definido. Evalúa la condición con el estado que corresponde y registra cuándo se ejecutó la acción para controlar repeticiones.

**Caso aplicado.** Un contacto cambia a propuesta enviada y después actualiza su teléfono.

**Resolución.** Limita el disparador a la transición de etapa y confirma que la edición no repita la ejecución.

**Error frecuente y cómo detectarlo.** Si el flujo se activa al editar cualquier campo puede duplicar tareas.

**Comprueba tu comprensión.** ¿Qué cambio debe disparar el flujo?

**Respuesta comentada.** La transición a la etapa definida, con registro de ejecución.

![Evento. La oportunidad cambia a «Propuesta enviada». Regla. Asigna el caso una vez y conserva el registro de ejecución. Prueba. Editar el teléfono después no debe repetir la asignación. Separa una transición del resto de las ediciones.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 02/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Disparadores basados en eventos». Para el primer panel usa esta situación. Un contacto cambia a propuesta enviada y después actualiza su teléfono. En el segundo, representa esta acción. Limita el disparador a la transición de etapa y confirma que la edición no repita la ejecución. En el último, incorpora esta comprobación. La transición a la etapa definida, con registro de ejecución. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. enrutamiento de prospectos por zona o especialidad

**Desarrollo técnico y aplicación.** El enrutamiento relaciona características verificadas y capacidad de atención. Una zona desconocida necesita salida de revisión y no una asignación aleatoria presentada como correcta. Defina prioridad cuando coincidan reglas. Compruebe que un cambio de responsable conserva contexto y no produce contactos simultáneos incompatibles con lo que el prospecto ya acordó.

El enrutamiento asigna por zona, producto o especialidad según criterios conocidos. Define qué regla gana si dos se aplican, y a qué persona se deriva si falta un campo indispensable.

**Fundamento y alcance.** El enrutamiento distribuye el trabajo mediante criterios verificables. Prevé coincidencias entre criterios y casos sin datos suficientes para que cada oportunidad tenga un destino.

**Caso aplicado.** Un prospecto de Costa también pertenece a una línea de atención especializada.

**Resolución.** Define prioridad entre criterios y un responsable alterno si faltan datos.

**Error frecuente y cómo detectarlo.** Dos asignaciones simultáneas pueden producir contactos repetidos.

**Comprueba tu comprensión.** ¿Quién recibe el caso si coinciden zona y especialidad?

**Respuesta comentada.** El destino que establezca la prioridad explícita del proceso.

#### 1.3. recordatorios automáticos.

**Desarrollo técnico y aplicación.** Un recordatorio tiene destinatario, fecha, condición y criterio de cese. Si el pedido ya se resolvió, la secuencia debe actualizarse. Distinga preparado y enviado y registre fallo. La prueba incluye evento duplicado y cambio de estado antes del vencimiento; esos recorridos detectan errores que una demostración con un único caso favorable no revela.

Un recordatorio necesita responsable, vencimiento y condición de cierre. Vincúlalo al tiempo de respuesta acordado y prueba que se cancele cuando el cliente ya fue atendido. Conserva una alerta por evento.

**Fundamento y alcance.** Una alerta anticipa o señala el incumplimiento de un plazo. Un acuerdo de nivel de servicio necesita un momento de inicio, tiempo de respuesta y un criterio de cierre.

**Caso aplicado.** Un recordatorio vence pronto y el cliente ya obtuvo respuesta.

**Resolución.** Comprueba que el registro de atención cierre la alerta y conserve el historial.

**Error frecuente y cómo detectarlo.** Un plazo sin condición de salida puede generar avisos aun después del cierre.

**Comprueba tu comprensión.** ¿Cuándo se cierra la alerta?

**Respuesta comentada.** Cuando se confirma la respuesta dentro del criterio definido.

![Asigna. Define a quién corresponde responder. Programa. Establece vencimiento según el tiempo acordado. Cierra. Registra la respuesta y desactiva la alerta pendiente. La condición de salida evita recordatorios innecesarios.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 02/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «recordatorios automáticos». Para el primer panel usa esta situación. Un recordatorio vence pronto y el cliente ya obtuvo respuesta. En el segundo, representa esta acción. Comprueba que el registro de atención cierre la alerta y conserve el historial. En el último, incorpora esta comprobación. Cuando se confirma la respuesta dentro del criterio definido. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

Al diseñar flujos colaborativos entre varios vendedores de un equipo comercial, es fundamental cuidar dos aspectos: primero, evitar el envío innecesario de correos masivos repetitivos —lo cual no solo satura al cliente, sino que genera consumo innecesario de recursos digitales y energía en servidores (criterio de eficiencia ambiental digital)—; y segundo, probar siempre el flujo con al menos tres tipos de casos simulados: un caso normal que debe activarse, un caso límite y un caso erróneo o duplicado que debe ser bloqueado por las condiciones del sistema.

### Ejemplo aplicado y resuelto

**Situación simulada.** Una oportunidad entra en «Propuesta enviada» y la zona Costa activa asignación. Crea un recordatorio para el asesor responsable dentro del plazo acordado. Repite la edición del contacto y verifica que el registro siga con una sola tarea activa y una única asignación.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Activación | Cambio a propuesta enviada | Evalúa zona |
| Asignación | Costa con asesor disponible | Crea una tarea |
| Control | Segunda edición del contacto | Conserva una sola ejecución |

**Ejemplo complementario de la guía didáctica.**

En el flujo simulado de una tienda digital, cada vez que se actualiza la ficha de un prospecto de Guayaquil se dispara una regla que asigna tarea de llamada al asesor de la región Costa. Un vendedor edita el teléfono del contacto dos veces seguidas y el disparador se activa dos veces generando tareas duplicadas.
- *Causa técnica:* La regla solo evalúa *"el campo ciudad es Guayaquil"*, sin verificar si ya existe una tarea de primer contacto abierta o si la propiedad de origen ya fue procesada.
- *Solución operativa:* Añadir la condición *"y el campo estado de asignación está vacío"* más un registro de ejecución única, de modo que la segunda edición actualice los datos sin duplicar tareas ni notificaciones.

**Advertencia y error frecuente.** Un disparador demasiado amplio puede activarse con una edición inocua. Prueba que solo responda al cambio de estado previsto y que cierre trabajos ya atendidos.

### Profundización técnica de la unidad

#### Disparadores y enrutamiento sin duplicación

Un disparador responde a un evento definido y no a una interpretación vaga como «cliente interesado». El enrutamiento necesita reglas de zona, especialidad o disponibilidad y una salida cuando no coincide ningún criterio. Los recordatorios requieren condición de cancelación para no perseguir tareas ya resueltas.

**Ejemplo resuelto.** Una solicitud de zona norte se asigna al equipo correspondiente. Si no hay responsable disponible, queda en una cola identificada y se genera aviso de revisión. Si el mismo evento llega dos veces, la regla reconoce el identificador y evita crear oportunidades duplicadas. Cada acción conserva estado y fecha.

Pruebe entrada normal, datos incompletos y excepción. Una automatización marcada «activa» no demuestra que todos sus eventos hayan terminado correctamente. El historial permite identificar si falló la condición, la asignación o el envío. Modifique una regla a la vez y compruebe efectos sobre casos ya abiertos. **Reflexión:** ¿qué mecanismo impide que dos asesores contacten simultáneamente al mismo prospecto por una asignación duplicada?

#### Datos y condiciones para estudiar el caso en detalle

En la empresa ficticia *AndinaSoluciones Comerciales* (escenario simulado exclusivamente con fines formativos), el equipo de ventas trabaja de manera distribuida con tres roles colaborativos asignados en Moodle (asesor región Sierra, asesor región Costa y especialista en cuentas corporativas). Actualmente, cuando ingresa un prospecto web o cambia de etapa una cotización, nadie recibe alerta automática y algunas oportunidades se enfrían durante días; al mismo tiempo, un intento previo de automatización enviaba dos correos seguidos cada vez que un asesor actualizaba dos veces el mismo registro. Su misión consiste en diseñar de manera colaborativa asincrónica (o documentando la matriz completa de roles si trabaja excepcionalmente de forma individual autorizada) **tres reglas automatizadas limpias** que asignen tareas según zona o especialidad, generen recordatorios dentro de los acuerdos de nivel de servicio (SLA) y bloqueen cualquier disparo duplicado o correo masivo innecesario.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Diseño colaborativo de la arquitectura de las tres reglas (semana 3):** Defina de forma coordinada con sus pares en Moodle (dejando constancia de los acuerdos asincrónicos en su documento) tres reglas complementarias:
   - **Regla 1 (enrutamiento por zona o especialidad):** Al crearse un prospecto nuevo desde formulario web, asignarlo automáticamente al asesor de Sierra, Costa o cuentas corporativas según provincia y categoría.
   - **Regla 2 (alerta de seguimiento por cambio de estado):** Cuando una oportunidad pase a estado *"Cotización enviada"* y no registre actividad en 48 horas, generar una tarea de recordatorio para el asesor responsable sin enviar correos masivos al cliente.
   - **Regla 3 (control antirepetición y eficiencia energética):** Bloquear nuevas alertas o correos automáticos si el evento se dispara por segunda vez sobre el mismo prospecto dentro del mismo ciclo, evitando redundancias e impacto innecesario de envíos masivos.
2. **Representación gráfica e implementación en entorno disponible:** Construya el diagrama de flujo completo (con entradas, bifurcaciones condicionales y salidas) y configure las tres reglas en el módulo de automatización del CRM disponible (o en el simulador de flujos equivalente indicado por el docente), documentando cada condición exacta.
3. **Prueba con caso normal (semana 4):** Ejecute o simule paso a paso un registro ficticio completo (por ejemplo, prospecto de Guayaquil con compra corporativa) verificando que se active la Regla 1 y, tras el cambio a *"Cotización enviada"*, se programe el recordatorio de la Regla 2 al responsable exacto.
4. **Prueba con caso límite y caso erróneo (disparador doble):** Compruebe primero qué sucede cuando un registro ingresa sin provincia especificada (debe ir a una cola de revisión manual sin quedar huérfano), y segundo qué ocurre cuando el disparador se activa **dos veces seguidas** por una edición repetida del mismo evento: documente cómo la Regla 3 detecta la repetición y registra por qué no corresponde ejecutar la acción nuevamente.
5. **Verificación ética y eficiencia digital:** Confirme que ninguna regla envía mensajes automáticos reiterados al cliente y justifique brevemente cómo esta contención reduce tanto la fatiga comercial como el envío ineficiente de correos redundantes.
6. **Integración única en Moodle:** Reúna diagrama, capturas de configuración o tabla lógica, bitácora de pruebas (normal, límite y repetida), acuerdos colaborativos y referencias bajo normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) en un solo archivo.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 2](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Cambios de estado y plazo acordado. Evento → Regla → Asignación → Alerta. Una secuencia que evita acciones repetidas](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 02/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Cambios de estado y plazo acordado | Evento → Regla → Asignación → Alerta | Una secuencia que evita acciones repetidas |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Automatización del seguimiento comercial en CRM». Muestra a la izquierda la información de partida (cambios de estado y plazo acordado), en el centro los pasos «Evento → Regla → Asignación → Alerta» y a la derecha el resultado (una secuencia que evita acciones repetidas). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Cómo debería reaccionar el flujo si la zona y el producto apuntan a equipos distintos?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Se actualiza una propuesta, el CRM alerta a dos personas y luego vuelve a hacerlo al editar el teléfono del contacto.

Delimita el evento activador, define prioridad de asignación y agrega un control de ejecución. Prueba una transición real y una edición posterior del mismo registro.

La automatización funciona cuando el caso llega a una persona a tiempo y se evitan tareas repetidas. Registra cuándo termina la alerta después de la respuesta.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 2 (100 % asincrónico):** Lectura comprensiva del capítulo 3 de Paredes Bermeo (2024) sobre estandarización del contacto comercial durante la semana 3, complementada en la semana 4 con una **síntesis práctica de buenas prácticas de seguimiento y control de errores en flujos**, entregando un único documento consolidado en Moodle al cierre de la semana 4.
2. **Trabajo Práctico-Experimental de la Unidad 2 (100 % asincrónico):** Práctica de laboratorio orientada a diseñar y configurar **tres reglas de automatización de tareas comerciales** (enrutamiento colaborativo por zona o especialidad, recordatorios automáticos de seguimiento y bloqueo de acciones redundantes), verificando su comportamiento ante eventos normales y duplicados. El procedimiento figura en la Práctica 2 de la Guía de Prácticas y se entrega al cierre de la semana 4.

**Evidencia del práctico según la guía de prácticas.** Un único documento en formato editable o en formato de documento portátil (PDF) identificado como Apellido_Nombre_Unidad2_Practica2 (junto con el archivo exportado del diagrama si utilizó una herramienta externa), que contenga:

- Constancia breve de coordinación colaborativa asincrónica entre roles del equipo comercial simulado.
- Diagrama visual claro y tabla técnica de las tres reglas de automatización (disparador, condición, acción y regla de salida o bloqueo).
- Evidencias verificables (capturas del CRM o tabla de trazado paso a paso) de la prueba con caso normal, caso límite y evento disparador activado dos veces.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 2: Implementación de tres reglas de automatización de seguimiento en CRM](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Registra ejecuciones y comprueba duplicados para que la automatización preserve continuidad en el seguimiento.

#### Mensaje de reflexión

¿Cómo debería reaccionar el flujo si la zona y el producto apuntan a equipos distintos?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Paredes Bermeo, E. E. (2024). *Técnicas efectivas aplicadas al proceso de ventas*. Editorial Instituto Tecnológico Superior Ibarra. Lectura prevista: Cap. 3

<a id="unidad-3"></a>

## Unidad 3: Inteligencia artificial, lead scoring y comportamiento del cliente

![CRM y Seguimiento de clientes II · Unidad 3. Encaje del perfil. Interacciones. Puntuación. Validación MQL a SQL. Resultado: Una cola de prospectos con prioridad explicable](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 03/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Representa tarjetas de prospectos que acumulan puntos en columnas separadas de encaje e interacciones. Muestra sumas por una solicitud activa y restas por inactividad. Añade un umbral del paso de MQL a SQL y un caso dudoso en revisión humana antes de que el CRM confirme la prioridad. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Cuando un negocio digital recibe decenas o cientos de contactos semanales, dedicar el mismo esfuerzo de llamada a todos desperdicia el tiempo del equipo de ventas y reduce la atención a quienes sí tienen necesidad real. El **sistema de puntuación de prospectos (*lead scoring*)** ordena la cola de atención combinando dos dimensiones complementarias: la **puntuación demográfica o de perfil** (qué tan bien encaja el prospecto con el cliente ideal según segmento, tamaño o cargo con capacidad de decisión) y la **puntuación conductual** (qué acciones reales demuestran interés reciente, como solicitar una demostración, responder mensajes, asistir a un seminario web o abrir correos informativos). También aplica **criterios de resta de puntos** cuando pasan semanas sin interacción o cuando el contacto no cumple requisitos mínimos del servicio.

El caso de la unidad guía este recorrido: **Perfil → Conducta → Puntuación → Revisión**.

### Resultados de aprendizaje

El estudiante calcula y asigna puntajes de cualificación a prospectos según criterios de interacción y perfil comercial, sustentando la priorización.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Modelos de puntuación de prospectos (Lead Scoring) | Puntuación demográfica vs. conductual<br>criterios de suma y resta de puntos<br>calificación comercial (MQL a SQL). |

### Caso inicial

La coordinación comercial de *AndinaSoluciones Comerciales* (escenario ficticio) acumuló quince prospectos activos ingresados durante las últimas dos semanas por distintos canales (seminarios web, anuncios profesionales, mensajería directa, referidos, formularios y ferias digitales). Como el equipo solo puede realizar seis contactos profundos por jornada, requiere una matriz transparente de *lead scoring* para decidir quién pasa de inmediato a atención de ventas, quién sigue en nutrición informativa y qué casos requieren revisión humana especial.

### Tema 1: Modelos de puntuación de prospectos (Lead Scoring)

#### 1.1. Puntuación demográfica vs. conductual

**Desarrollo técnico y aplicación.** El encaje demográfico y la conducta aportan señales diferentes y su utilidad depende del objetivo. Un atributo descriptivo no demuestra intención de compra. Una acción puede tener varias explicaciones. Mantenga procedencia y fecha y no complete valores por inferencia. La puntuación organiza revisión comercial y no mide el valor personal o la confiabilidad humana del contacto.

La puntuación de perfil mide encaje y la conductual interés observable. Pondera señales como una solicitud de demostración y revisa su fuente. Mantén visible el aporte de cada dimensión a la puntuación total.

**Fundamento y alcance.** El encaje mide compatibilidad con el perfil buscado y la conducta aporta señales de interés. Los componentes deben poder explicarse y calcularse por separado.

**Caso aplicado.** Una cuenta encaja en el sector y descargó una ficha técnica.

**Resolución.** Separa puntos de perfil e interacción y comprueba la vigencia de cada señal.

**Error frecuente y cómo detectarlo.** Una descarga repetida puede reflejar el mismo evento y sumar indebidamente.

**Comprueba tu comprensión.** ¿Qué diferencia el encaje de una descarga?

**Respuesta comentada.** El primero describe compatibilidad; la segunda aporta evidencia conductual.

![Perfil. Mide si la cuenta encaja por sector o tipo de compra. Conducta. Mide señales observables, como solicitar una demostración. Control. Evita contar dos veces el mismo evento. La prioridad se explica con ambas dimensiones.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 03/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Puntuación demográfica vs. conductual». Para el primer panel usa esta situación. Una cuenta encaja en el sector y descargó una ficha técnica. En el segundo, representa esta acción. Separa puntos de perfil e interacción y comprueba la vigencia de cada señal. En el último, incorpora esta comprobación. El primero describe compatibilidad; la segunda aporta evidencia conductual. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. criterios de suma y resta de puntos

**Desarrollo técnico y aplicación.** La suma y resta de puntos necesita reglas observables y versión. Un dato ausente no equivale a condición negativa. Si un requisito indispensable falla, el total no debería compensarlo por acumular señales menores sin justificación. Examine falsos positivos y casos descartados para comprobar que el umbral ayuda a cualificar y no solo a reducir el conjunto.

Expresa sumas y restas en reglas reproducibles. Una apertura aislada puede pesar menos que una respuesta. Diferencia inactividad de falta de datos y evita duplicar puntos por señales del mismo evento.

**Fundamento y alcance.** Una ponderación expresa cuánto aporta cada evidencia al orden de prioridad. Aplica criterios homogéneos, vigencia de las señales y reglas para puntuar eventos relacionados.

**Caso aplicado.** Una respuesta aumenta la prioridad y la inactividad la reduce.

**Resolución.** Publica regla, ventana y evidencia y revisa un caso con datos faltantes.

**Error frecuente y cómo detectarlo.** Una ausencia de registro no demuestra ausencia de interés.

**Comprueba tu comprensión.** ¿Cómo tratarías dos descargas idénticas?

**Respuesta comentada.** Comprueba si representan un solo evento antes de puntuar.

#### 1.3. calificación comercial (MQL a SQL).

**Desarrollo técnico y aplicación.** MQL y SQL requieren definiciones acordadas entre funciones. Un cambio de etiqueta debe corresponder a verificación y aceptación del siguiente paso. Registre motivo de devolución y datos pendientes para mejorar el proceso. Una puntuación alta no sustituye confirmar necesidad o capacidad; el asesor continúa el diagnóstico y no presenta el puntaje como probabilidad garantizada de cierre.

MQL identifica a un prospecto calificado por marketing y SQL a quien ventas valida para avanzar. Revisa casos cerca del umbral y mide falsos positivos y negativos. La intervención humana comprueba alertas sugeridas por IA.

**Fundamento y alcance.** La transición de MQL a SQL incorpora validación comercial. Examinar errores de clasificación permite ajustar el umbral y comprobar si la puntuación refleja oportunidades útiles.

**Caso aplicado.** Un caso llega justo al umbral de 30 puntos.

**Resolución.** Confirma necesidad, condiciones y criterio de ventas antes de pasarlo a SQL.

**Error frecuente y cómo detectarlo.** Revisar casos de falso positivo y falso negativo permite recalibrar.

**Comprueba tu comprensión.** ¿Qué confirma la transición a SQL?

**Respuesta comentada.** Que ventas valida necesidad y siguiente paso bajo sus criterios.

![Umbral. Un prospecto llega a 30 puntos en el ejemplo. Validación. Ventas comprueba encaje, necesidad y siguiente paso. Revisión. Coteja casos mal asignados para ajustar el modelo. El puntaje orienta. El equipo valida antes de avanzar.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 03/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «calificación comercial (MQL a SQL)». Para el primer panel usa esta situación. Un caso llega justo al umbral de 30 puntos. En el segundo, representa esta acción. Confirma necesidad, condiciones y criterio de ventas antes de pasarlo a SQL. En el último, incorpora esta comprobación. Que ventas valida necesidad y siguiente paso bajo sus criterios. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

A partir de un umbral transparente previamente definido, los contactos avanzan de **prospecto cualificado por mercadotecnia (MQL)** —aquel que muestra interés inicial y debe seguir recibiendo información útil— a **prospecto cualificado para ventas (SQL)** —aquel que reúne encaje e intención suficiente para pasar a contacto directo de un asesor—. Aunque las herramientas modernas de **inteligencia artificial (IA)** dentro de las plataformas de gestión de relaciones con clientes (CRM) ayudan a detectar patrones y sugerir puntajes, la decisión comercial final requiere **supervisión humana**: un puntaje por reglas suma puntos para establecer **prioridad operativa**, nunca equivale automáticamente a un porcentaje estadístico de probabilidad de cierre, y siempre debe auditarse para corregir **falsos positivos** (puntaje alto sin intención real de compra) y **falsos negativos** (buen cliente potencial con baja puntuación digital por preferir contacto directo).

### Ejemplo aplicado y resuelto

**Situación simulada.** Asigna 20 puntos por encaje, 15 por una solicitud y resta 5 por inactividad. El caso suma 30 puntos. Si el umbral es 30, revisa que la señal esté vigente y que el equipo de ventas valide la oportunidad antes de cambiarla a SQL.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Perfil | Encaje verificado | +20 |
| Conducta | Solicitud e inactividad | +15 y −5 |
| Calificación | Total de 30 | Validación humana antes de avanzar |

**Ejemplo complementario de la guía didáctica.**

Suponga una regla básica donde tener *necesidad confirmada* suma 2 puntos y registrar *interacción reciente* suma 1 punto. Un prospecto obtiene 3 puntos y otro alcanza 1 punto.
- *Error frecuente:* Afirmar en el reporte que el primer prospecto tiene *"75 % o 100 % de probabilidad matemática de comprar"*, o atender primero a alguien que abrió diez correos informativos pero trabaja en un cargo sin poder de decisión ni necesidad confirmada (falso positivo).
- *Criterio riguroso:* Explicar que 3 puntos sitúan al prospecto en prioridad alta según la regla interna para ser contactado por un asesor dentro del siguiente turno comercial, y revisar manualmente si una empresa con alta necesidad confirmada pero cero clics recientes en correos (falso negativo digital) merece validación telefónica directa antes de descartarla.

**Advertencia y error frecuente.** Controla indicadores correlacionados para evitar sumar dos veces el mismo comportamiento. Revisa manualmente los casos cerca del umbral.

### Profundización técnica de la unidad

#### Lead scoring y significado de una puntuación

La puntuación combina señales de encaje y comportamiento bajo criterios explícitos. Un valor alto no es una probabilidad calibrada de compra salvo que exista un modelo y una evaluación que lo sostengan. Abrir correos muchas veces puede representar interés, revisión automática u otra conducta.

**Ejemplo resuelto.** Regla simulada: necesidad confirmada +20, plazo compatible +15 y dato de contacto inválido −25. Un registro con los dos primeros criterios suma 35; si el contacto no sirve, queda en 10. La suma orienta revisión según la política, pero no autoriza a inventar presupuesto o capacidad decisora. «Dato desconocido» se conserva distinto de incumplimiento.

El paso de MQL a SQL necesita una definición compartida entre funciones. Revise falsos positivos, oportunidades descartadas que sí encajaban y señales que perjudican a públicos poco representados. Si cambian reglas, identifique versión y fecha para comparar puntajes correctamente. **Reflexión:** ¿qué evidencia valida que el umbral utilizado mejora la cualificación y no solo reduce la cantidad de registros?

#### Datos y condiciones para estudiar el caso en detalle

La gerencia comercial de la empresa ficticia *AndinaSoluciones Comerciales* (base didáctica simulada exclusivamente con fines formativos; no corresponde a organizaciones ni prospectos reales) reunió **15 prospectos simulados** ingresados durante los últimos catorce días desde distintos canales de comercio entre empresas (B2B), incluidos formularios web, seminarios en línea, anuncios profesionales y mensajería directa (DM). El equipo comercial dispone de tiempo limitado y necesita aplicar una fórmula explícita de puntuación de prospectos (*lead scoring*) en su plataforma de gestión de relaciones con clientes (CRM) para decidir qué contactos califican como prospectos cualificados por mercadotecnia (MQL) y cuáles suben a prospectos cualificados para ventas (SQL).

Recuerde un principio metodológico clave al interpretar su matriz: asignar puntos por reglas (por ejemplo, 2 puntos por necesidad confirmada más 1 punto por interacción reciente igual a 3 puntos) sirve para **ordenar prioridades operativas** según esa regla explícita, pero **nunca equivale a un porcentaje de probabilidad estadística de compra** (por ejemplo, 3 puntos no equivalen a 75 % de probabilidad de cierre). Asimismo, deberá revisar manualmente si la fórmula o una sugerencia automatizada basada en inteligencia artificial (IA) genera un falso positivo o un falso negativo.

A continuación dispone de la **base completa de 15 prospectos simulados**. Copie íntegramente esta tabla a su hoja de cálculo respetando los identificadores exactos del LD-01 al LD-15 antes de calcular la columna final:

| ID_Lead | Prospecto_Simulado | Segmento | Fuente_CRM | Necesidad_Confirmada | Interacciones_14d | Apertura_Correos | Cargo_Decisor | Score_Calculado |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LD-01 | Comercial Norte S.A. | Retail B2B | Webinar técnico | Sí | 3 | 75% | Sí | Por puntuar |
| LD-02 | Diseño Creativo Lab | Servicios | Formulario web | No | 1 | 40% | Sí | Por puntuar |
| LD-03 | Importadora Sierra | Comercio | LinkedIn Ads | Sí | 4 | 80% | Sí | Por puntuar |
| LD-04 | Café Altura | Alimentos | Instagram DM | Sí | 1 | 50% | No | Por puntuar |
| LD-05 | Constructora Valle | Construcción | Referido | Sí | 2 | 65% | Sí | Por puntuar |
| LD-06 | Farmacia Bienestar | Salud | Descarga guía | No | 0 | 20% | No | Por puntuar |
| LD-07 | Transportes Costa | Logística | Demo solicitada | Sí | 3 | 90% | Sí | Por puntuar |
| LD-08 | Estudio Contable Ruiz | Servicios | Correo entrante | No | 2 | 55% | Sí | Por puntuar |
| LD-09 | AgroInsumos Loja | Agroindustria | Feria digital | Sí | 0 | 30% | No | Por puntuar |
| LD-10 | TechParts Ecuador | Tecnología | Chatbot web | Sí | 4 | 85% | Sí | Por puntuar |
| LD-11 | Hotel Mirador Sur | Turismo | Formulario web | No | 1 | 35% | No | Por puntuar |
| LD-12 | Textiles Riobamba | Manufactura | LinkedIn Ads | Sí | 2 | 60% | Sí | Por puntuar |
| LD-13 | Clínica Veterinaria Pet | Servicios | Instagram DM | No | 3 | 70% | No | Por puntuar |
| LD-14 | Editorial Académica | Educación | Webinar técnico | Sí | 1 | 45% | Sí | Por puntuar |
| LD-15 | Ferretería Industrial Manta | Comercio | Demo solicitada | Sí | 2 | 75% | Sí | Por puntuar |

Su misión durante las semanas 5 y 6 consiste en definir un sistema transparente de puntos (incluyendo criterios de suma y resta), calcular automáticamente la columna *Score_Calculado*, establecer el orden de atención y sustentar las decisiones humanas sobre los casos ambiguos.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Definición explícita de la regla de puntuación (semana 5):** Documente en su matriz qué variables son demográficas o de perfil (*Cargo_Decisor*, *Segmento*) y cuáles son conductuales (*Interacciones_14d*, *Apertura_Correos*, *Fuente_CRM*, *Necesidad_Confirmada*). Incluya al menos un criterio explícito de **resta o penalización** (por ejemplo, restar puntos cuando *Interacciones_14d* es igual a cero o cuando no existe necesidad confirmada ni cargo decisor) y defina los umbrales que separan prospectos en nutrición (MQL) de prospectos listos para ventas (SQL).
2. **Cálculo automatizado en hoja de cálculo:** Traslade los 15 registros simulados (del LD-01 al LD-15) y programe la columna *Score_Calculado* utilizando fórmulas reales (como SI, Y, O o suma ponderada de celdas), nunca valores digitados manualmente. Agregue una columna adicional de *Clasificacion_Comercial* que muestre automáticamente el nivel asignado y ordene la lista de mayor a menor puntaje.
3. **Comprobación aritmética y control de interpretación (semana 6):** Verifique manualmente dos filas (una de puntaje alto y una de puntaje bajo) para confirmar que la fórmula no contiene errores. Deje constancia escrita de que los puntajes obtenidos establecen prioridad operativa y no expresan probabilidad estadística de compra.
4. **Análisis de falso positivo y falso negativo:** Compare la tabla ordenada e identifique al menos **un posible falso positivo** (por ejemplo, LD-13 con 3 interacciones y 70 % de apertura pero sin necesidad confirmada ni cargo decisor) y **un posible falso negativo** (por ejemplo, LD-09 que sí tiene necesidad confirmada captada en feria digital pero cero interacciones recientes y no ocupa cargo decisor, o LD-04 que ya confirmó necesidad por mensajería directa). Justifique qué acción humana debe tomar el asesor en ambos casos en lugar de seguir ciegamente el puntaje.
5. **Criterio ético y uso eficiente de recursos:** Explique cómo la priorización de los primeros puestos optimiza el tiempo del equipo comercial (gestión sostenible de recursos) sin discriminar ni descartar definitivamente a cuentas legítimas sin una breve verificación cualitativa.


[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 3](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Caso resuelto de integración: Puntuación y entrega de prospectos bajo reglas visibles

**Ejemplo simulado.** La política otorga veinte puntos por necesidad confirmada y quince por plazo compatible. Un contacto inválido resta veinticinco. La entrega a cierre requiere además un medio utilizable y un registro de la necesidad. Esta condición indispensable no se compensa por sumar otras señales.

| Prospecto | Necesidad | Plazo | Contacto | Puntos | Decision del ejemplo |
| --- | --- | --- | --- | ---: | --- |
| A | Confirmada | Compatible | Válido | 35 | Revisar entrega con contexto completo. |
| B | Confirmada | Compatible | Inválido | 10 | Corregir contacto; no entregar como listo. |
| C | Pendiente | Compatible | Válido | 15 | Continuar diagnóstico de necesidad. |
| D | Confirmada | Pendiente | Válido | 20 | Aclarar plazo antes de afirmar compatibilidad. |

Los valores pendientes no reciben automáticamente castigo ni premio. B tiene evidencia de encaje y un bloqueo operativo; C tiene acceso y falta de información. La misma acción de seguimiento no necesariamente sirve a ambos.

Para cada entrega se conserva qué dijo la persona, qué se comprobó y cuál es el siguiente paso. El equipo de cierre puede devolver un registro con motivo específico y esa información permite revisar criterios. Un umbral que produce muchas devoluciones quizá no representa adecuadamente lo que necesita la siguiente etapa.

**Control de interpretación.** Treinta y cinco puntos no significan 35 % de probabilidad de compra. Son una suma bajo una política del ejercicio. Convertirlos en probabilidad exigiría otro modelo y evaluación. La puntuación ayuda a ordenar revisión y no sustituye conversación ni autoriza a inventar presupuesto o capacidad de decisión para completar la ficha.

### Esquema de aplicación


![Señales de encaje, interés e inactividad. Perfil → Conducta → Puntuación → Revisión. Una cola de prospectos con prioridad explicable](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 03/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Señales de encaje, interés e inactividad | Perfil → Conducta → Puntuación → Revisión | Una cola de prospectos con prioridad explicable |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Inteligencia artificial, lead scoring y comportamiento del cliente». Muestra a la izquierda la información de partida (señales de encaje, interés e inactividad), en el centro los pasos «Perfil → Conducta → Puntuación → Revisión» y a la derecha el resultado (una cola de prospectos con prioridad explicable). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Qué error podría producir medir el interés solo con aperturas de correo?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Una persona abre varios mensajes y otra pide una cotización. Un primer modelo da más puntaje a la primera por repetir aperturas.

Revisa si esas aperturas representan señales distintas, examina ponderaciones y contrasta ambas oportunidades con un criterio de ventas.

Una calibración adecuada explica por qué cada evidencia modifica la prioridad. Para ajustar el umbral conviene revisar quienes entran por error y quienes quedan fuera pese a encajar.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 3 (100 % asincrónico):** Lectura del capítulo 12 de Prior, Buttle y Maklan (2024) en la semana 5 sobre puntuación y priorización de oportunidades, combinada en la semana 6 con la resolución de un **cuestionario aplicado de puntuación de prospectos (*lead scoring*)**, entregando un solo producto en Moodle al cierre de la semana 6.
2. **Trabajo Práctico-Experimental de la Unidad 3 (100 % asincrónico):** Taller práctico en hoja de cálculo o módulo CRM para definir la fórmula de ponderación, calcular el puntaje exacto de **15 prospectos simulados**, clasificarlos en niveles de cualificación comercial y documentar un falso positivo, un falso negativo y la decisión humana recomendada. Los 15 registros y pasos figuran en la Práctica 3 de la Guía de Prácticas y se entregan al cierre de la semana 6.

**Evidencia del práctico según la guía de prácticas.** Un único expediente en Moodle identificado como Apellido_Nombre_Unidad3_Practica3 (libro de hoja de cálculo en formato editable acompañado del informe interpretativo en formato de documento portátil (PDF) o dentro de una pestaña bien estructurada del mismo libro, según indique su docente), que contenga:

- Tabla de reglas de puntuación demográfica y conductual (con suma, resta y umbrales entre MQL y SQL).
- Matriz completa de los 15 prospectos simulados (LD-01 al LD-15) con fórmulas auditables en *Score_Calculado*, clasificación automática y orden de prioridad.
- Análisis argumentado de un falso positivo, un falso negativo, un ejemplo de control de interpretación del puntaje y recomendaciones humanas de seguimiento.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 3: Cálculo y asignación de lead scoring para 15 prospectos simulados](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Las ponderaciones ayudan a priorizar cuando son transparentes, se pueden reproducir y se revisan ante casos dudosos.

#### Mensaje de reflexión

¿Qué error podría producir medir el interés solo con aperturas de correo?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Prior, D. D., Buttle, F., & Maklan, S. (2024). *Customer relationship management: Concepts, applications and technologies* (5th ed.). Routledge. Lectura prevista: Cap. 12
- Arango Aramburu, J. E., Tito Huamaní, P. L., & Reátegui Paredes, V. R. (2022). *Gestión de relaciones con clientes (CRM) y lealtad actitudinal*. Atena Editora. Lectura prevista: Capítulos 3 y 4

<a id="unidad-4"></a>

## Unidad 4: Flujos automatizados de comunicación, decisión y fidelización

![CRM y Seguimiento de clientes II · Unidad 4. Preferencia de contacto. Secuencia posventa. Correo. Mensajería. Respuesta y retención. Resultado: Una secuencia con salidas y métricas definidas](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 04/01_Apertura.svg>)

### Prompt para la imagen de introducción

Genera una ilustración editorial didáctica para estudiantes de Ventas Digitales, en formato horizontal 16:9. Usa fondo claro, acentos en azul y turquesa, iconos sencillos y alto contraste. Deja espacio libre en la parte superior para añadir el título durante la maquetación. Muestra una secuencia de bienvenida, contenido útil y seguimiento posventa en dos carriles, correo y mensajería. Incluye una salida visual de desuscripción, una pausa entre contactos y un punto de traspaso a una persona. Agrega un panel pequeño que distingue apertura, respuesta, conversión, bajas y permanencia. Usa pantallas genéricas, datos ficticios y etiquetas breves en español solo cuando ayuden a entender la escena. Evita logotipos y marcas de agua.

### Introducción

Conseguir un nuevo cliente cuesta mucho más esfuerzo comercial que conservar y hacer crecer a quienes ya confiaron en la empresa. Las **secuencias automatizadas de nutrición (*nurturing* o goteo comercial) y fidelización** acompañan al cliente después del primer contacto o compra mediante mensajes oportunos y útiles adaptados a su etapa: una **secuencia de bienvenida** confirma qué esperar y enseña a aprovechar el producto o servicio; una **secuencia postventa** verifica satisfacción real y ofrece soporte antes de intentar vender de nuevo; y una **secuencia de reactivación** recuerda valor a clientes que llevan un periodo sin interactuar, siempre con un tono respetuoso y sin insistencia invasiva.

El caso de la unidad guía este recorrido: **Bienvenida → Nutrición → Posventa → Medición**.

### Resultados de aprendizaje

El estudiante diseña un flujo automatizado de nutrición y retención de clientes integrando correo y mensajería con indicadores de efectividad.

### Mapa de contenidos de la unidad

| Tema | Subtemas |
| --- | --- |
| 1. Diseño de secuencias de nutrición (Nurturing) y fidelización | Secuencias de bienvenida, reactivación y postventa<br>integración de canales de mensajería<br>KPIs de retención. |

### Caso inicial

Cerrando el proyecto de la empresa ficticia *AndinaSoluciones Comerciales*, el gerente comercial observa que los clientes corporativos que realizan una primera compra rara vez vuelven a adquirir insumos en el trimestre siguiente, mientras algunos antiguos usuarios se dan de baja por recibir recordatorios repetitivos incluso después de haber confirmado su pedido. Usted deberá diseñar el mapa multicanal de bienvenida, postventa y reactivación moderada con métricas claras de retención.

### Tema 1: Diseño de secuencias de nutrición (Nurturing) y fidelización

#### 1.1. Secuencias de bienvenida, reactivación y postventa

**Desarrollo técnico y aplicación.** Bienvenida, reactivación y posventa responden a estados diferentes y no comparten necesariamente frecuencia ni propósito. El contenido reconoce contexto y se detiene cuando deja de ser pertinente. Una reactivación no se justifica solo por inactividad: examine condiciones del canal y necesidad. Registre respuesta y resolución además de cantidad de mensajes preparados.

Diseña la secuencia según la etapa. Bienvenida presenta el siguiente paso, nutrición aporta información útil, reactivación valora interés y posventa verifica la experiencia. Define salidas cuando se cumpla el objetivo o se solicite la baja.

**Fundamento y alcance.** Cada etapa de fidelización busca una acción distinta. La secuencia define qué evento la inicia, qué contenido aporta y cuándo debe detenerse o pasar a otra etapa.

**Caso aplicado.** Una compra ya finalizada entra en seguimiento y el cliente solicita baja.

**Resolución.** Detén la secuencia promocional y documenta qué comunicaciones se permiten según el caso.

**Error frecuente y cómo detectarlo.** Una baja registrada en un solo canal puede no reflejarse en el resto del historial.

**Comprueba tu comprensión.** ¿Cuándo deja de ser pertinente la secuencia?

**Respuesta comentada.** Cuando alcanza su fin, existe baja o corresponde atención humana.

![Bienvenida. Explica cómo empezar y cuál es el próximo paso. Reactivación. Comprueba interés y pertinencia antes de contactar. Posventa. Resuelve dudas y deriva a una persona si hace falta. Cada secuencia necesita una condición para detenerse.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 04/02_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «Secuencias de bienvenida, reactivación y postventa». Para el primer panel usa esta situación. Una compra ya finalizada entra en seguimiento y el cliente solicita baja. En el segundo, representa esta acción. Detén la secuencia promocional y documenta qué comunicaciones se permiten según el caso. En el último, incorpora esta comprobación. Cuando alcanza su fin, existe baja o corresponde atención humana. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

#### 1.2. integración de canales de mensajería

**Desarrollo técnico y aplicación.** Integrar canales conserva identidad, estado y contexto con acceso apropiado. El mismo cliente puede consultar en dos medios sin generar dos oportunidades. Establezca una regla de vinculación y revise conflictos. Unificar no significa copiar toda información en cada canal, sino mantener lo necesario para continuar respetando finalidad y compromisos sin exposición innecesaria.

Coordina correo y mensajería con un historial compartido. Ajusta frecuencia, evita repetir mensajes y establece cuándo debe intervenir un asesor. Respeta la preferencia de canal registrada.

**Fundamento y alcance.** Coordinar canales requiere una vista compartida del contacto y sus preferencias. La derivación a una persona conviene cuando una consulta exige criterio o caso por caso.

**Caso aplicado.** Correo y mensajería contienen respuestas a la misma duda.

**Resolución.** Conserva la conversación en un registro común y deriva la excepción a una persona.

**Error frecuente y cómo detectarlo.** Repetir el mismo mensaje en ambos canales puede saturar al contacto.

**Comprueba tu comprensión.** ¿Qué controla que se respete la frecuencia?

**Respuesta comentada.** El historial compartido y sus reglas de exclusión por canal.

#### 1.3. KPIs de retención.

**Desarrollo técnico y aplicación.** La retención se calcula sobre una base inicial y un criterio de continuidad. Con cien clientes iniciales, ochenta retenidos y veinte nuevos, la base final puede seguir en cien aunque retención sea 80 %. Separar incorporación y permanencia permite interpretar pérdida. Mantenga periodo y definición y no confunda una compra adicional con retención de toda la cohorte.

Apertura, respuesta, conversión, bajas y permanencia responden a preguntas diferentes. Define el denominador y el periodo de cada indicador para saber qué cambiar en el flujo.

**Fundamento y alcance.** Los indicadores miden participación, respuesta, conversión o permanencia. La comparación requiere una base coherente, como entregas válidas, contactos elegibles o cuentas activas del periodo.

**Caso aplicado.** Ochenta contactos reciben un correo y responden ocho.

**Resolución.** Reporta 10 % sobre la base definida y compara con la tasa de permanencia por separado.

**Error frecuente y cómo detectarlo.** Abrir o responder un mensaje no equivale a retención.

**Comprueba tu comprensión.** ¿Cómo se calcula 10 % de respuesta?

**Respuesta comentada.** Ocho respuestas sobre ochenta contactos que recibieron el mensaje.

![Respuesta. Ocho respuestas de 80 contactos equivalen a 10 %. Retención. Revisa quiénes siguen activos dentro del grupo elegible. Comparación. Declara base y periodo para cada indicador. Abrir, responder y permanecer son resultados distintos.](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 04/03_Infografia.svg>)

**Prompt para la infografía del subtema.** Diseña una infografía didáctica en español, de fondo claro y alto contraste. Titúlala «KPIs de retención». Para el primer panel usa esta situación. Ochenta contactos reciben un correo y responden ocho. En el segundo, representa esta acción. Reporta 10 % sobre la base definida y compara con la tasa de permanencia por separado. En el último, incorpora esta comprobación. Ocho respuestas sobre ochenta contactos que recibieron el mensaje. Da prioridad a la secuencia visual, utiliza rótulos breves y conserva las cifras que figuren en el ejemplo.

### Criterios de aplicación

Para que una campaña multicanal (combinando correo electrónico y mensajería instantánea comercial) sea efectiva y ética, debe incorporar dos garantías innegociables: una **opción clara y directa de cancelación de suscripción** en cumplimiento de la protección de datos y privacidad, y una **condición de salida verificada** que detenga la secuencia apenas el cliente realice la acción esperada o resuelva su solicitud. Asimismo, al definir **indicadores clave de desempeño (KPI)** de retención, cada métrica debe especificar su fórmula, unidad de medida, periodo y fuente de datos, recordando que una alta tasa de apertura de correos no demuestra por sí sola satisfacción ni garantiza recompra.

### Ejemplo aplicado y resuelto

**Situación simulada.** Tras una compra, el correo envía la bienvenida y la mensajería responde a una consulta de entrega. El flujo suspende envíos adicionales si se pide la baja o si un asesor toma el caso. Al final del periodo, calcula respuestas sobre contactos elegibles que recibieron el mensaje.

| Elemento | Qué se examina | Resultado o criterio |
| --- | --- | --- |
| Bienvenida | Correo con información inicial | Apertura |
| Atención | Mensajería para dudas de entrega | Respuesta |
| Salida | Baja o traspaso humano | Detén la secuencia automática |

**Ejemplo complementario de la guía didáctica.**

Una tienda digital configura una secuencia de tres mensajes de recuperación (día 1 por correo, día 4 por mensajería y día 7 con encuesta breve) para clientes que dejaron pendiente la renovación de su suscripción. Sin embargo, un cliente renueva el día 2 tras recibir el primer correo y aun así recibe el día 4 un mensaje reclamando que *"no ha completado su renovación"*.
- *Falla detectada:* El flujo carece de una **condición de salida inmediata** ligada al cambio de estado *"Renovación pagada"*.
- *Ajuste correcto:* Configurar una regla de salida automática que verifique el estado antes de cada paso y retire al contacto en tiempo real apenas se confirme el pago, transfiriéndolo a la secuencia de agradecimiento y bienvenida del nuevo periodo, manteniendo un máximo de dos impactos semanales para respetar la tranquilidad del usuario.

**Advertencia y error frecuente.** Un flujo debe conservar la solicitud de baja en todos los canales pertinentes. Comprueba que los mensajes de reactivación respeten esa salida.

### Profundización técnica de la unidad

#### Fidelización medida por cohortes y condiciones de comunicación

Las secuencias de bienvenida, reactivación y posventa responden a estados diferentes. El contenido debe reconocer la interacción previa y detenerse cuando deja de ser pertinente. Integrar canales necesita una identidad coherente y condiciones de acceso, evitando duplicar el mismo mensaje sin control.

**Ejemplo resuelto.** Una cohorte inicial tiene cien clientes; ochenta permanecen al cierre del periodo y se incorporan veinte nuevos. La retención de la cohorte es 80 %, aunque la base total siga en cien. Usar únicamente el total ocultaría las veinte salidas. Debe aclararse qué significa permanecer activo en el caso.

La decisión de reactivar considera motivo de inactividad, canal y pertinencia del contacto. Un mensaje no equivale a retención lograda. Registre respuestas, incidencias y continuidad real. La propuesta de expansión se apoya en necesidad identificada y no solo en que el sistema permita automatizarla. **Reflexión:** ¿qué distingue una venta adicional de una mejora demostrada en la relación con el cliente?

#### Datos y condiciones para estudiar el caso en detalle

Cerrando el caso ficticio de *AndinaSoluciones Comerciales* (escenario simulado exclusivamente con fines formativos), el área de fidelización enfrenta dos retos urgentes: muchos clientes nuevos no reciben orientación tras su primera compra y no recompran al trimestre siguiente, mientras otros usuarios que ya resolvieron su reclamo o pagaron su renovación siguen recibiendo mensajes de recuperación porque el sistema no verifica la condición de salida. Además, varios contactos se dieron de baja por recibir mensajes diarios entre correo y mensajería sin un enlace claro para cancelar su suscripción. Usted deberá diseñar el mapa maestro multicanal de fidelización para las semanas 7 y 8 garantizando coordinación entre canales, salida automática ante resolución o recompra, respeto a la tranquilidad del cliente e indicadores claros para medir retención.

#### Desarrollo del procedimiento y controles del caso

El siguiente recorrido desarrolla la misma práctica de esta unidad. Se estudia junto con sus datos y controles; las consignas y los criterios de entrega se conservan en el apartado de actividades y en la guía enlazada.

1. **Estructura del mapa multicanal de fidelización (semana 7):** Diseñe un mapa visual completo que integre **correo electrónico** y **mensajería comercial** a lo largo de tres tramos conectados: secuencia de bienvenida, seguimiento postventa con encuesta breve y secuencia de reactivación para clientes inactivos. Indique con claridad el intervalo de espera entre impactos para asegurar frecuencias moderadas que eviten el agobio del cliente.
2. **Incorporación de garantías éticas y condiciones de salida:** Integre explícitamente en cada flujo dos controles obligatorios: primero, una **opción visible y directa de desuscripción** o gestión de preferencias en cumplimiento de la protección de datos y privacidad; y segundo, **condiciones de salida inmediata** (por ejemplo, si el cliente confirma recompra, responde que resolvió su necesidad o solicita atención humana, sale de inmediato de la secuencia de recuperación y pasa a atención personalizada o cierre).
3. **Definición técnica de indicadores clave de desempeño (KPI) de retención (semana 8):** Elabore una tabla con al menos cuatro indicadores clave de desempeño (KPI) de fidelización (por ejemplo: tasa de retención trimestral, tasa de recompra, tasa de respuesta útil en mensajería y tasa de cancelación de suscripción o baja). Para cada indicador detalle: propósito, fórmula matemática exacta, unidad, periodo de medición y fuente de registro en el sistema CRM, evitando confundir la apertura de un correo con satisfacción real.
4. **Prueba de recorrido con tres perfiles simulados:** Trace manualmente o dentro del entorno CRM de práctica el camino exacto que seguirían tres clientes ficticios: un cliente satisfecho que recompra el día 10 (debe salir de reactivación), un cliente que ya resolvió su incidente en postventa (no debe recibir mensajes de recuperación) y un cliente que pulsa el enlace de cancelación de suscripción (debe quedar bloqueado para campañas comerciales de inmediato).
5. **Traspaso a atención humana y coherencia integral:** Defina en qué momento exacto la automatización se detiene y transfiere el caso a un asesor humano (por ejemplo, ante calificación baja en postventa o respuesta negativa en mensajería) y vincule este sistema final con la preparación de su defensa integral para el examen final.
6. **Verificación de calidad e integración única en Moodle:** Compruebe la legibilidad del diagrama y sus textos alternativos descriptivos, verifique citas y referencias bajo normas de citación y referencias de la Asociación Americana de Psicología (séptima edición) y suba el paquete completo en Moodle en un solo envío.

[Fuente del caso y del procedimiento: Guía de Prácticas, práctica 4](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md). Las explicaciones y los ejemplos resueltos de esta profundización son desarrollo didáctico de los contenidos de la unidad; sus cifras de ejemplo no sustituyen las del caso de la guía.

### Esquema de aplicación


![Preferencias de contacto e historial. Bienvenida → Nutrición → Posventa → Medición. Una secuencia con salidas y métricas definidas](<../03_Recursos_Visuales/12_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II/Unidad 04/04_Esquema_de_aplicacion.svg>)


| Punto de partida | Secuencia | Producto o decisión |
| --- | --- | --- |
| Preferencias de contacto e historial | Bienvenida → Nutrición → Posventa → Medición | Una secuencia con salidas y métricas definidas |

**Prompt para una infografía.** Diseña una infografía horizontal para estudiantes de Ventas Digitales. Usa como título «Flujos automatizados de comunicación, decisión y fidelización». Muestra a la izquierda la información de partida (preferencias de contacto e historial), en el centro los pasos «Bienvenida → Nutrición → Posventa → Medición» y a la derecha el resultado (una secuencia con salidas y métricas definidas). Usa flechas visibles, fondo blanco y etiquetas cortas. Coloca al pie esta pregunta de reflexión: «¿Qué métrica usarías para comprobar si la coordinación entre canales evita saturar al cliente?». Usa los conceptos indicados y evita añadir cifras.

### Variante del caso resuelta

Un cliente recibe un recordatorio de reactivación mientras conversa por mensajería con un asesor sobre un reclamo.

Coordina los canales con un identificador y pausa el flujo al reconocer el traspaso humano. Comprueba qué pasa al registrar una solicitud de baja.

Evalúa respuesta, permanencia y salidas por separado. Un aumento de interacciones puede reflejar una incidencia abierta; revisa su significado antes de interpretarlo como fidelización.

### Actividades de aprendizaje

1. **Trabajo Autónomo de la Unidad 4 (100 % asincrónico):** Lectura analítica del capítulo 5 de Fonseca Romero y colaboradores (2026) durante la semana 7, articulada en la semana 8 con la elaboración de un **reporte final de retención de clientes** que sustente la estrategia y métricas propuestas, entregado como producto único en Moodle al cierre de la semana 8.
2. **Trabajo Práctico-Experimental de la Unidad 4 (100 % asincrónico):** Proyecto final orientado a diseñar el **mapa completo de automatización de fidelización multicanal** (integrando correo electrónico, mensajería comercial, condiciones de salida, enlace de desuscripción e indicadores clave de desempeño), acompañado de la prueba de recorrido con perfiles simulados y la preparación del sistema integral para su defensa en la evaluación final. El procedimiento completo figura en la Práctica 4 de la Guía de Prácticas y se entrega al cierre de la semana 8.

**Evidencia del práctico según la guía de prácticas.** Un único expediente en Moodle identificado como Apellido_Nombre_Unidad4_Practica4 (documento editable o en formato de documento portátil PDF, pudiendo acompañar el archivo del diagrama o, si lo prefiere como recurso accesible complementario, una breve demostración explicativa grabada dentro del mismo envío), que integre:

- Mapa visual completo de automatización multicanal (bienvenida, postventa y reactivación integrando correo y mensajería) con intervalos moderados, enlace de desuscripción y reglas de traspaso a atención humana.
- Tabla de trazado comprobando el recorrido de los tres perfiles simulados, incluida la salida verificada del cliente que ya resolvió su necesidad.
- Ficha técnica de los cuatro indicadores clave de desempeño (KPI) de retención con fórmulas, fuentes y criterios de interpretación responsable.

[Procedimiento y criterios de revisión en la Guía de prácticas V1, práctica 4: Diseño de mapa de automatización de fidelización y métricas](../../04_Guias_Practicas_V1/GP_VENDIG-P3-16_CRM_y_Seguimiento_de_clientes_II_V1.md)

### Cierre de la unidad

#### Síntesis de la unidad

Una comunicación coordinada ayuda a reconocer cuándo enviar, pausar o derivar según el objetivo y las preferencias del cliente.

#### Mensaje de reflexión

¿Qué métrica usarías para comprobar si la coordinación entre canales evita saturar al cliente?

### Referencias bibliográficas

Lecturas de profundización indicadas en el PEA para la unidad.

- Fonseca Romero, G. N., Armijos Arcos, F. M., Urgilés Rodríguez, B. E., & Márquez Sañay, F. R. (2026). *CRM estratégico con insumos multivariantes: Claves para fidelizar clientes*. Religación Press. Lectura prevista: Cap. 5
- Paredes Bermeo, E. E. (2024). *Técnicas efectivas aplicadas al proceso de ventas*. Editorial Instituto Tecnológico Superior Ibarra. Lectura prevista: Cap. 5
- Arango Aramburu, J. E., Tito Huamaní, P. L., & Reátegui Paredes, V. R. (2022). *Gestión de relaciones con clientes (CRM) y lealtad actitudinal*. Atena Editora. Lectura prevista: Capítulos 3 y 4
