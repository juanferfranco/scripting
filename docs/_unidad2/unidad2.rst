Unidad 2. Patrones de diseño
==========================================

Introducción
--------------

En esta unidad vamos a repasar y aplicar algunos principios de desarrollo 
de software que te ayudarán a estructurar tus aplicaciones interactivas para 
que sean más fáciles de modificar y extender.

Propósito de aprendizaje
^^^^^^^^^^^^^^^^^^^^^^^^^^

Analizar algunos principios de diseño y patrones para la estructuración 
de aplicaciones interactivas utilizando plataformas de software interactivas.

Temas
^^^^^^

* Principios SOLID: Single responsibility, Open–closed, Liskov substitution, 
  Interface segregation, Dependency inversion.

* La aplicación de patrones de diseño: command, flyweight (scriptable objects), 
  observer, singleton, state, object pool, component, entre otros.

* Persistencia.

* El análisis de arquitecturas guiadas por eventos y por datos.        


Ejercicios y proyectos
------------------------

Ejercicio 0: REPASO
^^^^^^^^^^^^^^^^^^^^^^

Recuerdas qué es una interfaz? un delegado? un evento? si la respuesta es NO.
Te voy a dejar un `playlist <https://www.youtube.com/playlist?list=PLzDRvYVwl53t2GGC4rV_AmH7vSvSqjVmz>`__ 
muy bueno donde podrás repasar esos conceptos.

Para lo que sigue es IMPORTANTE que repases en especial 
`qué es una interface <https://www.youtube.com/watch?v=MZOrGXk4XFI>`__.


Ejercicio 1: principios SOLID- Video 1-ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vas a analizar de manera práctica los principios de diseño SOLID mediante 
unos videos.

Primero comienza SIMPLEMENTE observando este `video <https://www.youtube.com/watch?v=_yf5vzZ2sYE>`__. 

Ejercicio 2: principios SOLID- Video 1-reproducir
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora vas a ver de nuevo el video, pero esta vez descarga el código y observa 
ambas cosas a la vez. 

* Escribe qué GameObjects tiene la escena.
* ¿Cuál es la función de cada GameObject en la escena?
* Busca la documentación de todo lo que no entiendas.

Ejercicio 3: principios SOLID- Video 1 - memoria
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Crea un nuevo proyecto y trata de reproducir de memoria el proyecto 
anterior, pero no tienes que reproducir el arte tal cual, solo nos vamos a 
concentrar en el código.

Ejercicio 4: principios SOLID- Video 2-ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora vas ver `este <https://www.youtube.com/watch?v=QDldZWvNK_E>`__ video donde se 
aplicarán algunos principios SOLID para hacer un refactoring al MonoBeHaviour 
SelectionManager. Profe, ¿Para qué si ya funciona? ya verás...

Mientras estás viendo el video anota todos los conceptos de programación 
y de C# que no entiendas o no recuerdes.

Ejercicio 5: principios SOLID- Video 2 - repasa
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En el ejercicio anterior anotaste los conceptos que no recordabas o 
no entendías. Ahora es tiempo de estudiarlos de nuevo.


Ejercicio 6: principios SOLID- Video 2- analiza
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vuelve a ver el video y responde estas preguntas luego de verlo:

* Si el código ya funciona ¿Para qué es necesario hacer un refactoring 
  en este ejemplo?

* Uno de los principios SOLID que se aplica es el Single responsibility.
  ¿En parte del código se aplica este principio? ¿Cuáles son las responsabilidades 
  detectadas?

* ¿Un código debería estar Open a qué y Closed a qué?
  
* ¿En este ejemplo qué deseamos extender y qué no queremos estar modificando?

* ¿Cómo se está aplicando el principio SOLID Liskov's substitution en este 
  ejemplo?

* ¿Qué relación tiene el polimorfismo en tiempo de ejecución con este 
  principio SOLID?

* En el ejemplo proponen una manera de aplicar otro principio 
  ¿Cómo se aplica el principio SOLID Interface segregation? 

* Finalmente, en el ejemplo ¿Cómo se está aplicando el principio 
  SOLID Dependency inversion?

Ejercicio 7: principios SOLID- Video 2 - código
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código del video 2 y organiza el proyecto para que puedas 
ver funcionando todo lo que viste en el video.

Ejercicio 8: principios SOLID- Video 2 - RETO
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Añade otro comportamiento para la selección de objetos. RECUERDA, sigue 
los principios SOLID y justifica por qué el nuevo comportamiento que has 
añadido respecta dichos principios.

Ejercicio 9: principios SOLID- Video 3 - ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vas a continuar el procesos de refactoring aplicando los principios SOLID. 
Esta será la segunda parte del video anterior. 
`Aquí <https://www.youtube.com/watch?v=Fs8jy7DHDyc>`__ está el video.

De nuevo, mira primero el video y anota todos los conceptos de programación 
y de C# que no entiendas o no recuerdes.

Ejercicio 10: principios SOLID- Video 3 - repasa
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En el ejercicio anterior anotaste los conceptos que no recordabas o 
no entendías. Ahora es tiempo de estudiarlos de nuevo.

Ejercicio 11: principios SOLID- Video 3 - analiza
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Nota que en este video número 3 se identifican las responsabilidades 
y luego se SEGREGAN esas responsabilidades en interfaces.

* Lista cuáles son las responsabilidades del SelectionManager.

* Indica cómo están segregadas las responsabilidades y qué principio SOLID  
  se está aplicando.

* Cuando decimos que una clase depende de una interface en vez de una 
  implementación concreta a ¿Qué principio nos estamos refiriendo?

* ¿En qué parte del código se ve aplicado el principio anterior?

* Cuando queremos reemplazar fácilmente un comportamiento por otro 
  ¿Qué principio estamos aplicando?

* ¿Cómo aplicamos el principio anterior en este ejemplo?

Ejercicio 12: principios SOLID- Video 3 - código
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código del video 3 y organiza el proyecto para que puedas 
ver funcionando todo lo que viste en el video.

Aprovecha y analiza de nuevo ya en contexto.

Ejercicio 13: principios SOLID- Video 4-ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En `este <https://www.youtube.com/watch?v=cxJnvEpwQHc>`__ video vas a ver 
uno de los beneficios de aplicar los principios SOLID cuando necesitas 
hacer modificaciones a tu proyecto.

Ejercicio 14: principios SOLID- Video 4 - analiza
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

¿Cómo funciona la idea de usar el producto punto en el video 4?

Ejercicio 15: principios SOLID- Video 4 - código
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código del video 4 y organiza el proyecto para que puedas 
ver funcionando todo lo que viste en el video.

Analiza de nuevo ya en contexto.

Ejercicio 16: principios SOLID- Video 5 - ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En `este <https://www.youtube.com/watch?v=MjwbhfR7DsM>`__ último video de la 
serie vas a aprender a realizar una herramienta 
para el editor que te ayudará a realizar cambios de comportamientos 
de manera más fácil y gracias al uso de los principios SOLID.

Ejercicio 17: principios SOLID- Video 5 - código
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código del video 5 y organiza el proyecto para que puedas 
ver funcionando todo lo que viste en el video.

Ejercicio 18: patrones de diseño - STATE pattern
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora que ya conoces los principios SOLID, te voy a proponer que 
estudies algunos patrones de diseño que te van a servir como 
herramienta para estructurar mejor tu código. 

Observa y analiza `este video <https://youtu.be/_1pz_ohupPs>`__.

En `este enlace <https://github.com/Brackeys/Turn-based-combat>`__ puedes 
descargar el juego.

* ¿Qué tipo de juego se construye en el video?
* ¿Cuáles son los ESTADOS del juego?
* ¿Qué es un tipo `enum <https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/enum>`__ 
  en C# y para qué se usa en el juego?
* Analiza detenidamente el código en BattleSystem.cs. Explica cómo funciona 
  cuándo el juego inicia, al presionar los botones de ataque y curación.
* ¿Para qué se usan las corutinas en el juego?
* Trata de explicar cómo están implementadas las corutinas.

Ahora vas a supón que necesitas ADICIONAR funcionalidad o añadir nuevas características 
al juego.

En `este <https://youtu.be/5PTd0WdKB-4>`__ video te proponen precisamente eso.
Puedes bajar el código del video `aquí <https://www.patreon.com/posts/32320915>`__.

* ¿Qué problema tiene el juego del primer video a la hora de añadir más funcionalidad?
* ¿A qué se refieren en el video con el término Spaghetti Code?
* ¿Para qué proponen utilizar una STATE MACHINE? ¿Qué patrón de diseño es este?
* Explica en tus propias palabras qué es el PATRÓN STATE.
* En la implementación del patrón se crea una clase abstracta. ¿Para qué sirve 
  en este caso?
* ¿Por qué el refactoring que se propone con el patrón STATE es más escalable?

Ejercicio 19: patrones de diseño -  INTERFACES
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora vas a ver la flexibilidad que obtienes al estructurar tu código por medio 
de eventos. Pero antes de eso repasa de nuevo el manejo de interfaces.

Dele una mirada a `este <https://youtu.be/2LA3BLqOw9g>`__ video. Mira que el personaje 
del video ya terminó el programa, PERO, como siempre, si la arquitectura no está bien 
pensada, extender el código o añadir funcionalidad no será fácil.

Descarga el código del video de `este sitio <https://www.patreon.com/posts/35152838>`__.
La escena inicial está en la carpeta _Project/Start Here.

Analiza esta escena detenidamente.Observa los scripts.

* ¿Por qué en el video indican que esta parte del código no es escalable?

  .. code-block:: csharp

      private void Update()
      {
          var nearestGameObject = GetNearestGameObject();
          if (nearestGameObject == null) return;
          
          if (Input.GetButtonDown("Fire1"))
          {
              var lightSwitch = nearestGameObject.GetComponent<Lamp>();
              if (lightSwitch != null)
              {
                  lightSwitch.Switch();
              }
              var door = nearestGameObject.GetComponent<Door>();
              
              if (door != null)
              {
                door.Open();
              }
              
              var radio = nearestGameObject.GetComponent<Radio>();
              if (radio != null)
              {
                radio.Toggle();
              }
          }
      }

* Si quieres adicionar otros objetos para interactuar tendrías que modificar el código anterior.
  ¿Cómo lo harías? ¿Qué principio SOLID estarías violando?

* En el video  ¿A qué se refieren con el término clase monolítica?

* Específicamente cuál es el problema de escalabilidad que tiene el programa?

La carpeta _Project/Completed tiene el refactoring al problema anterior

* ¿Cómo se están usando las interfaces en este caso para permitir que el programa 
  escale mejor?

* ¿Qué principio SOLID estás aplicando en este caso?

* Explica cómo funciona el componente CompositeInteractable.


Ejercicio 20: patrones de diseño -  OBSERVER pattern / EVENTOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Los eventos permiten mantener desacopladas partes del código. Esto permite 
flexibilidad. Observa el `siguiente video <https://youtu.be/GUTURxgcoj4>`__.

* Explica qué ventaja tiene usar eventos en este caso.

El `siguiente video <https://youtu.be/JupiI9jegFg>`__ muestra una característica particular 
de Unity que permite exponer un evento en el editor de tal manera que puedas suscribirte 
a ese evento de manera gráfica usando el editor.

* ¿Qué ventaja le encuentras a lo anterior?

Ejercicio 21: patrones de diseño -  OBSERVER pattern / EVENTOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código de los dos video anteriores y analiza la implementación. 
Ten presente que el autor simplificó al máximo las cosas entonces lo que verás 
será ligeramente diferente al video, pero conserva la esencia.

Ejercicio 22: patrones de diseño - COMMAND pattern
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Este patrón hace que un objeto le delegue la responsabilidad a otro 
objeto de ejecutar un comando. Ya verás en el video por qué esto 
te dará flexibilidad para hacer operaciones más complejas con el comando.

Para analizar este patrón vas a comenzar mirando, solo mirando,
`este <https://youtu.be/UoNumkMTx-U>`__ video de Jason Weimann.

* En el video, cuando el autor dice que _inputReader y _commandProcessor 
  serán ``getting chached`` ¿Qué quiere decir esto? ¿Qué ventaja tiene hacerlo?
  ¿Qué pasaría si no lo hago?

* ¿De qué instancias externas depende una ENTIDAD?

* ¿Qué relación hay entre MoveCommand y Command?

* ¿Por qué no se puede instanciar Command?

* Nota que el método ExecuteCommand de CommandProcessor recibe una 
  referencia a un tipo Command, pero en el código de la Entidad no se pasa
  la referencia a un objeto tipo Command sino a un tipo MoveCommand. 
  ¿Entonces por qué funciona? (recuerdas la pregunta sobre la relación entre 
  MoveCommand y Command). A esto se le conoce como polimorfismo. ¿Qué 
  tipo de polimorfismos es este?

* En el video nota que el autor indica que sería posible llamar directamente 
  a moveCommand.Execute(), pero no se hace así sino que se llama ese método
  mediante otro objeto cuya referencia esta en _commandProcessor. ¿Por qué 
  es esto? Entonces cuál es la gracias de este patrón Command?

* El autor menciona que el demo 1 puede ser ineficiente en el uso de memoria, 
  particularmente en el método update de la Entidad. ¿Por qué es esto?

* Analiza el demo2, puedes cambiar el personaje por un cilindro si gustas.

Ejercicio 23: patrones de diseño - COMMAND pattern
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora mira de nuevo el video, pero esta vez reproduce el código del DEMO 1. 
Una vez te funcione, analiza detalladamente la estructura del código. Dibuja 
un diagrama de clases y un diagrama de secuencias para que puedas entender 
de manera gráfica las partes de la solución y sus relaciones.

Ejercicio 24: patrones de diseño - FLYWEIGHT pattern
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

El patrón de diseño flyweight (peso mosca) busca optimizar el ``uso de la memoria`` 
haciendo que varias entidades (por ejemplo instancias) compartan aquellas cosas que son 
comunes entre ellas. En un motor como Unity se cuenta 
con varias de estas optimizaciones; sin embargo, vamos a concentrarnos en 
dos de ellas: scriptable objects y el entity-component-system.

Lo primero que debes hacer es leer 
`¿Qué son los scriptable objects? <https://docs.unity3d.com/Manual/class-ScriptableObject.html>`__

* ¿Cuándo es útil utilizar un Scriptable object (SO)?
* ¿Qué significa que se pueda acceder a los datos que almacena un SO 
  por REFERENCIA desde varios Prefabs?
* Entonces si varios Profabs utilizan el mismo SO ¿Cuántas copias en memoria 
  de los datos de ese SO hay?
* ¿Cómo puedes usar un SO en una aplicación interactiva? Resume los pasos que debes seguir.

En el `siguiente video <https://www.youtube.com/watch?v=7jxS8HIny3Q&t=40s>`__ puedes darle 
una última revisión a los puntos anteriores.

* ¿Por qué crees que los SOs son una característica que permite hacer el desarrollo de una 
  aplicación interactiva más amigable con el diseñador?

Y en este otro video puedes ver `cómo usar SOs <https://youtu.be/E91NYvDqsy8>`__ en una 
aplicación específica.

* Explica de qué se trataba el ejemplo del video y cómo se utilizaron los SO en 
  esta aplicación.

Ejercicio 25: patrones de diseño - OBJECT POOL
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

La memoria de un computador es un recurso finito que debemos usar de la mejor 
manera posible. Actualmente las plataformas móviles, incluyendo los headset 
de VR standalone demandan que hagas un uso adecuado de este recurso. 
El patrón object pool busca REUTILIZAR objetos ya creados y de esta manera 
puedas mantener un uso apropiado de la memoria.

Observa y analiza el `siguiente video <https://youtu.be/uxm4a0QnQ9E>`__.

* ¿De qué se trata la aplicación con la que se ilustra el patrón de diseño 
  en el video?
* ¿Cómo se está usando el patrón de diseño en el ejemplo?
* ¿Qué significa en el contexto de una aplicación interactiva EVITAR generar 
  basura? (Consulta qué es el GARBAGE collector).
* ¿Por qué es importante evitar al máximo que el Garbage collector trabaje mucho?

Ejercicio 26: patrones de diseño - Calentamiento para el siguiente ejercicio
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Antes de que realices el próximo ejercicio. REPASA de nuevo los patrones 
que están en `este video <https://youtu.be/hQE8lQk9ikE>`__.

* Lista los patrones que viste en el video y describe cuál es el objetivo 
  de cada uno de ellos. RECUERDA, la idea es repasar.

* Trata de implementar algunos de los ejemplos que viste en el video.

* OPCIONAL 1. En el video el autor hace referencia al patrón de diseño 
  STATE. Este ya lo trabajamos, pero si quieres repasarlo de nuevo, te dejo 
  `aquí el enlace <https://youtu.be/V75hgcsCGOM>`__ al video que señala el 
  autor.

* OPCIONAL 2. El mismo autor tiene un video sobre el patrón singleton.
  Lo puedes `ver aquí <https://www.youtube.com/watch?v=ptkxRn0HCJc>`__.

Ejercicio 27 (MUY IMPORTANTE): patrones de diseño - Última iteración
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En este ejercicio vamos a realizar una última iteración sobre el tema 
de patrones de diseño. La idea es que hagas esto:

* Inventa EJEMPLOS en Unity para estos patrones (puedes combinar varios 
  si quieres).

  * COMMAND
  * FLYWEIGHT (Scriptable Objects)
  * OBSERVER
  * COMPONENT
  * SINGLETON 
  * STATE 
  * OBJECT POOL

* Escribe un párrafo corto que explique en CADA EJEMPLO cómo usaste el patrón.

Ejercicio 28: persistencia - Introducción
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Persistencia se refiere a la capacidad de almacenar permanentemente 
información de tu aplicación interactiva en algún medio de almacenamiento 
permanente.

Inicia observando y analizando el `siguiente video <https://www.youtube.com/watch?v=uD7y4T4PVk0>`__.
Te darás cuenta que no hay un solo método para realizar la persistencia en tus aplicaciones 
interactivas. Cada método tiene sus debilidades y fortalezas. Por tanto, lo que te propongo 
con este ejercicio es que comiences a identificarlas.

* En el video te hablan de varios métodos para realizar la persistencia en tus aplicaciones 
  interactivas. Lista esos métodos.
* Para cada método indica cuándo se usa, que debilidades tiene y qué fortalezas.
* Explica ¿Qué significa el término serialización de los datos?
* En el video mencionan un formato denominado JSON. Busca en qué consiste ese formato.
* ¿Qué ventaja podría tener guardar datos en formato JSON comparado con un 
  `formato binario <https://en.wikipedia.org/wiki/Binary_file>`__? 

Repasa de nuevo y complementa las preguntas de este ejercicio con el texto en 
`este blog <https://blogs.unity3d.com/2021/02/23/persistent-data-how-to-save-your-game-states-and-settings/>`__.

Ejercicio 29: persistencia - ejemplos
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Inventa ejemplos para PlayerPrefs, JSON y JsonUtility. NO TE COMPLIQUES la idea es que 
aproveches este momento para que te quede código que luego puedas utilizar en otros proyectos.

Ejercicio 30: Arquitectura de una aplicación interactiva -Introducción 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

El término arquitectura de una aplicación interactiva se refiere a la manera 
como puedes organizar las diferentes partes que componen tu aplicación interactiva.

Observa y analiza `este video <https://youtu.be/WLDgtRNK2VE>`__.

* En el video indican cuál son las propiedades deseadas para la arquitectura 
  del juego. Lista cuáles son.
* En el video ¿Para qué se están utilizando SOs?
* Con lo que has aprendido hasta este momento porqué las conexiones rígidas entre 
  partes de tu aplicación interactiva pueden conducirte a problemas de escalabilidad?
* En el video mencionan el patrón SINGLETON. Explica de nuevo para qué se usa y 
  qué PROBLEMA tiene. 
* ¿Por qué el uso de SINGLETONS puede complicar los procesos de prueba de un programa?
* ¿Qué significa que un SO puede servir como un EVENT-RELAYER centralizado?
* Dibuja un diagrama que muestre cómo puedes utilizar un SO como un EVENT-RELAYER.
* ¿Por qué el uso de un SO como un EVENT-RELAYER ayuda a construir aplicaciones 
  interactivas modulares y fáciles de mantener?
* En el video ¿Qué quiere decir que un SO se puede usar como un punto intermedio 
  de comunicación? ¿Qué relación tiene esto con un EVENT-RELAYER? 
* ¿Qué quiere decir que un SO se usa como CHANNEL?

Ejercicio 31: Arquitectura de una aplicación interactiva - reto
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Crea una aplicación interactiva que al presionar un botón incremente un entero 
contenido en un Scriptable Object. Ese mismo SO debe generar un evento que 
incluya como argumente el valor del entero. Crea al menos estos tres GameObjects que se 
suscriban a ese evento: uno que actualice un texto en pantalla con el valor del entero,
uno que imprima en la consola el valor del entero, uno que genere una alerta auditiva 
cada que el entero cambie.

Como puedes ver, la idea es que implementes con un SO en EVENT-RELAYER.

Ejercicio 32: Arquitectura de una aplicación interactiva - reto
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Crea una aplicación que incluya DOS escenas. Cada escena tendrá 
un botón para incrementar un entero que estará en un SO, un botón para 
cambiar de escena y un texto para mostrar el valor del entero cada que se 
incremente. El entero estará en el mismo SO para ambas escenas.

* ¿Qué puedes concluir de este experimento?
* En el `manual de Unity <https://docs.unity3d.com/Manual/class-ScriptableObject.html>`__ 
  se describe que los SO tiene diferente comportamiento cuando estás en modo editor/play 
  y cuando estás en modo deploy. Explica la diferencia entre ambos.
* Si quieres conservar, en modo deploy, el valor de de los SO entre sesiones de la 
  aplicación interactiva ¿Qué harías?

.. warning:: FIN DE LA UNIDAD

   Aunque con esto llegamos al fin de la Unidad, todavía tienes mucho más 
   que estudiar y analizar en cuanto a los asuntos de arquitectura de una aplicación 
   interactiva. ¿Tal vez en Scripting 2? (no existe ese curso).

.. warning:: OPCIONAL

   Lee e`ste blog <https://blogs.unity3d.com/2017/11/20/making-cool-stuff-with-scriptableobjects/>`__ 
   y observa un par de videos que están allí. Verás más usos de los SO.

.. warning:: PARA VACACIONES

   Te recomiendo MUCHO, MUCHO, que estudies y analices el 
   `proyecto CHOP-CHOP <https://github.com/UnityTechnologies/open-project-1>`__. Tiene 
   mucha documentación y es un proyecto cargada de muchas ideas que pueden servirte

.. warning:: OPCIONAL

   Este `es un tutorial <https://www.youtube.com/watch?v=HVls6_srbNc>`__ que muestra 
   cómo usar el sistema de eventos de Chop-Chop.

