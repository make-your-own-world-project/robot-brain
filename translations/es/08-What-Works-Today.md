> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../08-What-Works-Today.md) | [Todos los idiomas](../README.md)

# Qué hace la implementación actual

![Las ideas, las pruebas, los fracasos y las habilidades probadas quedan claramente separados.](../../illustrations/evidence-implementation-gates.png)

Robot Brain está ejecutando software para preservar y reconstruir el significado del trabajo grabado. No es una propuesta de chatbot y su implementación actual no es un modelo de lenguaje.

## Capacidades en la implementación actual

Las ejecuciones registradas muestran que el software puede:

- conservar una conversación completa sin reemplazarla con un resumen
- mantener las palabras de la persona separadas de las respuestas modelo y de la interpretación posterior
- Crear hallazgos detallados sobre el lenguaje, el significado, el razonamiento, el tiempo, la experiencia humana y los valores.
- conectar cada hallazgo conservado con la parte de la conversación detrás de él
- Mantener correcciones, desacuerdos, trabajos fallidos y preguntas sin respuesta.
- agregar una descripción general local fechada de conocimiento general sin llamar al modelo original en línea
- reunir las contribuciones retenidas para una reconstrucción solicitada
- registrar lo que fue verificado, rechazado, corregido y aceptado
- reemplazar una pantalla o modelo de idioma participante sin reemplazar el historial guardado

Estas son funciones del software en torno a los modelos. No son habilidades reclamadas paraQwen,LibreChat, o un asistente en línea.

## ¿Qué sucedió en el hito de conversación completa?

La conversación probada se guardó con los mensajes de la persona y las respuestas del modelo en línea en orden.

Luego, los métodos locales enfocados produjeron registros separados sobre el intercambio. Su trabajo abarcó el lenguaje y el significado, el razonamiento, las observaciones psicológicas, las observaciones filosóficas, las relaciones y los cambios a lo largo del tiempo. Cada contribución retenida permaneció ligada al material original y al método que lo produjo.

Esos métodos detallados intencionalmente no conllevan el amplio conocimiento previo de un modelo de propósito general. un pequeño localQwenmodelo, atendido porvLLM, leyó el material seleccionado y agregó una descripción general fechada. Su tarea consistía en proporcionar los antecedentes habituales que conectaran los diferentes hallazgos y hicieran comprensible el intercambio en su conjunto.

Qwenno recuperó los pensamientos ocultos, el historial de entrenamiento ni el estado interno privado del modelo original. La útil contribución del modelo original ya estaba presente en sus mensajes guardados. Un modelo local reemplazable proporcionó un amplio conocimiento previo porque ese conocimiento no era exclusivo del proveedor original.

## Qué significa "completo" para este hito

La palabra se refiere a la lista mantenida de contribuciones para esta ejecución. Cada mensaje original y cada contribución que el proceso retuvo para la reconstrucción se puede encontrar y reunir nuevamente.

Esto no significa que un modelo proporcionara una interpretación completa. El logro es que las piezas aceptadas se conserven, se separen por fuente y método, y estén disponibles para su reconstrucción sin volver a ejecutar el intercambio original en línea.

## Cómo se sustenta el reclamo

La ejecución registra qué partes se ejecutaron, qué recibió cada una, qué devolvió cada una, qué contribuciones fueron rechazadas y qué controles se aprobaron. La reconstrucción se mide con respecto a su propia lista guardada de registros esperados.

Una prueba de componentes se describe como prueba de componentes. Una ejecución conectada se describe como una ejecución conectada. El trabajo planificado permanece separado de la implementación actual.

El próximo trabajo incluye pruebas independientes más amplias, soporte para más tipos de registros, más idiomas y culturas, pantallas de revisión más claras y una mejor medición del tiempo que las personas dedican a leer y corregir resultados.
