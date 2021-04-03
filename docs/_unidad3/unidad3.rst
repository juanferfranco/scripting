Unidad 3. Depuración, perfilamiento y optimización
=========================================================

Introducción
--------------

En esta unidad vas a estudiar alguna técnicas de depuración 
que te permitirán identificar posibles errores en tu código. Adicionalmente, 
varás algunas técnicas de perfilamiento y optimización de código.


Propósito de aprendizaje
^^^^^^^^^^^^^^^^^^^^^^^^^^

Conocer algunas técnicas de depuración, perfilamiento y optimización 
del código que describe el comportamiento de una aplicación interactiva.

Temas
^^^^^^

* Técnicas de depuración.
* Perfilamiento y optimización.

.. 
    Ejercicios 1 a 7: 7 horas. Semana 1 - parte de la 2
    Ejercicio 8 y 9: 11 horas: semanas 2 y 3.

Ejercicios y proyecto
-----------------------

Ejercicio 1: depuración - observar (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Lo primero que vas a hacer es aprender a depurar un programa. Para hacerlo tendrás 
que conectar el depurador de tu entorno de desarrollo al proceso que está corriendo 
el editor de Unity.

Observa detenidamente este `video <https://youtu.be/y3kqIlLzIig>`__.

* ¿Para que sirve un breakpoint?
* ¿Cuál es la diferencia entre step into y step over?
* ¿Cuál era el problema con el primer ejemplo?
* ¿Cuál era el problema del segundo ejemplo?

Ejercicio 2: depuración - reproducir (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Ahora que ya viste los ejemplos del video, trata de observalo de nuevo pero esta vez 
reproduce los ejemplos y las situaciones de error en tu computador.

Ejercicio 3: depuración - logs/introducción (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Utilizar Logs en tu aplicación puede ser de mucha ayuda a la hora de desarrollar. En este 
ejercicio te voy a pedir que leas `esta entrada <https://docs.unity3d.com/Manual/class-Debug.html>`__ 
del manual de Unity.

* ¿Que diferencia ves en la consola entre un log normal, un log de error y un log de advertencia?
* La clase Debug tiene más métodos además de log. Lee qué otros métodos tienes disponibles.

Ejercicio 4: depuración - logs/experimenta (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

La clase `Debug <https://docs.unity3d.com/ScriptReference/Debug.html>`__ tiene varios 
ejemplos de cómo puedes usar algunos métodos estáticos para depurar tu programa.

Experimenta reproduciendo algunos de esos ejemplos.

Ejercicio 5: depuración - logs/enriquecidos (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

El método `Log <https://docs.unity3d.com/ScriptReference/Debug.Log.html>`__ te permite 
utilizar texto enriquecido. Lee algunas posibilidades de este texto enriquecido 
`aquí <https://docs.unity3d.com/Packages/com.unity.ugui@1.0/manual/StyledText.html>`__.

Ahora observa `este video <https://youtu.be/S2LNvvcVgRo>`__ para que veas en acción 
lo anterior. Ten presente que el autor utiliza Rider, pero tu puedes utilizar la consola 
de Unity e ir y venir entre la consola y el editor de Visual Studio.

Ejercicio 6: depuración - logs/enriquecidos (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Observa de nuevo el video anterior, pero esta vez 
`descarga el código <https://www.patreon.com/file?h=29898031&i=4427918>`__ 
y reproduce lo que viste en el video.

Ejercicio 7: perfilamiento - introducción (2)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Cuando desarrollas aplicaciones interactivas es importante que analices y depures 
tu aplicación para que te asegures que está libre de errores y corre adecuadamente 
en la plataforma deseada. Unity te ofrece una herramienta conocida como el ``PERFILAR``. 

¿Qué es un perfilador (`profiler <https://docs.unity3d.com/Manual/Profiler.html>`__)? 
Es una herramienta que te permite obtener y visualizar información para ANALIZAR cómo se 
comporta tu aplicación en el tiempo en términos de uso de CPU, memoria, renderización 
y audio.

Tu puedes lanzar esta herramienta desde el editor, pero ten en cuenta que podrás 
conectarla a tu dispositivo mediante una conexión de red, es decir, puedes perfilar 
una aplicación interactiva que no está corriendo en el mismo dispositivo donde corres 
el profiler. Así mismo, podrás correr una aplicación desde el editor de Unity y perfilar 
una aplicación en desarrollo.

¿Por qué es importante perfilar una aplicación? Porque esto permite encontrar posibles 
errores u oportunidades de OPTIMIZACIÓN.

Observa el `siguiente video <https://youtu.be/uXRURWwabF4>`__ que introduce las posibilidades 
de profiling que tiene Unity.

Ejercicio 7: perfilamiento - análisis (6)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vuelve a observar el video anterior, pero esta vez analiza las siguientes preguntas:

#. En el video mencionan que el profiler es un instrumentation-based profiler y no un sample-based. 
   ¿Cuál es la diferencia?
#. En el video indican que es posible hacer profiling de un dispositivo móvil o una consola.
   ¿Cómo es posible hacer eso?
#. ¿Qué módulos tiene el profiler? ¿Es posible ver datos solo de algunos módulos?
#. Cuando se perfila la CPU y se usa el módulo jerárquico ¿Qué información puedes ver allí?
#. Considera que tu aplicación está corriendo a muy pocos frames por segundo porque posiblemente 
   hay un método que está tomando mucho tiempo en ejecutarse. ¿Para qué crees que pueda 
   servirte ver el comportamiento de la CPU en modo jerárquico en este caso?
#. Explica a qué se refiere el concepto de Budget (presupuesto) en términos de performance 
   en una aplicación interactiva.
#. En términos del concepto de Budget ¿Por qué crees que es más complicado hacer aplicaciones 
   interactivas en realidad virtual?
#. ¿Cuál es la estructura de un frame? Si buscas optimizar, es decir, hacer que una parte 
   del frame se ejecuta más rápido ¿Qué parte puedes mejorar?
#. ¿Qué es una GPU y qué función cumple en la ejecución de tu aplicación interactiva?
#. En la estructura de un frame de CPU ¿Cuál es la función del rendering?
#. ¿Qué hace que la GPU tenga que ``ESPERAR`` para poder renderizar un frame de tu aplicación?
#. ¿Qué significa una estructura de frame CPU-bound? 
#. ¿Qué significa una estructura de frame GPU-bound?
#. ¿Qué es Gfx.WaitForPresent (`Gfx.WaitForPresentOnGfxThread <Gfx.WaitForPresentOnGfxThread>`__)? 
#. ¿Qué quiere decir cuando este valor es muy alto?
#. La vista timeline en el profiler para qué sirve?
#. En el profiler se puede ver que el editor de Unity toma mucho tiempo en ejecutarse ¿Por qué 
   esto no es importante a la hora de perfilar una aplicación?
#. ¿Qué debes hacer si quieres sacar al editor de Unity del profiler? es decir, que no 
   veas información de este.
#. ¿Qué es WaitingForTargetFPS?
#. ¿Una aplicación puede configurar el 
   `FPS deseado <https://docs.unity3d.com/ScriptReference/Application-targetFrameRate.html>`__ 
   de una aplicación interactiva?
#. Explica el concepto de Screen tearing.
#. ¿Para qué sirve el Vsync?
#. Explica cómo funciona Vsync
#. Piensa en esto. Considera que en una aplicación móvil quieres alcanzar 60 fps; sin embargo, 
   el PlayerLoop toma 22 ms en ejecutarse. ¿Por qué los FPS serán 30 fps y no 45 fps?
#. En la vista TimeLine ¿Qué son los Jobs?
#. Qué significa que las físicas en Unity no son multi-hilo (multi-threaded)?
#. ¿Por qué se menciona en el video que los Jobs están sub-utilizados?
#. ¿Qué es el garbage collector?
#. ¿En qué parte de la memoria de un PROCESO vive la basura?
#. Recuerdas que en la Unidad 1 hablamos de la zona de memoria donde viven los objetos, ¿Cuál 
   es?
#. ¿Por qué en el TimeLine se ven PICOS en la CPU relativos al Garbage Collector?
#. ¿Cómo puedes hacer para saber qué parte del código está generando la ``basura``?
#. ¿Por qué crees que es importante mantener referencias de los objectos que vas 
   a usar mucho en vez de estar creando objetos constantemente?
#. ¿Qué significa un Garbage Collector incremental?
#. ¿Para qué sirve el Profiler Analyzer?
#. ¿Cuál es la diferencia entre el modo Single y el modo compare en el profiler analyzer?
#. ¿Para qué sirve el frame debugger?
#. En el video recomiendan unos momentos ideales para realizar profiling. Indica 
   cuáles o cuándo son esos momentos recomendados.
#. ¿Qué significa realizar un profiling en escenarios reales?
#. ¿Por qué es importante realizar un profiling cuando el juego lleva un rato 
   corriendo?
#. ¿Para qué crees que puede ser útil la clase Profiler.logFile de Unity?
#. ¿Qué ventajas en términos de optimización el uso del patrón OBJECT POLLING?
#. ¿Qué quiere decir la expresión Spreading the load in time?
#. Si tienes un algoritmo que toma mucho tiempo en ejecutarse, considerando la pregunta 
   anterior ¿Qué deberías hacer?

.. 
    Hasta aquí van 7 horas de trabajo

Ejercicio 8: perfilamiento y optimización caso de estudio 1 / Job System (1)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En este ejercicio vas a estudiar un caso donde se recurre al Job System para 
optimizar la aplicación interactiva.

Se trata de un simulador de una ciudad que cuenta con 65 edificios. Cada 
edificio tiene 150 pisos (aunque puedes modificar la cantidad) y en cada piso 
pueden vivir entre 20 a 500 inquilinos (tenants). Para cada edificio se 
realiza el cálculo de su consumo de energía. Esta operación es intensiva en el 
uso de CPU, como te darás cuenta. Por tanto, esta aplicación será CPU-bounded o 
ligada a la CPU. Ten en cuenta que otras aplicaciones son I/O-bounded, es decir, 
la aplicación debe esperar a que se complete una operación de entrada-salida (I/O). 
La técnica de optimización que verás en este ejercicio te sirve para lidiar 
con problemas CPU-bounded. Cuando tengas escenarios I/O-bounded tendrás que 
recurrir a otras técnicas; sin embargo, el mecanismos de fondo es usar ``Threads``.

¿Quieres volver a repasar el concepto de Threads que viste en la Unidad 1?
Te dejo por `aquí <https://youtu.be/Iwj0_p0bLpc>`__ un video corto para que lo hagas.

Por lo pronto te voy a pedir SOLO VER `este video <https://youtu.be/3o12aic7kDY>`__ donde 
se presenta el caso de estudio. En el siguiente ejercicio vas a analizar a fondo 
el caso.

Ejercicio 9: perfilamiento y optimización caso de estudio 1 / Job System (3)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

El código para analizar el proyecto lo tienes `aquí <https://www.patreon.com/posts/34702445>`__.

#. Crea un proyecto en Unity 2019.4 LTS 
#. Antes de importar el código que descargaste incluye los paquetes Mathematics, Collections 
   y Jobs usando el Packet Manager. No olvides habilitar la opción mostrar los paquete 
   en preview (Show preview packages).
#. Importa el paquete de código que descargaste.
#. Carga la escena que está en el directorio Start Here. Esta escena te permitirá 
   observar la primera parte del video. Verifica el problema usando el profiler.
   Deberías observar una figura similar a esta:

   .. image:: ../_static/ExJobProblem.png
      :alt:  captura del profiler con el problema
      :scale: 50%
      :align: center

#. ¿Qué parte del código tiene el problema? ¿Cuál es el problema? (Observa 
   la duración del PlayerLoop y la franja azul)
#. Nota en la figura que el Main Thread está muy ocupado mientras que los 
   Workers están básicamente desocupados. ¿Y si lo pones a trabajar? Eso 
   lo puedes hacer con el Job System.
#. ¿Qué es el `C# Job system <https://docs.unity3d.com/Manual/JobSystem.html>`__?
#. Para definir un Job se utiliza una struct. ¿Cuál es la razón que indican el video?
#. Nota que se implementa la interfaz 
   `IJobParallelFor <https://docs.unity3d.com/Manual/JobSystemParallelForJobs.html>`__. 
   ¿Qué relación hay entre esta interfaz y los Threads?
#. En el minuto 5:28 se crea un nuevo MonoBeHaviour llamado BuildingManager que tendrá 
   una lista para almacenar las referencias a todos lo edificios y adicionalmente le dirá 
   al Job System de Unity que por favor le reparta trabajo a los worker threads que tiene 
   disponibles:

   .. code-block:: csharp
   
      private void Update()
      {
        var job = new BuildingUpdateJob();
        var jobHandle = _job.Schedule(buildings.Count, 1);
        jobHandle.Complete();
      }
    
   ¿De qué tipo es la variable job? ¿Esa variable vive en el stack o en el heap?
#. En el código anterior el método Complete() espera a que todos los Jobs terminen. 
   ¿Qué crees que ocurra si el trabajo que tienen que hacer los Jobs es muy largo?
   ¿Qué harías para lidiar con lo anterior?
#. Observa que, en este caso, un Job (la estructura de datos) está definido por dos 
   partes: un arreglo de datos y el código que se ejecutara sobre cada item del arreglo 
   de datos. Mira el código que actuará sobre cada dato:

   .. code-block:: csharp
   
      public void Execute(int index)
      {
            var data = BuildingDataArray[index];
            data.Update();
            BuildingDataArray[index] = data;
      }
   
   ¿Por qué luego de actualizar a data (data.Update()) se copia de nuevo a data 
   en el arreglo? Si necesitas repasar te dejo 
   `aquí <https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/struct>`__ 
   un enlace.
#. En el minuto 5:28 se creó BuildingManager y en el método update se escribió código 
   para solicitarle al Job system de Unity que le diera trabajo a los worker threads: 
   
   .. code-block:: csharp
   
      private void Update()
      {
            var job = new BuildingUpdateJob();
            var jobHandle = _job.Schedule(buildings.Count, 1);
            jobHandle.Complete();
      }

   Nota que hasta este punto BuildingUpdateJob no tiene los datos almacenados sobre los 
   cuales cada worker thread ejecutará el método Execute:  

   .. code-block:: csharp
   
        private void Update()
        {
                // 1
                var buildingDataArray = new NativeArray<Building.Data>(buildings.Count, Allocator.TempJob);
                
                // 2
                for ( var i = 0; i < buildings.Count;i++)
                {
                    buildingDataArray[i] = new Building.Data(building[i]);
                }

                // 3
                var job = new BuildingUpdateJob
                {
                    BuildingDataArray = buildingDataArray;
                }
                var jobHandle = _job.Schedule(buildings.Count, 1);
                jobHandle.Complete();

                // 4
                buildingDataArray.Dispose();
        }
    
   Explica qué hacen las líneas marcadas con 1,2,3 y 4. En la marca 3 del código
   estás haciendo una copia por valor o por referencia?
#. Esta no es una pregunta. Pero quería contarte que en la parte final de la unidad 
   te dejé un enlace con material que ven tus compañeros de experiencias sobre aplicaciones  
   interactivas I/O bounded. 

.. 
    Hasta aquí van 9 horas de trabajo

.. 
    Este segundo caso le añadiría 5 horas de video y 4 de análisis
    para completar 18 horas de trabajo en este Unidad.

Ejercicio 10: perfilamiento y optimización / caso de estudio (18)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. warning:: EJERCICIO LARGO!

   Este último ejercicio de la unidad es largo. Te tomará aproximadamente 
   9 horas en completarlo. Ten paciencia y distribuye tu tiempo. Te recomiendo 
   que lo hagas en una semana y media.

   El ejercicio se basa en un proyecto de Unity learn. Primero 
   tendrás que leer unos fundamentos teóricos y luego realizarás una serie de 
   RETOS guiados para ir optimizando el proyecto.

   Lo primero que debes hacer es descargar los archivos del proyecto. Es sobre 
   este proyecto que realizarás todos los RETOS.

   Al final de todo el proyecto verás una grabación donde se hace la optimización 
   de este proyecto en VIVO. Si gustas podrías comenzar por aquí y luego 
   volver a revisar al final los videos para repasar.

En este caso de estudio vas a realizar uno de los proyectos de Unity learn 
relacionado con el asunto de esta unidad. La idea es que practiques de nuevo 
todo lo que hemos estudiado. 

El enlace al proyecto esta 
`aquí <https://learn.unity.com/project/optimizing-for-performance-2019-3>`__.

Puedes bajar el código del proyecto 
`aquí <https://connect-prd-cdn.unity.com/20200319/9d88a529-d7d4-4f3e-bfa6-9af72294a535/LearnLive_OptimizationAssets.zip?_ga=2.126028237.1943325220.1617376423-1653210251.1613099991>`__.

Para usar el código crea un proyecto 3D en Unity 2019.4LTS e importa el packet anterior.

No olvides ir documentando toda la experiencia. Verás como varios de los conceptos 
fundamentales que hemos abordado en el curso se aplican y analizan. Además de ir 
documentando tu experiencia y resultados del proyecto, te voy a dejar algunas 
preguntas para que reflexiones un poco más sobre los conceptos. TEN PRESENTE que 
además verás conceptos nuevos que no solo se aplican a Unity sino a cualquier 
otro tipo de motor. Este ejercicio es importante y por ello que le dedicaremos 
9 horas de trabajo, es decir, semana y media.

#. ¿Por qué la memoria que se usa en el stack se libera automáticamente?
#. ¿Por qué se dice que le memoria en el heap es manejada?
#. ¿Por qué es más lento el manejo de memoria en el heap?
#. Explica de nuevo en pocas palabras el concepto de Object pooling y explica 
   por qué permite optimizar la recolección de basura por parte del Garbage 
   collector.
#. ¿Por qué puede ser mejor utilizar GetComponent en el método Start o Awake en 
   vez de Update?
#. ¿Cuándo deberías utilizar LateUpdate en vez de Update?
#. ¿Cuándo deberías utilizar FixedUpdate en vez de Update?
#. ¿Cómo se comparan las corutinas con las máquinas de estado?
#. Si tienes una operación MUY MUY larga que te está tomando varios frames 
   ¿Qué tienes que hacer para poder implementar esa operación con una corutina?
#. En `esta parte <https://learn.unity.com/tutorial/introduction-to-optimization-with-unity-2019-3?uv=2019.3&projectId=5e71011aedbc2a07f42bd138#5e1da6a0edbc2a3da3a31f09>`__ 
   del proyecto hay un ejemplo de código que podría optimizarse. 
   Muestra cómo podrías hacerlo.
#. ¿Qué es el lenguaje CIL?
#. ¿Qué hace un ahead of time compiler (AOT)?
#. ¿Qué hace un Jit compiler?
#. ¿Cuál es la diferencia entre el AOT y el Jit compilers?
#. ¿Cuál es la relación entre el lenguaje C++ y el motor de Unity?
#. ¿Qué es código manejado?
#. ¿Qué es el managed run time?
#. Enumera y explica las posibles causas para que un código no se ejecute de manera 
   eficiente.
#. ¿Qué es `reflection` y por qué es tan costosa en términos de desempeño?
#. ¿Por qué el uso de find es costo en términos de desempeño? ¿Qué podrías hacer 
   para minimizar su impacto en la aplicación?
#. ¿Por qué no deberías tener métodos Update vacíos?
#. ¿Por qué usar Camera.main es costoso en términos de desempeño y qué podrías 
   hacer para minimizar este costo?
#. Explica y muestra un ejemplo del concepto Culling.
#. Explica a qué se refiere el concepto de LOD o level of detail.
#. Enumera y explica varias estrategias que permitan minimizar el impacto del Garbage 
   collector.
#. ¿Qué síntomas en la ejecución de tu código pueden ser indicios de problemas 
   con el Garbage collector? ¿A qué se puede deber este síntoma?
#. ¿Cuál es la diferencia entre el manejo de memoria manual y el Garbage collector?
#. ¿A qué se refiere el concepto de Allocated Memory?
#. ¿A qué se refiere el concepto de Deallocated Memory?
#. ¿Qué significa el concepto IN SCOPE relacionado con las variables?
#. Explica cómo es el proceso de allocate y deallocate memoria del STACK.
#. Explica cómo es el proceso de allocate y deallocate memoria del HEAP.
#. ¿Cada cuánto se ejecuta el Garbage collector?
#. ¿Qué puede hacer que el Garbage collector tome mucho tiempo en ejecutarse? 
   ¿Crees que esto puede ser grave o no para tu aplicación? ¿Por qué?
#. ¿Qué es el concepto de heap fragmentation?
#. ¿Qué tipo de variables se almacenan en el heap y en el stack? Muestra ejemplos.
#. Enumera y explica tres ESTRATEGIAS con las cuales puedes reducir el impacto del 
   Garbage collector.
#. Explica y da ejemplos de la técnicas Caching.
#. ¿Por qué no deberías asignar memoria en métodos que sean llamados frecuentemente?
#. Explica le técnica Clearing collections.
#. ¿Por qué es útil en términos de memoria la clase StringBuilding?
#. Explica y muestra un ejemplo del concepto de Boxing.
#. ¿Por qué deberías evitar el Boxing?
#. ¿Qué es el concepto de CLOSURE?
#. Explica los pasos que debe realizar la CPU con cada frame que se renderiza.
#. ¿Qué significa el término Draw Call?
#. ¿Qué significa el término Batching.
#. Explica los pasos que debe realizar la GPU con cada frame que se renderiza.
#. ¿Qué significa que el PIPELINE de renderización sea ineficiente, es decir, qué 
   puede hacer qué no sea eficiente?
#. ¿Cuál es el `flujo de trabajo <https://learn.unity.com/tutorial/challenge-optimize-the-project-scripts?uv=2019.3&projectId=5e71011aedbc2a07f42bd138#5e734280edbc2a001f390afd>`__ 
   que debes seguir para optimizar un proyecto?
#. ¿A qué se refiere el término Global Illumitation?
#. Cuando estés realizando el RETO Bake the scene lighting ten presente que en el paso 
   2 cuando selecciones Generate Lighting esto tardará un buen rato. Todo dependerá de 
   tu computador.
#. ¿Qué significa la técnica occlusion culling? ¿Para qué sirve? ¿Qué hace?
#. ¿Por qué la técnica no es sirve cuando el contenido de una escena se genera en 
   tiempo real?
#. ¿Para qué tipo de proyectos la técnica es ideal? 
#. ¿El proyecto que estás optimizando es buen candidato según lo anterior?

.. warning:: OPCIONAL (tal vez en vacaciones o cuando tengas tiempo libre)

   Te voy a dejar aquí otros enlaces muy interesantes. TEN PRESENTE 
   que varias de las tecnologías relacionadas con Dots están en etapa experimental, 
   en particular la parte que llaman actualmente ENTITY (antes ECS).

   * `Mejoras al profiler <https://youtu.be/oWaBW8A1pmQ>`__.
   * `Sobre el Job system <https://youtu.be/3o12aic7kDY>`__.
   * `Tutorial sobre el Job system <https://youtu.be/C56bbgtPr_w>`__.
   * `Conceptos básicos <https://youtu.be/HVzSTEIAXi8>`__ de Dots.
   * `Sobre Dots <https://youtu.be/Z9-WkwdDoNY>`__.
   * `PathFinding in Dots <https://youtu.be/1bO1FdEThnU>`__.
   * `Curso avanzado <https://learn.unity.com/course/performance-and-optimisation>`__ 
     sobre profiling y optimización.
   * Los escenarios I/O-bounded son muy comunes en las aplicaciones interactivas 
     que construyen tus compañeros de Experiencias Interactivas ya que ellos deben 
     integrar a la aplicación `DISPOSITIVOS EXTERNOS`. Si tienes curiosidad puedes 
     aprender un poco más acerca de esto 
     `aquí <https://sensores1.readthedocs.io/es/latest/_unidad4/unidad4.html>`__.
   * `Conferencia de Unity <https://youtu.be/kwnb9Clh2Is>`__ en el GDC del 2018 donde 
     explican algunos asuntos relativos al Job system, entre otros.
   * `Conferencia introductoria <https://youtu.be/epTPFamqkZo>`__ sobre profiling y 
     optimización en Unity.