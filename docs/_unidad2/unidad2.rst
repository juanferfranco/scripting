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
anterior.

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


Ejercicio 6: principios SOLID- Video 2-ver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vuelve a ver el video y responde estas preguntas luego de verlo:

* Si el código ya funciona ¿Para qué es necesario hacer un refactoring 
  en este ejemplo?

* Uno de los principios SOLID que se aplica es el Single responsibility.
  ¿En parte del código se aplica este principio? ¿Cuáles son las responsabilidades 
  detectadas?

* ¿Un código debería estar Open a qué y Closed a qué?
  
* ¿En este ejemplo qué deseamos extender y qué no queremos estar modificando?

* ¿Cómo se está aplicando el principio SOLID Liskov substitution en este 
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

