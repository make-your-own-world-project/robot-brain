> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Todos los idiomas](../README.md)

# Fallos observados en los servicios de pago de modelos lingüísticos y las salvaguardias a las que condujeron

![Los fallos registrados se convirtieron en pruebas y salvaguardas para trabajos posteriores.](../../illustrations/failures-became-blueprint.png)

## Estas fueron las opciones pagas más sólidas disponibles

Este proyecto utilizó servicios pagos de modelos de lenguaje en línea para investigación, codificación, redacción y revisión. Las cuentas incluían los modelos generales más sólidos que ofrecían esos servicios en ese momento. La elección de una opción paga más capaz no evitó las fallas que se detallan a continuación.

Cada ejemplo proviene de un registro de proyecto fechado. Las tablas describen lo que hizo un modelo pago, qué sucedió después y qué salvaguarda se creó fuera del modelo. Se trata de fallos observados en servicios comerciales, no fallos causados ​​porRobot Brain. La columna de la derecha describe cómo responde este proyecto.

Los registros no adivinan el motivo de un proveedor ni afirman conocer una causa técnica no revelada. Los nombres de los proveedores se omiten porque las salvaguardas responden a comportamientos repetidos y no a una sola empresa.

## Lo que cuestan los fracasos

El costo no se limitó a una respuesta incorrecta.

- **Se perdió tiempo.** El trabajo descrito como terminado tuvo que ser inspeccionado, explicado nuevamente, reparado y probado por la persona. Algunas fallas consumieron horas.
- **Se perdió la asignación de uso pagada, a veces denominada cuota.** Los reintentos, el contexto repetido, los borradores de reemplazo y las correcciones utilizaron la misma asignación limitada como trabajo útil. En estas sesiones grabadas, no se devolvió ninguna cuota automática para la producción inutilizable ni para los intercambios correctivos.
- **El servicio se pagó de cualquier manera.** El cargo de suscripción o uso se mantuvo mientras la persona también absorbía el tiempo y el esfuerzo necesarios para encontrar y reparar la falla.
- **Las cosas que funcionaban estaban rotas.** Las ediciones incompletas dejaron un servicio en vivo que no se pudo ejecutar. Se realizaron cambios en la copia incorrecta de una configuración. La producción se alejó de su ubicación requerida en lugar de reparar el acceso.
- **El registro histórico se puso en riesgo.** El texto generado se mezcló con material humano y los registros se cambiaron o eliminaron antes de que la persona aprobara ese cambio.
- **La atención se consumía sin permiso.** Las respuestas importantes quedaban enterradas dentro de explicaciones repetidas, lo que obligaba a la persona a leer todo para recuperar la pequeña parte que importaba.

Es por eso que aquí las reglas importantes no se encuentran solo en un aviso.Robot Brain comprueba lo que realmente sucedió y puede rechazar una contribución incluso cuando el modelo dice que tuvo éxito.

## Continuidad y fallos en el conocimiento.

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Suena continuo después de perder la historia. | Un servicio acortó la conversación anterior para adaptarla a su límite de trabajo. Mantuvo algunas conclusiones pero perdió fuentes, correcciones, alternativas rechazadas, orden de eventos e intención del usuario mientras seguía sonando con fluidez. | Mantenga la conversación completa en orden. Guarde la versión abreviada por separado y registre lo que incluyó, lo que omitió y lo que pudo haber perdido. |
| Una nueva respuesta que reemplaza la historia registrada | Una respuesta de modelo de lenguaje más nuevo podría parecer que reemplaza todo lo anterior, aunque provenga de información, reglas y elecciones diferentes sobre el mundo. | Guarda cada hallazgo con su tiempo. Nunca permita que la respuesta más reciente sobrescriba los resultados previamente aceptados, rechazados o inciertos. |
| El aprendizaje mediante modelos de lenguaje destruyó el camino de regreso a la fuente | El modelo de lenguaje mantuvo patrones útiles al tiempo que los separaba del creador, el propósito, la audiencia, la evidencia, el desacuerdo y la historia posterior de la fuente. | Mantenga las fuentes sin cambios y sus conexiones conocidas fuera de cada modelo de lenguaje. Trate el conocimiento del modelo de lenguaje no respaldado como una sugerencia a menos que evidencia separada lo reconecte con una fuente. |
| Pérdida de las circunstancias detrás de lo que aprendió el modelo de lenguaje | El modelo de lenguaje siguió siendo útil mientras su respuesta no pudiera revelar todas las personas, fuentes, propósitos, desacuerdos, permisos y culturas que lo moldearon. | Mantenga las circunstancias conocidas y el crédito con fuentes guardadas fuera del modelo de idioma. Trate el conocimiento aprendido sin fundamento como una sugerencia de un modelo de lenguaje, no como un hecho vinculado a una fuente. |
| Sesgo oculto de lo seleccionado | Lo que el modelo de lenguaje podía reconocer reflejaba los idiomas, fuentes, archivos, etiquetas, revisores humanos y objetivos utilizados para construirlo. Su respuesta no reveló todas esas influencias. | Registre los límites conocidos del modelo de lenguaje y lo que se sabe sobre el material del que aprendió. Compare varias herramientas limitadas y no trate una respuesta fluida como una vista completa. |
| La historia compartida se reescribe silenciosamente | Varios trabajadores que editan una historia de apariencia principal podrían perder o combinar decisiones incompatibles. | Agregue un nuevo historial de fuentes sin sobrescribir las entradas anteriores. Cree vistas actuales a partir de ese historial sin tener que volver a escribir el registro del evento. |
| Diferentes épocas y estados tratados como iguales | Las declaraciones actuales, históricas, experimentales, probadas por separado y reemplazadas se presentaron como si tuvieran la misma categoría. | Guarde el tiempo y el estado actual de cada reclamo importante y parte del sistema. |
| Quitar una pieza sin comprobar quién la usa | Una pieza no utilizada en el proceso actual fue tratada como obsoleta sin comprobar trabajos posteriores que dependían de ella. | Registre el trabajo de cada pieza, los usuarios, el estado actual y los reemplazos. Verifique esos usuarios antes de eliminarlo. |
| Mezclar texto generado en el registro de una persona | La explicación escrita basada en un modelo de lenguaje se guardó junto al material humano en una forma que luego podría confundirse con las propias palabras o creencias de la persona. | Mantenga claramente separados el material humano palabra por palabra, las transcripciones y la interpretación generada por modelos de lenguaje. Nunca permita que el texto generado se convierta silenciosamente en parte del registro humano. |
| Eliminar el historial durante la limpieza | Los registros anteriores se cambiaron o eliminaron porque un modelo de lenguaje los consideró incorrectos o desordenados. Eso destruyó la evidencia necesaria para entender qué pasó y por qué cambió. | Preservar el registro histórico. Agregue una corrección o un hallazgo posterior en lugar de reescribir silenciosamente el pasado. |

## Fallos de instrucción y alcance

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Reglas que se pierden durante la tarea. | Un modelo de lenguaje podría leer, reformular y luego violar una regla en la misma tarea. | Convertir reglas cuyo incumplimiento tiene un alto costo en condiciones requeridas y controles que puedan rechazar el trabajo. |
| Las reglas de reclamación se siguieron sin pruebas | La modelo afirmó que se habían seguido instrucciones o documentos cuando el resultado demostró lo contrario. | Exigir evidencia de que se realizó y aprobó la verificación correspondiente. Un modelo de lenguaje que diga que tuvo éxito no es una prueba. |
| Reemplazo de la tarea solicitada | Una solicitud específica fue reemplazada por el encuadre preferido del modelo de lenguaje, lo que obligó al usuario a defender nuevamente el trabajo original. | Preservar los límites solicitados. Rechace un cambio no solicitado en el marco a menos que un conflicto real de seguridad o permiso lo requiera. |
| Hacer trabajo extra sin permiso | Se realizó un trabajo relacionado porque parecía útil, aunque no fue solicitado. | Vincula cada acción a la tarea declarada. Trate cualquier expansión como una nueva decisión. |
| Cambiar el destino solicitado | Cuando la ubicación solicitada era inalcanzable, el resultado se trasladaba a un lugar más fácil en lugar de reparar el acceso. | Preservar el destino elegido. Cambiarlo requiere la decisión del usuario. |
| Pasando de la corrección solicitada | La retroalimentación fue tratada como una dirección para seguir cambiando el trabajo en lugar de una corrección precisa a alcanzar. | Registre el estado final solicitado y verifique el resultado después del cambio. |
| Forzar material nuevo a colocarlo en el lugar equivocado | Se añadió material nuevo a un documento existente sin encajarlo en la estructura, lo que dañó a ambos. | Planifique el resultado completo, rastree los cambios de la adición y cree un documento separado cuando no corresponda. |
| Mover la salida en lugar de arreglar el acceso | Cuando no se pudo acceder a la carpeta solicitada, un asistente trasladó el resultado a un lugar más fácil. Eso dividió los registros de la persona y descartó la presentación, los permisos y los hábitos ya creados en torno a la ubicación original. | Reparar el acceso al lugar elegido. Cambiar el destino sigue siendo decisión de la persona. |

## Fallos de evidencia y finalización

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Declarar la finalización demasiado pronto | La edición o el inicio de una parte se informó como completada antes de que se probara su efecto. | La finalización requiere evidencia del resultado solicitado, no una declaración de estado generada. |
| Aceptar un diagnóstico sin comprobarlo | Se aceptó un mensaje de error sin comprobar de dónde y cuándo procedía ni si describía la tarea actual. | Mantenga las pruebas vinculadas a dónde, cuándo y bajo qué circunstancias se produjeron. |
| Conjeturas plausibles | Se propusieron causas y próximos pasos porque parecían razonables, no porque la evidencia los señalara. | Preservar las incógnitas. Separe lo observado, una posible explicación, la prueba y la causa confirmada. |
| Suponiendo que el cambio más reciente fue correcto | Se supuso que los cambios recientes en la escritura del modelo de lenguaje eran correctos, mientras que otras partes se sospecharon primero. | Consulte el cambio más reciente y las explicaciones competitivas antes de asignar la causa. |
| Tratar el momento como prueba de causa | Se culpó a la parte activa cerca de una falla sin comparar el comportamiento normal u otras condiciones modificadas. | Haz que el problema vuelva a ocurrir. Compare las condiciones normales y modificadas, busque evidencia contraria y rastree la causa. |
| Tratar una pequeña prueba como prueba de un comportamiento en vivo | Se presentó una imitación, un ejemplo preparado o una pequeña prueba como prueba de que todo el sistema funcionaba en el uso normal. | Indique exactamente lo que se probó y no pretenda que el resultado demuestra más. |
| Pruebas con permisos incorrectos | Se aprobó una verificación utilizando el acceso del desarrollador a pesar de que el programa en vivo se ejecutó con permisos diferentes. | Pruebe con la misma cuenta y permisos utilizados por el programa en vivo, o deje el resultado sin probar. |
| Reparar un error antes de grabarlo | Se reparó un error antes de que se revelara, haciendo que el registro pareciera más limpio que el trabajo. | Preservar el fallo y la corrección en orden. No permita que la reparación borre la evidencia. |
| Revisión repetida frente al usuario. | Un resultado se revisaba repetidamente delante del usuario porque la planificación se retrasaba hasta después del primer resultado. | Seleccione el material y planifique todo el resultado antes de solicitar una revisión. Presente un borrador limitado cuando sea posible. |
| Romper un servicio en vivo con una edición incompleta | Un modelo de lenguaje cambió solo una parte de un archivo de trabajo y siguió adelante. El servicio en ejecución no pudo completar su trabajo. | Trate un cambio como inacabado hasta que todo el archivo sea válido y el servicio real complete el trabajo previsto. |
| Cambiar la copia incorrecta de una configuración | Un modelo de lenguaje editó el archivo de configuración principal, reinició el servicio, recibió una respuesta de reinicio exitosa e informó el éxito. El servicio utilizó una copia generada diferente, por lo que la configuración anterior permaneció activa. | Verifique el resultado visible, no solo el mensaje de edición o reinicio. Mantenga una ruta clara desde la configuración principal hasta la copia que realmente utiliza un servicio. |
| Correcciones repetidas que no solucionaron el problema. | Se realizaron cuatro cambios para un problema. Cada uno demostró que se ejecutó algún código, pero ninguno demostró que el problema original había desaparecido. | Defina el resultado que debe cambiar antes de editar. Después de cada cambio, pruebe ese resultado directamente. |
| Comprobando con acceso el servicio en vivo no tenia | Una carpeta funcionó cuando se probó a través de la cuenta de la persona, pero el servicio en vivo usó una cuenta diferente y aún así no pudo acceder a ella. | Ejecute la verificación en las mismas condiciones que el servicio en vivo. |

## Fallos sobre quién puede decir o aprobar qué

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Diferentes trabajos tratados como iguales | Los observadores, escritores, inspectores, personas que pueden detener el trabajo y los aprobadores de liberación fueron tratados de la misma manera porque cada uno tocó el resultado. | Cada parte tiene un trabajo establecido y límites a lo que puede decidir. Un escritor no puede hacer que una afirmación sea cierta. Un observador no puede publicar. |
| Mostrar valores sustitutos como reales | Las pantallas mostraban medidas vacías o sustitutos plausibles para que la instalación pareciera completa. | Muestre un valor medido y de dónde proviene, o indique claramente que no está disponible. |
| Actualizar una página destruyó el lugar del usuario | Una actualización reemplazó una página completa y destruyó el foco, la selección, la posición de desplazamiento o la copia. | Trate la pantalla como un espacio de trabajo humano. Actualice los valores cambiantes sin destruir el lugar del usuario. |
| Mantener contraseñas en texto desprotegido | Las contraseñas y claves de acceso se colocaron en archivos normales en lugar de en un almacenamiento protegido. | Guárdelos en un almacenamiento protegido y verifique cada archivo antes de publicarlo. |
| Informar que un servicio se detuvo mientras seguía ejecutándose | La solicitud de detención regresó exitosamente, pero el proceso continuó funcionando. | Comprobar el proceso y su efecto real tras una solicitud de control. No reportar la solicitud como resultado. |

## Fallos de atención humana

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Rellenar las palabras de una persona | Una breve declaración humana se amplió con material generado hasta que las palabras originales fueron difíciles de encontrar. | Conservar la declaración original como registro principal. La interpretación generada sigue siendo separada y opcional. |
| Escritura circular | La respuesta fue explicada, reformulada, resumida y concluida una vez que se agotó el contenido útil. | Deténgase cuando se complete el resultado solicitado. Eliminar conclusiones repetidas. |
| Enterrando la respuesta | Se colocaron uno o dos datos útiles dentro de pantallas llenas de material que el usuario no solicitó. | Coloque primero la respuesta completa más corta y haga que el material más profundo sea opcional. |
| Gastar atención no ofrecida | La explicación correcta pero innecesaria obligó al lector a dedicar tiempo a decidir que era innecesaria. | Cuente la lectura y la corrección como costos reales. Deje que el lector inicie la profundidad opcional. |
| demasiado énfasis | Casi todos los puntos estaban en negrita, con encabezado o colocados en una tabla, por lo que las advertencias reales ya no destacaban. | Utilice el énfasis sólo para las pocas distinciones que conllevan la carga de decisión o seguridad. |

## Fallos que involucran costos e incentivos de proveedores.

| Fallo observado | Qué pasó | Protección agregada fuera del modelo de lenguaje |
|---|---|---|
| Un modelo de lenguaje grande pago utilizado por defecto | El trabajo se enviaba a través de un modelo pago en línea porque estaba disponible, incluso cuando un simple proceso fijo, un resultado guardado o una herramienta limitada podían hacerlo de manera más confiable. | Mida el valor total y el costo del trabajo. Elija la combinación más pequeña de herramientas cuyo trabajo pueda comprobarse y justificarse. |
| El costo de corrección desapareció de los totales. | Los reintentos, el contexto repetido, la espera y la corrección humana se consideraron gratuitos después de un mal resultado, aunque utilizaron un subsidio pagado y exigieron más tiempo y energía de la persona. | Registrar esperas, reintentos, rechazos, uso repetido del servicio y atención humana como parte del costo real. |
| No se devolvió ninguna cuota por trabajo fallido | La producción inutilizable y los intercambios necesarios para corregirla se computan contra la cuota pagada. La persona no recibió ningún reemplazo automático por el subsidio o el tiempo perdido. | Registre el uso fallido y correctivo por separado. Reutilice el contexto guardado y los resultados rechazados para que no se vuelva a comprar el mismo error. |
| Se descartó el fallo útil. | Una respuesta rechazada desapareció, por lo que el trabajo posterior repitió el mismo error y volvió a pagarlo. | Mantener los resultados rechazados y sus motivos de rechazo fuera del conocimiento aceptado. Reutilice la lección sin aceptar el reclamo sin fundamento. |
| El mismo contexto tuvo que ser proporcionado nuevamente. | Cuando la información anterior desaparecía de la vista de trabajo del modelo de lenguaje, la persona tenía que reconstruir la solicitud y reenviar el historial ya proporcionado en una sesión paga. | Mantenga el contexto duradero fuera del servicio. Cree un paquete limitado para cada trabajo y guarde el trabajo devuelto, la corrección y el rechazo para su uso posterior. |

## Cómo esas fallas del servicio se convirtieron en el diseño de este proyecto

El problema observado no se limitó a un modelo débil. Al mismo asistente temporal se le pedía que actuara como memoria, historiador, planificador, escritor, verificador y juez de su propio trabajo. Incluso los modelos mejor pagados podían tener éxito en una tarea individual perdiendo la historia humana que la conectaba con todo lo demás.

Robot Brain da esos trabajos a partes separadas. El guardián de la fuente preserva el evento. Los lectores locales enfocados examinan las características definidas. El creador de solicitudes recopila pruebas con un propósito. Un modelo puede contribuir con antecedentes o redacción. Los controles independientes y la aprobación humana deciden lo que se acepta.

El historial queda fuera del servicio pago. Un modelo puede ayudar con un trabajo elegido, pero no almacena la vida de la persona ni se convierte en la única forma de utilizar el trabajo que ya se ha realizado.

El modelo local tiene el mismo límite. No se entrena en los registros de la persona. Lee el material seleccionado, devuelve una sugerencia fechada y puede reemplazarse. Las palabras, el tiempo, la experiencia, las decisiones, los fracasos y las correcciones de la persona son la parte valiosa.
