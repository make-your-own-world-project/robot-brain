> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../02-A-Lasting-Record-Outside-the-Model.md) | [Todos los idiomas](../README.md)

# Lo que hace cada parte y lo que ningún modelo controla

![Las fuentes originales respaldan una historia duradera, mientras que las herramientas reemplazables realizan un trabajo limitado.](../../illustrations/core-architecture-layers.png)

Robot Brain es una colección de partes cooperativas construidas alrededor de un disco duradero. No se trata de un gran modelo de lenguaje, ni de un grupo de modelos que pretenden serlo, ni de un servicio de chat con búsqueda adicional.

La distinción es importante porque los problemas que se abordan provienen de pedirle a un servicio de modelo de lenguaje temporal que sirva como memoria, investigador, escritor, verificador y juez al mismo tiempo. Este software separa esos trabajos y mantiene el historial de la persona fuera de cada modelo.

## Guarda el evento antes de interpretarlo.

El guardián de la fuente guarda la conversación, nota, imagen, documento, tarea u otro elemento tal como llegó. También guarda datos que realmente se conocen, como la hora de llegada, la fuente, el creador cuando se establece y el permiso cuando se registra.

Un nombre de archivo, una suposición de un modelo o una interpretación posterior no pueden convertirse silenciosamente en un hecho sobre la fuente. La información que falta sigue faltando.

## Haga que la búsqueda sea útil sin reemplazar la fuente

El software crea copias con capacidad de búsqueda, como texto extraído, descripciones e índices. Estas copias apuntan a la fuente sin cambios. Se podrán reconstruir cuando esté disponible un método mejor.

Esto es diferente a pedirle a un modelo de lenguaje que resuma una pila de archivos y luego tratar el resumen como la memoria. Un resumen es una vista posterior. Nunca reemplaza el material que describe.

## Deje que los lectores locales enfocados hagan hallazgos limitados

Métodos locales separados examinan características definidas de la fuente. Algunos analizan la estructura del lenguaje. Otros identifican declaraciones, posibles relaciones, razonamientos, cambios a lo largo del tiempo u observaciones sobre la experiencia y los valores humanos.

Estos métodos no son pequeños chatbots. Realizan trabajos estrechos contra material ahorrado. Cada hallazgo identifica el pasaje examinado, el método utilizado, la fecha y los límites conocidos. Un método puede encontrar algo, no encontrar nada, negarse a responder o fallar. No puede reescribir el trabajo de otro método.

## Mantener la historia como historia

Se añaden nuevos hallazgos a eventos anteriores. Las correcciones no borran los errores. Una conclusión posterior puede volverse actual mientras que la conclusión anterior permanece visible con la evidencia y las circunstancias que alguna vez la respaldaron.

Esto permite que el trabajo posterior responda no sólo “¿qué se cree ahora?” pero también “¿qué cambió, por qué cambió y cuánto costó el cambio?”

## Reúna pruebas para una solicitud

El generador de solicitudes comienza con el propósito de la respuesta o documento. Identifica lo que el lector necesita, reúne las fuentes y los hallazgos relacionados con esas preguntas y registra lo que se incluyó y lo que se omitió.

Un servicio de chat comercial generalmente le pide al modelo que trabaje con cualquier texto que encaje en la solicitud actual. Aquí, la selección de evidencia es un paso registrado fuera del modelo. El modelo no puede decidir tranquilamente que la historia perdida no importa.

## Utilice modelos como contribuyentes

Un modelo de lenguaje puede ser útil para investigaciones, antecedentes amplios o escritura. Recibe material seleccionado para un trabajo declarado.

La instalación actual también utiliza un pequeño localQwenmodelo para un propósito específico: después de que el análisis local enfocado haya examinado una conversación completa,Qwenagrega conocimientos previos ordinarios que ayudan a conectar los hallazgos separados. No se convierte en memoria, no recupera pensamientos ocultos, ni decide lo que significa el intercambio.

Ya sea local o en línea, una respuesta modelo se guarda como una contribución fechada. Se puede verificar, corregir, rechazar o reemplazar sin cambiar la fuente.

## Verificar el trabajo fuera del escritor.

Verificaciones separadas comparan una respuesta o documento terminado con sus fuentes, cobertura requerida y límites establecidos. Se registra la versión exacta que pasó.

Un modelo de lenguaje no puede hacer realidad su propia afirmación escribiendo con seguridad. Tampoco puede hacer que se acepte su propio trabajo diciendo que siguió las instrucciones.

## Utilice cualquier pantalla adecuada

el incluidoLibreChatfork proporciona una pantalla conversacional para solicitar trabajo y leer resultados. No almacena el registro duradero, no dirige ninguna otra parte ni aprueba respuestas.

LibreChatpuede ser reemplazado por otra pantalla.QwenSe puede sustituir por otro modelo adecuado. Un proveedor en línea se puede cambiar u omitir. El historial fuente y el trabajo aceptado siguen siendo utilizables porque ninguna de esas partes los posee.

## El límite que define el proyecto

Los modelos de lenguaje generan contribuciones temporales a partir del material que se muestran.Robot Brain preserva la fuente, organiza el trabajo en torno a ella, registra los cambios, prepara solicitudes limitadas y verifica lo que regresa.

Por eso este no es otro modelo de lenguaje, un modelo de proxy o un chatbot mejor. Los modelos pueden participar en el trabajo. El trabajo no depende de ningún modelo.
