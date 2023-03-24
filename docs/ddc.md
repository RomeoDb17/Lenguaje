**Diagramas de casos de uso**

1. Nombra y describe brevemente los elementos que se utilizan en un diagrama de casos de uso. Busca información si es necesario.
   1. **Actores** : es *cualquier entidad que desempeñe un papel* en un sistema determinado. Puede ser una persona, una organización o un sistema externo.
   2. **Límites del sistema (sujeto)** : refleja los límites o *alcances que abarca* un determinado sistema. Se utiliza para reflejar diferentes áreas dentro del mismo.
   3. **Casos de uso** : se utiliza para representar una de las funcionalidades que realiza el sistema. Es una secuencia de acciones que hace el sistema y que producen un resultado que puede percibir un usuario.
   4. **Relaciones** : la interacción entre *dos casos de uso* o de *un actor con un caso de uso* se representa por medio de una relación. Las principales *relaciones* son: Generalización (Generalization), Inclusión (Include) y Extensión (Extends).

2. Por cada ejemplo de diagrama de casos de uso que aparece en las diapositivas, realiza su interpretación. Escribe la descripción con tus palabras.

![UML_diagrama_caso_de_uso](/img/UML_diagrama_caso_de_uso.svg)

**Diagramas de secuencia**

1. Nombra y describe brevemente los elementos que se utilizan en un diagrama de secuencia. Busca información si es necesario.
   1. **Objetos** : son bloques de construcción básicos de los diagramas UML y representan ciertas características de un elemento del sistema, que varían dependiendo del diagrama.
   2. **Líneas de vida** : son *líneas discontinuas* que sale del objeto y avanza en el tiempo desde arriba hacia abajo.
   3. **Mensajes** : es un elemento con nombre que define un tipo específico de comunicación entre *líneas de vida* de una interacción.
   4. **Ocurrencias de Ejecución** : *periodo de tiempo* durante el cual *un objeto* está *en ejecución*.
   5. **Ocurrencias de destrucción** : *momento* en el cual *un objeto es destruido*.****

2. Por cada ejemplo de diagrama de secuencia que aparece en las diapositivas, realiza su interpretación. Escribe la descripción con tus palabras.

![Ejemplo_1_secuencia](/img/Ejemplo_1_secuencia.png)

**Diagramas de estados**

1. Nombra y describe brevemente los elementos que se utilizan en un diagrama de estados. Busca información si es necesario.
   1. Estado: Un estado representa una condición o situación en la que se encuentra el sistema. Se representa mediante un rectángulo con esquinas redondeadas y se etiqueta con un nombre descriptivo.
   2. Transición: Una transición es una relación que describe el cambio de un estado a otro en respuesta a un evento o acción. Se representa mediante una flecha dirigida desde el estado de origen al estado de destino y se etiqueta con una etiqueta que describe la acción que desencadena la transición.
   3. Evento: Un evento es una acción que desencadena una transición. Puede ser un estímulo externo o interno que causa un cambio en el sistema. Se representa mediante una etiqueta en la flecha que conecta los estados de origen y destino.
   4. Acción: Una acción es una actividad que se realiza cuando se produce una transición. Puede ser una acción interna del sistema o una acción que se realiza en respuesta a un evento externo. Se representa mediante una etiqueta en la flecha que conecta los estados de origen y destino.
   5. Punto de inicio y fin: El punto de inicio es el estado inicial del sistema, desde donde se inicia el diagrama de estados. Se representa mediante un pequeño círculo conectado por una flecha al primer estado del sistema. El punto final es el estado final del sistema, donde termina el diagrama de estados. Se representa mediante un pequeño círculo conectado por una flecha al último estado del sistema.
   6. Jerarquía de estados: Los diagramas de estados también pueden tener una jerarquía de estados, donde un estado puede tener subestados y transiciones internas. Se representan mediante una caja contenedora alrededor de los subestados y se etiquetan con el nombre del estado principal.

2. Por cada ejemplo de diagrama de estados que aparece en las diapositivas, realiza su interpretación. Escribe la descripción con tus palabras.

![Ejemplo_1_estado](/img/Ejemplo_1_estado.png)

**Diagramas de actividades**

1. Nombra y describe brevemente los elementos que se utilizan en un diagrama de actividades. Busca información si es necesario.
   1. Actividad: Una actividad es una tarea que se realiza en el sistema y que contribuye al logro de un objetivo. Se representa mediante un rectángulo con esquinas redondeadas y se etiqueta con un nombre descriptivo.
   2. Acción: Una acción es una tarea atómica que se realiza como parte de una actividad. Puede ser una acción interna del sistema o una acción que se realiza en respuesta a un evento externo. Se representa mediante un rectángulo con esquinas rectas y se etiqueta con un nombre descriptivo.
   3. Transición: Una transición es una relación que describe el flujo de control entre dos actividades o acciones. Se representa mediante una flecha dirigida desde la actividad o acción de origen a la actividad o acción de destino y se etiqueta con una condición que debe cumplirse para que se produzca la transición.
   4. Decisión: Una decisión es un punto en el diagrama de actividades donde se toma una decisión basada en una condición. Se representa mediante un rombo y se etiqueta con la condición que debe cumplirse para que se tome una u otra ruta.
   5. Actividad inicial y final: La actividad inicial representa el punto de inicio del diagrama de actividades y se representa mediante un círculo negro. La actividad final representa el punto de finalización del diagrama de actividades y se representa mediante un círculo redondeado.
   6. Partición: La partición se utiliza para dividir el diagrama de actividades en diferentes secciones o particiones, cada una de las cuales representa una actividad o proceso independiente. Se representa mediante una línea vertical discontinua y se etiqueta con el nombre de la partición.

2. Por cada ejemplo de diagrama de actividades que aparece en las diapositivas, realiza su interpretación. Escribe la descripción con tus palabras.![Ejemplo_1_actividades](/img/Ejemplo_1_actividades.png)
