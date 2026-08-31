> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../13-The-Parts-Running-Today.md) | [Todos los idiomas](../README.md)

# Siga una solicitud a través de las partes de trabajo

![Las partes separadas conservan fuentes, registran cambios, recopilan hallazgos, generan resultados y los verifican.](../../illustrations/public-machinery-catalog.png)

La forma más clara de entenderRobot Brain es seguir una conversación guardada a través de él. Ninguna parte realiza todo el trabajo y ningún modelo de lenguaje controla el proceso.

## 1.LibreChatproporciona una pantalla

Una versión modificada deLibreChatpermite a una persona enviar una solicitud y leer los resultados en una conversación familiar.

LibreChatNo es la memoria ni la inteligencia del proyecto. Cerrarlo o reemplazarlo no elimina las fuentes, los hallazgos, las correcciones o las aprobaciones guardadas. Otras pantallas pueden solicitar el mismo trabajo subyacente.

## 2. El responsable de la fuente conserva la conversación.

Los mensajes de la persona, las respuestas del modelo de idioma y el orden del intercambio se guardan como el evento que ocurrió.

Los resúmenes e interpretaciones posteriores se almacenan por separado. No pueden reemplazar los mensajes originales ni convertir las palabras generadas en palabras propias de la persona.

## 3. La búsqueda encuentra posible material.

La búsqueda limita un registro grande a pasajes que pueden ser importantes para una solicitud. No decide que dos acontecimientos tienen el mismo significado simplemente porque utilizan palabras similares.

Los pasajes permanecen conectados a sus ubicaciones originales para que una persona o un control posterior pueda inspeccionarlos.

## 4. Los lectores locales centrados examinan características específicas

Los métodos locales separados analizan la estructura del lenguaje, las declaraciones, las posibles relaciones, el razonamiento, el tiempo, la experiencia humana y los valores.

Cada método tiene un tema nombrado y una autoridad limitada. Informa hallazgos relacionados con los pasajes que examinó. Puede decir que no se apoyó ningún hallazgo. No puede aprobar una cuenta final ni sobrescribir otro resultado.

Aquí es donde ocurre gran parte del análisis detallado. No se requiere un modelo de lenguaje de propósito general para improvisar toda la explicación de una sola vez.

## 5. El registro histórico preserva los cambios.

Los hallazgos, correcciones, desacuerdos, intentos fallidos y preguntas sin respuesta se agregan en orden. La vista actual puede cambiar sin eliminar la ruta que la produjo.

Esto evita que una respuesta fluida posterior oculte el trabajo, la incertidumbre y la corrección detrás de una conclusión.

## 6. LocalesQwenproporciona una amplia experiencia cuando es necesario

Los lectores concentrados pueden producir piezas precisas que son difíciles de entender juntas. un pequeñoQwenmodelo, atendido localmente porvLLM, puede leer partes seleccionadas de una conversación completa y sus hallazgos.

QwenEl trabajo de se limita a agregar una descripción general anticuada de conocimientos generales. Ayuda a explicar los antecedentes ordinarios que los métodos enfocados no comparten.

Qwenno está capacitado en la historia de la persona. No recupera el conocimiento oculto del modelo en línea original. La contribución real del modelo en línea ya sobrevive en sus respuestas guardadas. Otro modelo adecuado puede reemplazarQwensin quitar esas respuestas ni el análisis anterior.

## 7. El creador de solicitudes prepara el trabajo.

Para una respuesta o documento, el creador de solicitudes identifica el propósito, el lector, las preguntas requeridas, la evidencia relevante y la extensión razonable. Registra qué material se incluyó y se omitió.

Este paso puede preparar el trabajo para un proceso local fijo, un modelo local, un modelo en línea o ningún modelo. No es un servicio de reenvío que envía todas las solicitudes a cualquier modelo de idioma disponible.

## 8. Un escritor presenta un candidato.

Un modelo de lenguaje puede redactar o revisar el texto cuando sea útil. Otros trabajos se pueden completar mediante búsqueda, reglas fijas o material previamente verificado.

El escritor recibe sólo el material seleccionado y las instrucciones para ese trabajo. Su respuesta es un candidato, no un hecho nuevo ni una aprobación.

## 9. Los controles independientes y la aprobación humana deciden lo que queda

Los controles comparan al candidato con sus fuentes y requisitos. Pueden detectar pruebas faltantes, afirmaciones sin fundamento, material repetido o un resultado que no coincide con la solicitud.

El registro de aprobación indica la versión exacta aceptada. El modelo que produjo al candidato no puede aprobarse por sí solo.

## Por qué cada pieza es reemplazable

LibreChates una pantalla.Qwenes una fuente de amplios antecedentes. Un modelo en línea es un trabajador opcional. La búsqueda y los lectores enfocados son métodos limitados cuyos resultados se pueden reconstruir.

El valor duradero es la fuente conservada, su historia, los hallazgos relacionados con ella y el registro de lo que se aceptó. Reemplazar una pieza funcional cambia la forma en que se realiza el trabajo; no borra el conocimiento ya preservado.

## Alcance actual

Las partes descritas aquí existen en la implementación actual o en pruebas conectadas registradas. Las afirmaciones públicas distinguen la operación actual de pruebas, experimentos y trabajos futuros separados. El proyecto no utiliza la existencia de un componente como prueba de que todos los usos posibles de un extremo a otro estén completos.
