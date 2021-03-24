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

* La aplicación de patrones de diseño: command, flyweight (scriptable objects, 
  entity-component-system), observer, prototype, singleton, state, object pool, 
  game loop, update method, components, strategy, mediator, entre otros.

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

Ejercicio 18: patrones de diseño - ESTADOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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


Ejercicio 20: patrones de diseño -  EVENTOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Los eventos permiten mantener desacopladas partes del código. Esto permite 
flexibilidad. Observa el `siguiente video <https://youtu.be/GUTURxgcoj4>`__.

* Explica qué ventaja tiene usar eventos en este caso.

El `siguiente video <https://youtu.be/JupiI9jegFg>`__ muestra una característica particular 
de Unity que permite exponer un evento en el editor de tal manera que puedas suscribirte 
a ese evento de manera gráfica usando el editor.

* ¿Qué ventaja le encuentras a lo anterior?

Ejercicio 21: patrones de diseño -  EVENTOS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Descarga el código de los dos video anteriores y analiza la implementación. 
Ten presente que el autor simplificó al máximo las cosas entonces lo que verás 
será ligeramente diferente al video, pero conserva la esencia.

Ejercicio 22: patrones de diseño - command pattern
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

Ejercicio 23: patrones de diseño - command pattern
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora mira de nuevo el video, pero esta vez reproduce el código del DEMO 1. 
Ana vez te funcione, analiza detalladamente la estructura del código. Dibuja 
un diagrama de clases y un diagrama de secuencias.

