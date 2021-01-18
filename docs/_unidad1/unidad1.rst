Unidad 1. Estructuras de datos, algoritmos y trabajo en equipo
=================================================================

Introducción
--------------

En esta unidad vamos a introducir algunas herramientas que te permitirán
organizar tu trabajo y trabajar en equipo. Una de las herramientas más
importantes será aquella que permita hacer control de versión.

También vamos a repasar algunos de los conceptos más importantes que has 
estudiado en tus cursos de programación y claro, los avanzaremos aún más 
estudiando a fondo la implementación de algunas estructuras de datos y 
algoritmos relacionados con esas estructuras. 

Propósito de aprendizaje
^^^^^^^^^^^^^^^^^^^^^^^^^^

Aplicar algunas estructuras de datos y algoritmos en la resolución 
de problemas.

Aplicar herramientas de productividad y control de versión a la hora
de programar.

Temas
^^^^^^

* Control de versión y flujo de trabajo.

* Conceptos básicos de funcionamiento de un computador.

* Estructuras de datos: listas, stacks, colas, diccionarios, grafos.

* Algoritmos de búsqueda de caminos y toma de decisiones.

Trayecto de acciones, tiempos y formas de trabajo
---------------------------------------------------

Ejercicio 1
^^^^^^^^^^^^^

* Crea una cuenta en GitHub con tu correo institucional de la UPB. Si
  tienes la cuenta, tanto mejor.
* Explora `este <https://www.gitkraken.com/student-resources>`__ sitio y 
  solicita, por medio de tu cuenta de GitHub, el paquete de herramientas
  para estudiantes. Este proceso requiere aprobación, así que te recomiendo
  que lo hagas YA.
* Ingresa a `este <https://www.gitkraken.com/learn/git/tutorials>`__ sitio
  y realiza el curso corto sobre Git.
* Finalmente, observa el siguiente `video <https://www.youtube.com/watch?v=lYAHmthUO1M>`__
  para que analices un posible flujo de trabajo en equipo utilizando herramientas
  de control de versión.

Ejercicio 2
^^^^^^^^^^^^

Considera el último video que viste donde te muestran cómo contribuir a un proyecto 
open source. Vamos a suponer que el proyecto lo inició uno de tus compañeros 
del equipo del trabajo. Los pasos que deberías seguir para contribuir al proyecto 
serían:

#. Puedes hacer un fork del repositorio en tu cuenta de GitHub.
#. Clona en tu computador el repositorio.
#. Crea un rama o branch sobre la cual realizarás tu contribución.
#. Realiza únicamente commits sobre los archivos de tu contribución. Observa que el
   video te sugieren no modificar archivos de configuración del proyecto que no tienen
   nada que ver con tus aportes.
#. Envía (push) a GitHub la rama con tus cambios.
#. Cámbiate de nuevo a la rama ``master`` de tu copia local del repositorio.
#. Luego procede a realizar un merge entre la rama que creaste y la master. De esta manera
   tus aportes se añadirán a la rama principal (de tu clone)
#. Luego realiza el commit con tus cambios.
#. Envía (push) de nuevo el repositorio a tu cuenta en GitHub.
#. GitHub detectará las diferencias entre tu rama master y la de tu compañero de equipo.
#. Procede a realizar un pull request.
#. Tu compañero encargado de hacer la integración de tus cambios al proyecto aprobará o no
   tu contribución luego de probar que todo está correcto.

Ejercicio 3
^^^^^^^^^^^^^

Ahora observa `este <https://youtu.be/WH7qDUYHGK8>`__ video. 

Reproduce tu mismo el primer caso: creas un repo en GitHub, lo clonas y luego 
adicionas el proyecto de Unity.

* Cuando creas tu propio repositorio para trabajar con Unity ¿Qué configuración
  debes hacerle al proyecto? 
  (Project Settings: version control (Visible Meta files) y asset serialization (Force text)).
* ¿En dónde debe estar el archivo .gitignore? Abre el archivo y mira las primeras líneas.
  Ahí está la respuesta.

Ejercicio 4
^^^^^^^^^^^^

Ahora reproduce tu mismo el segundo caso (video anterior): creas un proyecto de Unity y luego 
adicionas un repositorio al proyecto. De todas 
maneras no olvides ir a Project Settings (Project Settings: version control 
(Visible Meta files) y asset serialization (Force text)).

Comprueba que el proyecto queda publicado en GitHub.

Ejercicio 5
^^^^^^^^^^^^
En el minuto 12:10 del video te hablarán sobre un flujo de trabajo que involucra la 
creación de ramas.

¿Por qué y para qué se crean las ramas?

En el ejercicio anterior creaste un repo. Ahora adiciona una rama llamada feature1.
Realiza cambios al proyecto en esa rama. Cuando esté satisfecho con los cambios 
realiza un pull request. Como es tu propio proyecto, tu mismo puedes aprobar los cambios
y realizar un merge. AHORA, te presente que al trabajar en equipo otro de tus compañeros 
puede tener la tarea de aprobar e integrar los cambios.


Ejercicio 6
^^^^^^^^^^^^

Ahora salta al minuto 18:10. Verás cómo deshacer errores. Reproduce los pasos 
en tu proyecto.


Ejercicio 7
^^^^^^^^^^^^

En este ejercicio te voy a pedir que hagas de memoria los siguientes pasos.
Si no recuerdas, vuelve a ver el video. El reto es que puedas hacer todos 
los pasos al menos una vez de memoria.

* Crea un proyecto en Unity
* Colócalo bajo control de versión. No olvides los settings y gitignore.
* Publica el proyecto en GitHub.
* Piensa en un cambio simple a tu proyecto.
* Crea una nueva rama. Realiza el cambio.
* Publica la rama a GitHub.
* Realiza un pull request para hacer un merge a la rama principal.
* Crea otra rama.
* Realiza dos o tres cambios. Realiza commits por cada cambio y no olvides 
  hacer push.
* Ahora deshace todos los cambios, uno por uno, haciendo revert al commit inicial.
  comprueba los cambios en el proyecto cada que los hagas.

Ejercicio 8
^^^^^^^^^^^^

Ahora que ya sabes qué es el control de versión, conoces las herramientas
y los flujos de trabajo, te voy a proponer un ejercicio en grupo:


* Habla con otro compañero (o crea otra cuenta de GitHub con la cual puedas
  simular a otra persona)
* Vas a crear un proyecto en Unity y lo colocarás bajo control de versión.
* Luego vas a escribir 3 features que vas a implementar en ese proyecto. 
  Para cada feature sigue las estrategias del flujo de trabajo que aprendiste. 
  No te compliques, la idea es que practiques control de versión, pero sobre 
  una plataforma real de trabajo.
* Ten presente el flujo de trabajo, por tanto, deberías clonar el repositorio, 
  crear ramas de trabajo, hacer commits, realizar pull request, hacer merge, etc.

¿Para qué te pido que hagas esto? Porque en este curso todo el código que escribas 
debe estar bajo control de versión. Trabajar bajo control de versión es un 
estándar en la industria y es una habilidad que deberás dominar para poder trabajar 
de manera efectiva en equipo. ENTONCE vamos a practicar MUCHO.

¿Por qué Unity? Porque es una herramienta muy versátil con la que puedes hacer
muchos tipos de productos interactivos, no solo videojuegos.


Ejercicio 9
^^^^^^^^^^^^

En el ejercicio 1 te pedí que vieras la serie de videos del tutorial 
de git de Gitkraken. Te voy a pedir que mires de nuevo 
`este <https://youtu.be/S03EEusFxoI>`__. ¿Por qué es importante para nosotros?
Por que como tu sabrás cuando hacemos aplicaciones interactivas generamos
varios archivos binarios. Por tanto git lfs será necesario en nuestros 
proyectos. 

Lo primero entonces que tendrás que hacer es instalar el soporte para Git LFS. 
Mira `aquí <https://docs.github.com/en/github/managing-large-files/installing-git-large-file-storage>`__ 
cómo lo harías para tu sistema operativo.

Ahora observa `este <https://youtu.be/LS1VI1Y8WTM>`__ video y `este <https://youtu.be/09McJ2NL7YM>`__ 
otro. Te explicarán cómo usar Unity con git lfs.

Ejercicio 11
^^^^^^^^^^^^^

Sigue las instrucciones del último video y practica la creación de un proyecto en Unity 
con control de versión y lfs.

Ejercicio 12
^^^^^^^^^^^^^

¿Hay otra manera más fácil de hacer todo lo anterior? Si. Unity compró en 2020 la empresa 
que hace PlaticSCM.

Puedes leer al respecto en `este <https://forum.unity.com/threads/announcement-plastic-scm-joins-unity.953252/>`__ 
foro. También encontrarás información reciente en `este <https://youtu.be/PjPK6hxGUFU>`__ video.

.. warning::
    En este curso vamos a utilizar Git y GitHub. Ten en cuenta que todos 
    los repositorios que crees sean públicos para poder hacer seguimiento a tu trabajo.

Ejercicio 13
^^^^^^^^^^^^^^^

En la introducción del curso te hablé de las herramientas de planeación o gestión de 
proyectos. En este curso puedes usar los boards y calendarios de Notion; sin embargo, 
puedes mirar otras herramientas como:

* `Hacknplan <https://hacknplan.com/>`__ 
* `Codecks <https://www.codecks.io/>`__
* GitKraken Boards, GitKraken TimeLines.

.. warning::
    En este curso vamos a utilizar Notion para realizar la gestión y documentación 
    del trabajo del curso.

