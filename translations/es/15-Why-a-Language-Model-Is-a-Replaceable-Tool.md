> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Todos los idiomas](../README.md)

# Utilice un modelo de lenguaje para el trabajo, no como memoria

![Las herramientas, los archivos entrenados y las colecciones de fuentes mantienen registros separados de su origen y términos.](../../illustrations/tool-model-source-index.png)

Robot Brain No es un modelo de lenguaje con memoria adicional. Es el software de mantenimiento de registros, análisis, ensamblaje y verificación el que decide cuándo sería útil un modelo de lenguaje y qué trabajo limitado puede realizar.

El modelo más potente disponible no siempre es la mejor opción para ese trabajo.

Un modelo de lenguaje pago puede ser adecuado para investigaciones o escritos difíciles. Un pequeño modelo local puede ser suficiente para una explicación general. La búsqueda puede ser suficiente para encontrar un pasaje. Un proceso fijo puede ser más seguro cuando la respuesta debe seguir una regla exacta. A veces la mejor respuesta es aquella que ya fue revisada y guardada.

El creador de solicitudes toma esa decisión a partir de las necesidades del trabajo. Puede utilizar un modelo, combinar varios métodos limitados, reutilizar el trabajo comprobado o no realizar ninguna llamada al modelo. Por eso no se trata de un proxy que simplemente reenvía solicitudes a otro servicio.

## Modelos pagados en línea

Los servicios de modelos de lenguaje comerciales ayudaron a construir este proyecto. Apoyaron la investigación, la codificación, la redacción y la revisión.

También perdieron instrucciones anteriores, acortaron conversaciones, adivinaron causas, enterraron respuestas breves en rellenos y reportaron el trabajo como completo antes de verificarlo. Corregir esas fallas requirió más asignación remunerada y más tiempo humano.

Su límite más profundo no es un mal aviso. Un modelo entrenado no puede reconstruir la historia completa del trabajo humano que lo enseñó. Mantiene patrones y al mismo tiempo pierde vínculos confiables con cada autor, propósito, audiencia, disputa, corrección y punto de vista faltante.

Ese amplio conocimiento sigue siendo útil. Simplemente no debería convertirse en el único lugar donde exista la historia de alguien.

Para una solicitud en línea,Robot Brain registra qué modelo se utilizó, qué recibió, qué devolvió, cuánto costó el servicio, qué comprobaciones se realizaron y si se conservó el resultado. Los antecedentes no respaldados siguen siendo una sugerencia del modelo más que un hecho fundamentado.

## El modelo local no está entrenado en la persona.

La instalación actual ejecuta una pequeñaQwenmodelo de lenguaje a travésvLLMen hardware local.Qwenes un contribuyente reemplazable, no el proyecto en sí.

No aprende entrenándose en las conversaciones, el trabajo o la vida de la persona. La capacitación mezclaría esa historia en un modelo y debilitaría el camino de regreso a las palabras y eventos originales.

En cambio,Qwenrecibe material seleccionado para un trabajo después de finalizar una conversación. Otros métodos locales ya han examinado el lenguaje, las declaraciones, las relaciones, el razonamiento, el tiempo, la experiencia humana y los valores en el intercambio.Qwenagrega los amplios antecedentes que esos métodos no comparten. Esto hace que sea más fácil explicar qué sucedió y por qué.

Qwenno revela los pensamientos ocultos, la formación o el razonamiento privado del asistente en línea. La útil contribución del asistente en línea ya está presente en la conversación guardada. Los conocimientos generales no son exclusivos de ese asistente, por lo que otro modelo adecuado puede ayudar a conectar las piezas grabadas.

ElQwenLa lectura se guarda con el nombre del modelo y la fecha. Permanece separado de la conversación y puede corregirse o reemplazarse más adelante. La solicitud nunca tiene que salir del hardware local.

## La búsqueda no es una explicación.

La búsqueda puede encontrar pasajes con palabras o temas relacionados. No puede decidir por qué un evento fue importante, si una acción causó otra o qué quiso decir alguien.

Esas conclusiones necesitan evidencia, historia y margen de corrección.

## El costo incluye el tiempo de la persona.

El precio y la velocidad no son los únicos costos. Una respuesta barata se vuelve cara cuando alguien pasa horas buscando el error, explicando nuevamente el historial y reparando el resultado.

Por lo tanto, el creador de solicitudes considera las tarifas de servicio, la espera, los reintentos, el uso de energía y la verificación humana. Un modelo más pequeño, un método local fijo o un resultado guardado pueden crear más valor cuando su trabajo es más fácil de inspeccionar.

## Las fuentes siguen siendo identificables

Los registros originales, el texto copiado, las respuestas modelo, la investigación pública, las citas y las reseñas posteriores siguen siendo cosas diferentes.

Cuando se conoce y se permite, el registro conserva el creador, el propósito, la audiencia, la fecha, el idioma, las pruebas, los desacuerdos, los derechos y las correcciones posteriores. La disponibilidad pública y el crédito no otorgan por sí solos permiso para redistribuir material protegido.

Este repositorio incluye documentación pública e ilustraciones creadas por el proyecto. Omite registros privados, contraseñas, detalles de acceso, secretos de proveedores y material externo cuya divulgación no ha sido autorizada.
