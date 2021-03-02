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

