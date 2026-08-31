> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../README.md) | [Todos los idiomas](../README.md)

# Mantenga el registro. Reemplace el modelo.

![Los registros de una persona permanecen en un solo lugar mientras partes de trabajo separadas se encargan de trabajos limitados.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain es un software para preservar la historia y el significado detrás del trabajo humano de larga duración. No es un modelo de lenguaje, un chatbot o un servicio que envía cada pregunta a un modelo.

Los modelos de lenguaje grandes pueden investigar, escribir, explicar y ayudar a resolver problemas difíciles. Los servicios pagos creados a su alrededor siguen siendo espacios de trabajo temporales. Pueden acortar una conversación larga, perder instrucciones anteriores, separar conclusiones de su evidencia y continuar escribiendo como si la historia faltante todavía estuviera presente. Luego, una persona dedica más tiempo y uso pago a reconstruir el contexto que ya se le proporcionó.

Este software cambia dónde vive el valor duradero. Las conversaciones, documentos, decisiones, intentos fallidos, correcciones y preguntas sin respuesta de la persona permanecen en registros que la persona controla. Los programas locales pueden examinar esos registros. Un modelo de lenguaje puede ayudar con un trabajo seleccionado, pero su contribución regresa al registro como un trabajo revisable y fechado. Luego, el modelo se puede reemplazar sin llevarse el historial.

[Lea esta documentación en otro idioma.](../README.md)

## La diferencia en una vista.

| Un servicio modelo de lenguaje comercial | Robot Brain |
|---|---|
| Produce una respuesta a partir del material actualmente en su vista de trabajo. | Mantiene la fuente completa y la historia que la rodea. |
| Puede acortar o perder la conversación anterior a medida que aumenta el trabajo. | Guarda conversaciones fuera de cada modelo para que puedan usarse nuevamente. |
| Combina el conocimiento aprendido de muchas fuentes sin un camino completo de regreso a cada fuente y sus circunstancias. | Mantiene cada fuente conocida, hallazgo posterior, corrección y desacuerdo como un registro separado. |
| Puede escribir, buscar, planificar y juzgar su propia respuesta en un solo intercambio. | Permite guardar, buscar, analizar, escribir, verificar y aprobar partes separadas con autoridad limitada. |
| Controla el modelo, reglas de servicio, límites de uso y cambios de producto. | Deja el registro duradero bajo el control de la persona. |
| Se paga por los intentos fallidos y los intercambios correctivos, así como por el trabajo útil. | Mantiene fallos y correcciones para que no sea necesario volver a comprar sus lecciones. |

Robot Brain Puede llamar a un modelo de idioma local o en línea. Eso no lo convierte en un proxy modelo. Puede preservar, buscar, comparar, organizar y reconstruir trabajos anteriores sin llamar al modelo que participó en la conversación original. Cuando un modelo es útil, la solicitud es un paso en un proceso más amplio que existe independientemente de ese modelo.

## ¿Por qué se construyó esto?

Los modelos remunerados de uso general más potentes disponibles durante el desarrollo eran custodios capaces pero poco fiables de un trabajo prolongado.

Los fallos registrados incluyeron instrucciones perdidas, pruebas faltantes, conexiones inventadas, afirmaciones prematuras de finalización, cambios no deseados y daños a los archivos en funcionamiento. Corregir esas fallas requirió más solicitudes, más pruebas, más subsidios pagados y más tiempo y energía de la persona. Los servicios no devolvieron automáticamente el uso invertido en trabajos inutilizables ni los intercambios necesarios para repararlos.

El problema era mayor que cualquier mala respuesta. Se pedía a un generador de texto temporal que sirviera de memoria, historiador, investigador, escritor, verificador y juez final. Cambiar de modelo no cambió ese arreglo.

Robot Brain se construyó en torno a un arreglo diferente: mantener primero el registro humano, dejar que varias partes reemplazables contribuyan a él y requerir evidencia fuera del modelo generador antes de aceptar un trabajo importante.

## Lo que un modelo entrenado no puede mantener

Un modelo de lenguaje grande aprende patrones de enormes colecciones de trabajo humano. Esos patrones hacen que el modelo sea útil, pero el modelo no es una biblioteca de las obras completas que le dieron forma.

Dentro del modelo, se combina la influencia de libros, artículos, conversaciones, traducciones, comunidades, etiquetas y comentarios humanos. Por lo general, el modelo no puede mostrar qué fuentes dieron forma a una oración en particular. No puede restaurar el propósito, la audiencia, la evidencia, el desacuerdo, la corrección posterior o el punto de vista faltante de cada autor.

Se trata de una pérdida de significado incluso cuando la obra original todavía existe en otro lugar. El modelo conserva cierta utilidad del trabajo al tiempo que descarta el camino confiable de regreso a su entorno humano.

El mismo problema aparece durante el uso normal. Una respuesta final puede sobrevivir después de que se haya acortado la conversación que le dio significado. La conclusión permanece, pero los intentos fallidos, la incertidumbre y las razones detrás de ella desaparecen de la visión operativa del modelo.

Este proyecto no responde a ese problema entrenando otro modelo sobre la vida de una persona. El historial personal sigue siendo legible y rastreable en lugar de combinarse con otro modelo entrenado. Los modelos funcionan con registros seleccionados; no se convierten en registros.

## ¿Qué hace cada parte?

El software en funcionamiento separa los trabajos que un servicio de chat a menudo hace que parezcan una sola actividad:

1. **El administrador de la fuente guarda lo sucedido.** Conserva la conversación, el documento, la imagen u otro material sin reemplazarlo con un resumen.
2. **Las copias con capacidad de búsqueda hacen que la fuente sea más fácil de encontrar.** El texto, las descripciones y los índices copiados apuntan a la fuente sin cambios y se pueden reconstruir.
3. **Los lectores locales enfocados examinan características específicas.** Los métodos separados analizan el lenguaje, las declaraciones, las relaciones, el razonamiento, el tiempo, la experiencia humana y los valores. Cada uno informa sólo sus propios hallazgos y los pasajes detrás de ellos.
4. **El registro histórico mantiene los cambios visibles.** Se agregan nuevos hallazgos, correcciones, desacuerdos, intentos fallidos y preguntas abiertas sin reescribir eventos anteriores.
5. **El generador de solicitudes reúne lo que necesita un trabajo.** Selecciona fuentes y hallazgos relevantes y registra lo que se incluyó o se omitió.
6. **Un modelo de idioma puede aportar ayuda limitada.** Un modelo local puede proporcionar una amplia experiencia. Un modelo en línea puede ayudar con investigaciones o escritos difíciles. Cualquiera de las respuestas sigue siendo una contribución anticuada que puede verificarse, rechazarse o reemplazarse.
7. **Verificaciones separadas comparan el resultado con la solicitud y la evidencia.** El modelo que escribió una respuesta no puede declarar aceptado su propio trabajo.
8. **Una pantalla permite a una persona usar el software.** El incluidoLibreChatfork es una de esas pantallas. Reemplazarlo no reemplaza los registros ni las otras partes funcionales.

Ninguna parte se presenta como un asistente que todo lo sabe. Sus trabajos limitados son los que hacen que cada pieza sea reemplazable.

## Hacer que una conversación completa vuelva a ser útil

Una conversación completa contiene la solicitud de la persona, las respuestas reales del modelo de lenguaje, el trabajo intentado, los fracasos, las correcciones y el punto donde terminó el intercambio. Esos mensajes preservan lo que aportó el modelo original sin necesidad de que ese modelo se explique más tarde.

Los lectores locales enfocados examinan el intercambio guardado desde varios ángulos. Pueden encontrar patrones y relaciones detallados sin depender de un amplio conocimiento del mundo. Sus hallazgos separados permanecen conectados con partes exactas de la conversación.

Es posible que esos hallazgos aún necesiten conocimientos previos ordinarios antes de que formen una explicación clara. Para ese paso limitado, un pequeñoQwenEl modelo se ejecuta localmente a través devLLM. Agrega una descripción general fechada que ayuda a conectar los hallazgos detallados y explicar lo que logró el intercambio.

Qwenno recupera los pensamientos ocultos ni el historial de entrenamiento del modelo en línea. Proporciona un amplio conocimiento previo que no es exclusivo del modelo original. La útil contribución del modelo original ya se conserva en las palabras que produjo.

ElQwenLa descripción general se almacena junto a la fuente y los hallazgos anteriores. Se puede corregir o reemplazar. La conversación original y el análisis local detallado permanecen sin cambios.

## ¿Qué está funcionando ahora?

La implementación actual puede preservar una conversación completa, examinarla a través de métodos locales separados, agregar una lectura de conocimiento general local y reunir cada contribución retenida en un registro que se puede reconstruir más adelante.

También puede preparar una solicitud limitada para un modelo en línea cuando la ayuda externa sea útil. Ese servicio recibe únicamente el material seleccionado. Su respuesta regresa al registro local, donde los controles y la aprobación humana (no el modelo) deciden qué se guarda.

Este es el logro central: el trabajo que alguna vez dependió de una conversación temporal puede seguir siendo útil después de que su pantalla de chat, su modelo y su proveedor desaparezcan.

## Lea la explicación completa

- [Por qué los grandes modelos de lenguaje no pueden preservar la historia completa](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Lo que hace cada parte y lo que ningún modelo controla](02-A-Lasting-Record-Outside-the-Model.md)
- [Mantener la corrección sin borrar el error](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Siga un reclamo hasta la evidencia](04-How-Every-Claim-Can-Be-Checked.md)
- [Construya el documento antes de escribir la prosa.](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Explicar la misma verdad a diferentes lectores.](06-One-Meaning-Different-Readers.md)
- [Mantener el historial privado bajo el control de la persona](07-Privacy-and-Control-Stay-With-People.md)
- [Qué hace la implementación actual](08-What-Works-Today.md)
- [Por qué el diseño se basa en muchos campos](09-How-Research-Strengthens-the-System.md)
- [Ayuda sin entregar registros privados](11-Contribute-Without-Giving-Up-Control.md)
- [Palabras utilizadas en estos documentos.](12-A-Short-Guide-to-Key-Terms.md)
- [Siga una solicitud a través de las partes de trabajo](13-The-Parts-Running-Today.md)
- [Utilice un modelo de lenguaje para el trabajo, no como memoria](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Fallos observados en los servicios de pago de modelos lingüísticos y las salvaguardias a las que condujeron](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lecciones que cambiaron el diseño.](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Notas de uso público, crédito y privacidad](18-Use-Attribution-and-Limits.md)
- [Cómo una conversación completa se convierte en conocimiento duradero](19-What-the-System-Accomplishes.md)
- [¿Qué viene después?](20-Where-the-System-Goes-Next.md)

## Créditos, fuentes y derechos

- [¿Qué ayudó a dar forma a este trabajo?](10-What-Helped-Shape-This-Work.md)
- [Investigación detrás del diseño](14-Sources-Behind-the-Design.md)
- [Fuentes, licencias y comprobaciones de divulgación pública](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Licencia

Los escritos, diagramas e ilustraciones originales del proyecto están disponibles en el sitio web de la organización.[Licencia Creative Commons Atribución 4.0 Internacional](../../LICENSE.md), a menos que un documento establezca términos diferentes. El material creado por otros mantiene sus propios derechos y términos.

## Independencia y privacidad

Este es un proyecto personal independiente desarrollado en tiempo personal, equipos, cuentas y servicios pagos. Ningún empleador participó en él. Mencionar cualquier persona, empleador, institución, proveedor de modelos, grupo de investigación, regla compartida o proyecto externo no implica participación, aprobación, asociación o respaldo.

La divulgación pública excluye registros privados, detalles de identificación, contraseñas, información de conexión privada, información del empleador e instrucciones para acceder a servicios privados. Las descripciones de las fallas del modelo se limitan al comportamiento registrado y su efecto; no afirman causas o motivos no revelados. Los documentos no son asesoramiento profesional ni una promesa de resultados.

![Un camino desde la memoria controlada por el proveedor hacia registros que permanecen con las personas a las que interesan.](../../illustrations/open-door-human-future.png)
