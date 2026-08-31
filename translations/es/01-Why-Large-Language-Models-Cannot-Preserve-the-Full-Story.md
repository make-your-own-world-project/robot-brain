> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Todos los idiomas](../README.md)

# Por qué los grandes modelos de lenguaje no pueden preservar la historia completa

![Las piezas guardadas pierden valor cuando se separan sus fuentes, relaciones e historia.](../../illustrations/ordinary-storage-loses-context.png)

Los modelos de lenguaje pago más sólidos utilizados durante la construcción de este proyecto podrían realizar un trabajo impresionante. Podrían escribir, investigar, explicar y ayudar a resolver problemas difíciles. Todavía no pudieron preservar la historia completa detrás de un largo proyecto.

Una respuesta posterior podría recordar la conclusión pero perder los intentos fallidos, las correcciones y las pruebas que condujeron a ella. Las instrucciones anteriores podrían desaparecer cuando la conversación se hiciera demasiado larga. La modelo seguiría escribiendo como si no se hubiera perdido nada importante.

Ese es un problema grave cuando la historia que falta representa el tiempo, el conocimiento o la experiencia de alguien.

## Los archivos no son suficientes

Una carpeta puede contener cada nota, conversación, imagen y tarea sin perder la historia que las conecta.

Meses después, es posible que una persona necesite saber:

- que empezó el trabajo
- qué ideas se consideraron
- por qué un intento falló
- ¿Qué evidencia cambió el plan?
- ¿Qué conclusión es actual?
- lo que aún se desconoce
- por qué una nota vieja importa ahora

La búsqueda puede encontrar un archivo con palabras similares. No puede responder de manera confiable a esas preguntas. Enviar una gran cantidad de archivos a un modelo de lenguaje tampoco crea memoria permanente. El servicio ve lo que se seleccionó para esa solicitud. Cuando finaliza la solicitud, las conexiones útiles pueden volver a desaparecer.

## El entrenamiento también pierde la ambientación original.

Los modelos de lenguaje aprenden patrones de enormes colecciones de trabajo humano. Eso es lo que los hace útiles. También es por eso que no pueden actuar como un archivo fiel de todo lo que los formó.

Las ideas de un libro, artículo, conversación, traducción o comunidad se mezclan con ideas de muchos otros. El modelo no mantiene intacto cada trabajo con su autor, propósito, audiencia, evidencia, desacuerdo y correcciones posteriores adjuntas.

Es posible que la obra original aún exista en otro lugar. Un proveedor también puede conservar copias separadas. La pérdida aquí descrita ocurre dentro del modelo entrenado: mantiene la influencia útil del trabajo pero no puede reconstruir el significado humano completo a su alrededor.

Repetir una frase no es lo mismo que conservar ese significado. Un modelo puede reproducir palabras familiares sin saber por qué fueron escritas, qué situación describieron, qué vista faltaba o qué sucedió después.

## La historia perdida también esconde prejuicios

Ningún modelo de lenguaje aprendido de todo el mundo.

Su conocimiento refleja lo que se escribió, conservó, recopiló, tradujo, autorizó, etiquetó y seleccionó. También refleja lo que faltaba. Algunas lenguas y comunidades tienen mucho más material publicado que otras. Los archivos preservan las opiniones de instituciones poderosas con más frecuencia que el conocimiento privado, local u oral.

Las personas que construyen el modelo toman más decisiones sobre qué eliminar, recompensar, desalentar o tratar como una buena respuesta. Las reglas del producto añaden otra capa. Una respuesta terminada puede contener todas esas influencias sin mostrar cuál afectó a una oración en particular.

Una cita encontrada durante una nueva solicitud no revela este historial completo. Muestra una fuente utilizada o nombrada para esa solicitud, no todo lo que le enseñó al modelo cómo interpretar el tema.

## Lo que este proyecto guarda en su lugar

Robot Brain mantiene la fuente antes de pedir ayuda a cualquier modelo para interpretarla. La fuente no cambia cuando se agrega un resumen, corrección o nueva interpretación.

El trabajo posterior se guarda al lado con una fecha y un enlace al pasaje correspondiente. Un intento fallido puede permanecer visible. Una conclusión corregida puede señalar la evidencia que la cambió. Si se desconoce el motivo de un cambio, así lo indica el expediente.

Cuando alguien necesita una respuesta o un documento, el creador de solicitudes reúne la parte de ese historial necesaria para el trabajo. El resultado puede ser más corto que el registro completo sin pretender sustituirlo.

Un modelo de lenguaje puede ayudar con ese resultado. No puede borrar las fuentes, reescribir el pasado ni hacer que una suposición sin fundamento pase a formar parte del registro aceptado.

## la prueba practica

Un resultado útil debería permitir al lector responder cuatro preguntas:

1. ¿Qué pasó?
2. ¿Qué evidencia respalda este relato?
3. ¿Qué cambió, falló o sigue en disputa?
4. ¿Qué se desconoce aún?

Si el expediente no puede responder a una de esas preguntas, un lenguaje refinado no debería ocultar la brecha.
