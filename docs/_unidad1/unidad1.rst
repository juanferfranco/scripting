Unidad 1. Trabajo en equipo, estructuras de datos y algoritmos
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

Ejercicios y proyectos
------------------------

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

Ejercicio 14
^^^^^^^^^^^^^^^

Antes de comenzar a estudiar algunas estructuras de datos y algoritmos, vamos 
repasar algunos conceptos claves.

Asume que dentro de un método tienes lo siguiente:

.. code-block:: csharp
    :linenos:

    classType variable = new classType();


* ¿En qué parte de la memoria queda almacenada variable?
* ¿En qué parte de la memoria queda almacenado el objeto?
* ¿Cuál es la relación en variable y el objeto que se crea?
* ¿Para qué sirve new?
* ¿Para qué sirve el constructor de una clase?

Ejercicio 15
^^^^^^^^^^^^^^^

Considera el siguiente código donde crearemos dos perros Huskies. 
Uno se llamará Pepe y el otro Tom. El color de los ojos de Pepe 
será azul. A Tom lo crearemos copiando a Pepe y luego le cambiaremos el 
color de los ojos a Tom para que los tenga cafés. Ejecuta el código 
y observa el resultado. Descubre que salió mal. 

.. code-block:: csharp
    :linenos:

      public class Eye
      {
          public string Color;
      }

      public class Husky
      {
          public string Name;
          public Eye RightEye;
          public Eye LeftEye;
          
          public Husky CopyHusky()
          {
              var newDog = new Husky {Name = Name, LeftEye = LeftEye, RightEye = RightEye};
              return newDog;
          }

          public string ToStringDog()
          {
              return String.Format("{0} has a {1} color on his right eye, and a {2} color on his left eye.", Name,RightEye.Color,LeftEye.Color);
          }
      }

      static class MainClass
      {
          public static void Main()
          {
              var pepe = new Husky {Name = "Pepe", LeftEye = new Eye(), RightEye = new Eye()};
              pepe.LeftEye.Color = pepe.RightEye.Color = "blue";
              
              var tom = pepe.CopyHusky();
              tom.Name = "Tom";
              tom.LeftEye.Color = tom.RightEye.Color = "brown";
              
              
              Console.WriteLine(pepe.ToStringDog());
              Console.WriteLine(tom.ToStringDog());
              Console.ReadKey();
      
          }
      }


Ejercicio 16
^^^^^^^^^^^^^^^

Corrige el problema del código anterior.

Ejercicio 17
^^^^^^^^^^^^^^^

En C# ¿Cuál es la diferencia entre un tipo valor y un tipo referencia?

Si no lo sabes, dale una mirada a `este <http://www.albahari.com/valuevsreftypes.aspx>`__ 
artículo hasta antes de la sección Memory Disposal.

Ejercicio 18
^^^^^^^^^^^^^^^^^^

Considera el siguiente programa (tomado de `aquí <http://www.albahari.com/threading/>`__):

.. code-block:: csharp
    :linenos:


    internal static class ThreadTest
    {
        internal static void Main()
        {
            var t = new Thread(WriteY); // Kick off a new thread
            t.Start(); // running WriteY()

            // Simultaneously, do something on the main thread.
            for (var i = 0; i < 1000; i++) Console.Write("x");
        }

        private static void WriteY()
        {
            for (var i = 0; i < 1000; i++) Console.Write("y");
        }
    }

Ejecuta varias veces el programa. ¿Qué observas? ¿Notas que se comporta 
diferente cada vez que lo ejecutas?

En este programa tan simple tenemos en un momento dado dos flujos de instrucciones 
independientes que estás bajo el control del sistemas operativo. Tu programa 
pierde el control sobre los flujos y el sistema operativo hará lo mejor que pueda 
por darles recursos de procesamiento. Para ejecutar un flujo de instrucciones el 
sistema operativo de tu computador crea una abstracción denominada Thread. De esta 
manera el sistema operativo puede asignar recursos de cómputo a tu programa, es 
decir, podrías llegar a tener dos cores de tu CPU ejecutando el programa. Cool! No?

Ya te estarás preguntando, bueno, bueno, y ¿En dónde están los tales flujos de 
instrucciones? El primer flujo comenzará ejecutando el método Main hasta terminar 
con el ciclo for que imprime las ``x``. El segundo flujo ejecutará el método WriteY 
y comenzará cuando el sistema operativo lo decida, luego de que solicites 
iniciar el hilo con ``t.Start();``

Ejercicio 19
^^^^^^^^^^^^^^^^^^

Ahora dale una mirada a este programa (tomado de `aquí <http://www.albahari.com/threading/>`__):

.. code-block:: csharp
    :linenos:
  
    internal static class ThreadTest
    {
        static void Main() 
        {
            new Thread (Go).Start();      
            Go();                         
        }

        private static void Go()
        {
            for (var cycles = 0; cycles < 5; cycles++) Console.Write ('?');
        }
    }

Déjame hacerte unas cuantas preguntas

* ¿Cuál es la diferencia entre una clase y un objeto? 
* ¿Cuál es la diferencia entre un método y un hilo?
* ¿Cuántos flujos de instrucciones puede llegar a tener este programa?
* Parece que en algún momento los hilos están ejecutando el mismo flujo, ¿Qué 
  opinas?
* ¿Los hilos están compartiendo la variable cycles?


Ejercicio 20
^^^^^^^^^^^^^^^

Te prometo que vamos a seguir repasando otros conceptos que aprendiste 
en tu curso de programación y diseño orientado a objetos, pero por ahora, 
vamos a trabajar con estructuras de datos y algoritmos. 

¿Qué son las estructuras de datos? son una manera organizada o estructurada de 
almacenar DATOS ( :) ). 

¿Conoces alguna estructura de datos? (Yo creo que varias: arreglos, listas ...)

¿Qué es un algoritmo? No hay una definición formal, pero lo puedes entender
como un plan detallado y paso a paso para resolver un problema.

¿Conoces ejemplos de algunos algoritmos que se usen en la construcción de aplicaciones 
interactivas?

Ejercicio 21
^^^^^^^^^^^^^

¿Cómo analizar la eficiencia de un algoritmo? ¿Cómo comparo entre dos alternativas?

Utilizaremos la notación Big-O.

Observa `este <https://youtu.be/__vX2sjlpXU>`__ video.

* Si tengo dos computadores, uno más lento y otro más rápido, ¿Tendría dos medidas 
  Big-O diferentes?

* El análisis Big-O toma en cuenta el mejor caso de ejecución del algoritmo, el peor, 
  el promedio?

* Abre un navegador de Internet. Ingresa a 
  `este <https://www.google.com/search?sxsrf=ALeKk01_tmrFvfdDXWpP_byaAHT8nflMpQ%3A1610980569784&ei=2ZwFYIOxL_bj5NoPjoCq8AY&q=f%28x%29+%3D+x+and+g%28x%29+%3D+log2%28x%29&oq=f%28x%29+%3D+x+and+g%28x%29+%3D+log2%28x%29&gs_lcp=CgZwc3ktYWIQAzoECAAQR1C1LljPc2DSdGgAcAJ4AIABsQGIAa0EkgEDMC40mAEAoAECoAEBqgEHZ3dzLXdpesgBCMABAQ&sclient=psy-ab&ved=0ahUKEwjDgeik2qXuAhX2MVkFHQ6ACm4Q4dUDCA0&uact=5>`__ 
  sitio. Observa la gráfica y la expresión matemática ``f(x) = x and g(x) = log2(x)``. Este 
  recurso puede servirte mucho para visualizar de manera gráfica la notación Big-O entre 
  dos algoritmos.

* ¿Qué algoritmo crees que sea mejor uno con O(1) o con O(n) ?

Ejercicio 22
^^^^^^^^^^^^^

En este curso vas a trabajar con C#. Ingresa a 
`este <https://docs.microsoft.com/en-us/dotnet/standard/collections/#algorithmic-complexity-of-collections>`__ 
sitio. Mira por ejemplo la fila ``List<T>.Add`` observa que tienes dos medidas
Amortized: ``O(1)``	y Worst Case:	``O(n)``. Amortized es el promedio. 

¿Qué quiere decir lo anterior? Mira, en el caso de una List, la operación Add puede tomar 
solo un paso siempre que tengas memoria disponible en la lista; sin embargo, si recuerdas, 
una List es una estructura de datos dinámica. Por tanto, si no hay espacio para hacer el 
Add toca reservar más memoria, crecer la List. Tu dirás, eso es una operación. 
¿Entonces de donde salen las N para convertirse en O(n)? Debes copiar TODOS los datos de la 
lista vieja a la nueva (que tiene más memoria). Si tienes N datos, debes hacer N copias.

Dale de nuevo una mirada a `este <https://docs.microsoft.com/en-us/dotnet/standard/collections/>`__ 
sitio y déjalo en tus favoritos para futuras consultas.

Ejercicio 23
^^^^^^^^^^^^^

Comencemos con los arrays. Mira `estos <https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/>`__ 
ejemplos.

En notación Big-O ¿Cuál sería el costo de acceder a un elemento del arreglo?

Toma el ejemplo de la página que te compartí. Añade un método y sus 
`sobrecargas <https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/member-overloading>`__ 
para imprimir todos los items de cada arreglos. ¿Todos te funcionaron? ¿Alguna excepción? ¿Por qué?

Ejercicio 24
^^^^^^^^^^^^^

Ahora si vamos a practicar un poco más. Ya sabrás que una de las desventajas de los 
arreglos es que son estáticos. Una vez creados, no puedes cambiar su tamaña. Entonces te 
propongo que crees una Lista. Tu me dirás, profe, pero eso ya existe en C#. Tienes toda la razón, 
pero en esta Unidad vamos a aprovechar para calentar motores y repasar tus conceptos de 
programación.

Vamos a tomar el código de `este <https://github.com/PacktPublishing/-C-8-Data-Structures-and-Algorithms/tree/master/Section%202/Arrays>`__ 
repositorio público.

* Crea un proyecto C# en tu editor favorito (yo uso `rider <https://www.jetbrains.com/rider/>`__) 
* Del repositorio público copia el archivo `ArrayList.cs <https://github.com/PacktPublishing/-C-8-Data-Structures-and-Algorithms/blob/master/Section%202/Arrays/ArrayList.cs>`__ 
* Del repositorio público copia el archivo `Program.cs <https://github.com/PacktPublishing/-C-8-Data-Structures-and-Algorithms/blob/master/Section%202/Arrays/Program.cs>`__ 
* Del repositorio público copia el archivo `Extensions.cs <https://raw.githubusercontent.com/PacktPublishing/-C-8-Data-Structures-and-Algorithms/master/Section%202/Arrays/Extensions.cs>`__ 

No olvides adaptar el namespace de cada archivo al que definiste en un tu proyecto.

* Lee el código y analiza en detalle. BUSCA todos los elementos sintácticos que no 
  entiendas.
* Ejecuta el programa ¿Cuál de las pruebas aplicaste?
* ¿Ya viste que hay otras dos pruebas para realizar? Realiza las pruebas y compara los resultados.
* Recuerda que estamos repasando, por tanto en la práctica se espera que uses
  la clase `List<T> <https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1?view=netframework-4.7.2>`__, pero lo importante es que notes que List es un arreglo dinámico, similar,
  al que está implementado en la clase ArrayList. 

Te haré algunas preguntas relacionadas con el código en ArrayList.cs:

* ¿En ArrayList<T> qué significa <T> ? ¿Qué utilidad le ves a esto?
* ¿Al crear un objeto de tipo ArrayList de qué tamaño es el arreglo inicial?
* En el método ExpandStorage por qué se hace ``new T[_storage.Length * 2];``

Ahora te pido que abras Program.cs y observes esta línea: ``customArrayList.PrintElements();``. 
En customArrayList estamos almacenando una referencia a un objeto tipo ArrayList<int>. 
Busca en la clase ArrayList el método PrintElements. ¿Lo encontraste?

Tienes razón, no encontraste el método en ArrayList.cs. Resulta que PrintElements es 
lo que se conoce como un `extension-method <https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods>`__.

Lee la definición:

Extension methods enable you to "add" methods to existing types without creating a 
new derived type, recompiling, or otherwise modifying the original type. Extension 
methods are static methods, but they're called as if they were instance methods on 
the extended type.

¿Cómo crees que estos métodos funcionen? Te ayudo un poco. Considera este código:

.. code-block::
    :linenos:

    classType varRef = new classType();
    varRef.method();

¿Qué es method? Pues son simplemente unas instrucciones que debe ejecutar 
la CPU del computador. ¿Sobre qué datos se aplicarán esas instrucciones? Sobre 
los datos del objeto cuya dirección está almacenada en varRef. Si lo piensas 
bien, al hacer ``varRef.method();`` es como si le pasaras a method la dirección 
del objeto. Ahora te pregunto. ¿Cómo llamarías a un método estático definido en 
la clase classType?

.. code-block::
    :linenos:

    classType.StaticMethod();

De nuevo ¿Qué es StaticMethod? Son unas instrucciones que debe ejecutar la CPU 
de mi computador. ¿Sobre qué datos actúan esas instrucciones? Creo que ya te diste 
cuenta. Como no estoy pasando la dirección de un objeto al método no queda más de 
otra que el método actúe sobre los datos ESTÁTICOS definidos en la clase classType 
y es por eso que en un método estático solo puedes usar variables estáticas. 
Si usaras variables NO estáticas en el método, estas variables serían 
las de ¿Cuál objeto? COOL!!!

De nuevo: ``customArrayList.PrintElements();``. Vamos a verla en contexto:

.. code-block:: csharp
    :linenos:

    ArrayList<int> customArrayList = new ArrayList<int>();
    customArrayList.Add(4);
    customArrayList.Add(5);
    customArrayList.Add(6);
    customArrayList.PrintElements();

Profe!!!!!!!!!!!!! me estás enredando. Me habías dicho esto: ``customArrayList`` es 
una variable que almacena la dirección de un objeto de tipo ArrayList<int>. Luego,
voy a buscar PrintElements y no lo veo. Pero lo encontré en Extensions.cs:

.. code-block:: csharp
    :linenos:

    public static void PrintElements<T>(this ArrayList<T> arrayList)
        {
            if (null == arrayList || arrayList.Length == 0)
            {
                Console.WriteLine("[]");
                return;
            }
    .
    .
    .

Profe, eso es un método estático. Me acabas de decir que no lo puedo llamar 
sobre la referencia a un objeto: ``customArrayList.PrintElements();`` ¿Y entonces?
(ESPACIO PARA LLANTO!!!)

Mira la declaración del método:

.. code-block:: csharp
    :linenos:

    public static void PrintElements<T>(this ArrayList<T> arrayList)

¿Ves la palabra this? Pues esto es un truco de los creadores del lenguaje para
permitirnos tener Extension methods. La idea es que le pasemos al método 
la dirección del objeto sobre el cuál queremos aplicar las instrucciones 
que estamos definiendo. Mira de nuevo en contexto:

Así llamas al método:

.. code-block:: csharp
    :linenos:

    ArrayList<int> customArrayList = new ArrayList<int>();
    customArrayList.Add(4);
    customArrayList.Add(5);
    customArrayList.Add(6);
    customArrayList.PrintElements();

Así lo declaras:

.. code-block:: csharp
    :linenos:

    public static void PrintElements<T>(this ArrayList<T> arrayList)

¿Ya te diste cuenta? Mira que al llamar ``customArrayList.PrintElements();`` no 
pasas ningún parámetro. Entonces ahí está el truco que están aplicando:
almacenar en la variable ``arrayList`` la dirección en memoria, que está 
en customArrayList, del objeto. UFFFFFFF. Interesante.

