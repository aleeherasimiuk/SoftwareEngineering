# Estimaciones de Software

Elementos susceptibles de estimación:

- Tamaño?
- Esfuerzo?
- Tiempo?
- Costo?

> Ejemplo del Pintor:

Tengo una pieza para pintar, ¿Cuánto cobras? ¿Cuanto tardarías?

Lo primero que pregunta el pintor son las medidas de la pieza

De la misma manera es conveniente “medir” el tamaño del software que tenemos que realizar.

Otras variables que afectan a la estimación del pintor, el estado de la pared, si hay ventanas, si es trabajo de altura, ¿Es un trabajo que potencialmente se puede hacer con muchas personas?.

La complejidad también es parte del tamaño cuando se estima el tamaño en la construcción de software.
> 

Son pocas las veces que nos preguntamos:

- ¿Cuál es el tamaño de lo que tenemos que construir?
    - Esta pregunta debería ser la primera para poder pasar a preguntarnos sobre el tiempo o el costo.
    - La realidad parece indicarnos que el tamaño se calcula informalmente y solo formalizamos el esfuerzo, ventana y costo.
    - Debemos ser lo más rigurosos posibles con la estimación del tamaño

## Tiempo vs Esfuerzo

Son dos cosas completamente diferentes.

¿El tiempo realmente se estima? ¿O es más bien una consecuencia de la estimación del esfuerzo?

El calendario es una consecuencia de haber tratado al esfuerzo luego de planificar con el staff, los recursos, etc.

## Procedimiento de Estimar

- Buscar y entender las features y requerimientos
- Asignar un tamaño
- Mediante alguna técnica transformar el tamaño a esfuerzo en hs/hombre
- Evaluar un costo a partir del esfuerzo
- Por último la duración

![Untitled](Estimaciones%20de%20Software%204dc11840c1cb43d1b567e94b9037d33a/Untitled.png)

> Pensar que si el pintor nos dijo en un inicio que iban a ser 8hs, y podía ser resuelto en 1 día, si me dice que solo puede por las mañanas, el tamaño y el esfuerzo sigue siendo el mismo, pero el problema que el pintor tuvo al asignar recursos (staffear), cambió únicamente el calendario, ahora tardaría 2 días. O a lo sumo podría agregar otra persona y resolverlo en el  mismo día, bajo el mismo precio. (Si la tarea permite paralelización)

Luego puede ajustarse un poco si hubo algún imprevisto, por ejempo si se agrega otra persona, si bien el esfuerzo y el costo sería el mismo, capaz que se necesita pagar un seguro de vida extra.
> 

# LO QUE SE ESTIMA ES EL TAMAÑO

# ¿Por qué fallan las estimaciones?

- Optimismo
- Estimaciones informales (”estomacales”)
- No hay historia
- Mala definición del alcance
- Novedad | Falta de experiencia
- Complejidad del problema a resolver
- No se estima el tamaño
- Porque la estimación fue buena pero cuando empieza el proyecto:
    - Mala administración de los requerimientos
    - No hay seguridad y control
    - Se confunde progreso con esfuerzo

## ¿Cómo puedo saber si mi estimación fue correcta o no fue correcta?

- Al final del proyecto
- La diferencia entre el esfuerzo que me incurrió y el que estimé (No hablo de tiempo)

> Ejemplo con la visión del usuario (importante el costo y calendario)

Tengo que hacer un viaje a Mar del Plata, quiero llegar con un tanque de 55litros y quiero tardar 5 hs para hacer 400km

Si gasté 4 tanques y tardé 2 días.

Qué falló?

La estimación suponía 5hs en el auto.

Mala ejecución?. Si fui hasta mar del plata en marcha atrás, y tardé 2 días yendo a 45km/h no es culpa de la estimación, pero lo ejecuté mal.

Cosas que no tuve en cuenta:
Fecha pico, día de lluvia, manifestaciones, etc.
> 

## Nivel de incertidumbre

- El cono de la incertidumbre define niveles estadísticos predecibles de la incertidumbre de las estimaciones en cada etapa del proyecto
- Cuanto más **refinada la definición**, más **exacta** será la **estimación**

![Untitled](Estimaciones%20de%20Software%204dc11840c1cb43d1b567e94b9037d33a/Untitled%201.png)

Uno tiene que forzar que el cono se vaya poniendo angosto, eliminando todas aquellas variables de incertidumbre, cosas no definidas, supuestos que tengo que tener en cuenta, requerimientos inestables y pocos claros, etc.

## Tips para estimar

- Diferenciar entre estimaciones, objetivos y compromisos
- Asociar a las estimaciones un % de confiabilidad
- Es recomendable presentar las estimaciones como rangos en lugar de un único valor
- Siempre presentar junto con la estimación, los supuestos que se tuvieron en cuenta para llegar a la misma.
- Tener presente la Ley de Parkinson: “Toda tarea se expande hasta ocupar el tiempo que tiene asignado”
- Considerar todas las actividades relacionadas al desarrollo de software, no solamente codificación y testing (análisis, diseño, actividades de SCM, testing, etc)
- No asumir que solo por el paso del tiempo y de las fases de un proyecto se avanca con menor incertidumbre en las estimaciones (Cono de la incertidumbre)
- Recolectar datos históricos para tener como referencia.

> Tenemos un requerimiento que tiene que ser completado antes del 1ro de julio

Sabemos que tenemos que hacer una estimación de tamaño y esfuerzo.
El tiempo es constraint.

Si queremos mantener la constraint podríamos aplicar Timebox Development, para entender cómo priorizar aquello que tenemos que hacer para alcanzar esa unidad de tiempo. Y la variable que tengo que empezar a recortar el alcance como grado de libertad; con lo cual nos empezaríamos a comer la variable esfuerzo.
> 

## Estimaciones Creíbles

- Las estimaciones las hacen las personas, no herramientas ni modelos
    - Se necesitan juicios razonables y compromisos con los objetivos organizacionales que no se pueden delegar a modelos automáticos
- Las estimaciones se basan en comparaciones
    - Cuando las personas estiman buscan similitudes y diferencias con proyectos previos
- Para que la gente pueda estimar necesitamos historia de proyectos pasados para poder comparar
    - Las estimaciones se pueden mejorar colectivamente juntando historia
- Un método creíble debe ser de caja blanca

## Ciclo de Estimación

- Estimar: Comenzar por estimar el tamaño para derivar el esfuerzo y el costo
- Medir: Mientras evoluciona el proyecto, medir el tamaño, el esfuerzo y el costo incurrido
- Registrar: Dejar claras las mediciones tomadas
- Analizar: Razones de desvíos, supuestos que quizás variaron, temas no contemplados, etc.
- Calibrar: Ajustar c/u de las variables y parámetros que intervienen en el proceso de estimación
- Volver a estimar
    - El mismo proyecto pero ahora con más información que al comienzo del mismo
    - Nuevos proyectos con el proceso ajustado por...
    
    ![Untitled](Estimaciones%20de%20Software%204dc11840c1cb43d1b567e94b9037d33a/Untitled%202.png)
    
    Relacionando con Scrum, en la retrospectiva pueden hacerse estos ajustes para poder estimar mejor en el próximo Sprint.
    
    # Métodos de Estimación
    
    Se dividen principalmente en 2 categorías:
    
    - Métodos rudimentarios ⇒ Estiman esfuerzo a partir del tamaño basado en los requerimientos. Nos dice horas hombre que lleva a hacer la tarea de forma ininterrumpida sabiendo que todas las personas que la ejecutan tiene todos los conocimientos para hacerlo.
        - Juicio experto
            - Alguien con experiencia define la cantidad de horas que puede llevar esa tarea.
            - Son muy dependientes de la persona
            - Es muy rápido.
            - “Esto se parece a algo que ya hice alguna vez”
            - 1 sola persona que estima.
        - ~~Pert.~~ Clarck
            - Un conjunto de 4 a 6 personas que hacen la misma estimación y se pondera.
        - Wideband Delphi: Colaborativa, participan las personas del equipo.
            - Se junta el equipo y de forma individual y sin comentar estiman un valor de esfuerzo, y se van poniendo de acuerdo.
            - Basado en una serie de reglas.
        - Planning poker: Idem
            - Suele utilizarse junto con scrum
            - Se estima el tamaño de un requerimiento
            - Consiste en una serie de tarjetas, pueden seguir fibonacci o cualquier otra.
            - Variación del método Wideband Delphi con algunas diferencias para adaptarse a los proyectos actuales con métricas similares a las de los métodos sofisticados
            - Se estiman tamaños de tareas relativos entre sí (tomando alguna como modelo). La estimación en SP puede variar entre proyectos, pero el tiempo no.
            - Muy buena para proyectos ongoing o desarrollo incremental a largo plazo. No tanto para primeras estimaciones o desarrollos de 0-100% en corto tiempo
            - Es más concensuado, pero no deja de ser subjetivo
            - Reglas
                - Participantes: Todo el equipo tiene que participar de la estimación
                - Timebox: Fijar la cantidad de tiempo que se va a estimar y cumplirlo (1h aprox)
                - Priorizar: Todas las User Stories (req) tienen que estar priorizadas y leídas previamente por el equiop para conocer lo que se está estimando.
                - Escala: Se miden las User Stories en Story Points que siguen la escala de la sucesión de fibonacci modificada
                - Tarea Pivote: Definir una user story pivote y darle un tamaño en Story Points. 5 u 8 SP son buenos candidatos. Puede ser una User Story actual o una anterior que sea significativa y todos la conocen o un caso general. Pueden ser varias de diferentes tamaños.
                - Velocity: Definir la velocidad del equipo (basada en sprints anteriores) para saber el número mínimo de SP que necesito estimar para completar un Sprint
                - DoD: Dar la definición de terminado de una User Story.
                    - Solo desarrollo?
                    - Incluye testing?
                    - Deploy a staging?
                    - UAT?
                    - Producción?
                - Puede utilizarse fibonacci, modified fibonacci, T-Shirt Sizes, The power of 2.
            - Dinámica de la estimación
                
                Hasta que se llegue a la cantidad de SP que marca la velocity para un sprint
                
                - El moderador (PO) plantea la User Story a todo el equipo
                - Cada integrante propone una estimación sin saber la de los demás (para evitar el efecto ancla)
                - Dar vuelta las cartas todos al mismo tiempo
                    - El mayor y el menor, dan explicaciones y discuten entre todos (2 min máximo)
                    - Se vuelven a mostrar las cartas por si alguno quiere cambiar su estimación (no se recomienda hacer más de 2 rondas de estimación para la misma story)
                - Se anota el ID de la User Story en el pizarrón en la columna de los SP estimados
                - Se continúa con la siguiente user story
    
    - Métodos paramétricos: Estiman tamaño.
        - Function Points
            - Evalúan la funcionalidad del sistema
            - Aplican una serie de reglas
            - Ve al sistema desde:
                - Las funciones que tiene que cubrir
                - Las entradas de información de la función
                - La salida de información de la función
                - La información que procesa la función
            - Independiente de la tecnología.
        - Use Case Points
            - No importa tanto la funcionalidad del sistema
            - Mide los casos de uso del usuario.
        - Story Points
            - Mide en función de la forma en la que se hacen las user stories
            - Mide la dificultad o el tamaño de implementar una user story
            - A partir de un análisis de la historia de usuario
            - No necesariamente 1 <=> 1, la user story como algo que aporta valor suele ser una línea, pero luego todo eso se desmenuza en cosas más concretas.
        - Object Points
            - Define al sistema como un conjunto de componentes (DB, Front, Back)
            - Define cuántos objetos son afectados por el requerimiento
            - Ideal para mantenimiento.
        
        Hay reglas de conversión que permiten conocer las horas a partir de la cantidad de puntos asignados. Se basa en la experiencia previa. A veces las conversiones dependen de la tecnología, no es lo mismo 10 FP en JS que en JAVA + Spring.
        
    
    > Ejemplo: Hay una tarea que se estimó que tardaría unas 4 horas en hacerla, pero como se va a asignar a un junior, por factor de conversión esa tarea tardaría 16hs, pero como el junior trabaja solo 4h por día. La tarea se calendariza en 4 días, si fuesen 2 personas, podría realizarse en 2 días si fuera paralelizable, pero ojo, a veces al poner más personas se puede incurrir en un esfuerzo mayor al puro, ya que hay que incluir la coordinación, y la adaptación de la persona a la tarea. Mientras más transparente sea el mecanismo de estimación, mayor chance de éxito y más se puede negociar.
    
    Así convierto esfuerzo puro en un calendario.
    > 
    
    ## Paper de Function Points
    
    “El modelo canónico” ⇒ Algo de lo cual se puede derivar el resto.
    
    Pensemos en este modelo en el cuál podría surgir cualquier mecanismo de estimación
    
    Hay un 1er paso que es **contabilizar y cuantificar cosas concretas de lo que tengo por delante**. En el caso de los function points hay 5 componentes que se utilizan para poder estimar, por ejemplo en una etapa temprana del proyecto con ciertos artefactos ya realizados, se realizaba hace algunos años lo que sería un diagrama de contexto, que identifica las fronteras del proyecto, identificando los componentes que interactuaban con el sistema: mi sistema con quién interactua? qué consume? qué tiene que proveer?. Cuando habla de external inputs y external outputs son dos de los elementos que se tiene que tener en cuenta a la hora de hacer el dimensionamiento de lo que estoy estimando. Luego habla de 3 conceptos más: las consultas externas (no es un input), almacenamiento lógico (no habla de implementaciones), (internal lógicas files y external files, que son los almacenamientos que no residen dentro del sistema). En el caso de los Use Case points, este primer paso cambia, pasa a contabilizar los actores y los casos de uso. Volviendo al modelo canónico, tenemos que identificar qué vamos a contar. Una vez que sabemos lo que vamos a contar. El segundo paso es **contar cuánto tengo de cada uno de eso** (ej: 5 actores, 20 casos de uso; o bien 5 inputs externos, tantas consultas, etc); lo que me pregunto ahora, es ¿Puedo contar todo de la misma manera? No, no todo tiene la misma complejidad, hay actores que “pesan más”, hay consultas que son más sencillas que otras. El tercer paso es **categorizar cada elemento** del paso anterior, para ver qué peso tiene respecto a otros, (por ejemplo simple, mediano, complejo, etc), una forma de **medir la complejidad** de un caso de uso es contar la cantidad de interacciones que tiene el caso de uso con sus actores, mientras más interacciones ⇒ más complejo. En cuanto a los estímulos y respuestas un external input de un código de operación con un precio en usd, es más sencillo probabablemente que el formulario de solicitud de un préstamo, podría establecer que la cantidad de atributos mide la complejidad de los external inputs o external outputs. Como 4to paso tengo que **definir cuánto pesa cada complejidad** con respecto al anterior (ej: un external input entre 1 y 5 atributos pesa 3, entre 5 y 15 pesa 5, etc), ahora tengo que contar cuántos elementos tengo en cada categoría. Por último **suman, y llegan a un número SIN AJUSTAR**, no tiene en cuenta el contexto. Lo que viene después es llevarlo a la realidad de mi proyecto, con factores de ajuste: elementos de contexto que pueden o no aplicar al proyecto, según qué tan relevante sea; puedo ver qué peso tienen ciertos atributos de la calidad y qué factor uso para ajustar el número sin ajustar, por ejemplo una aplicación que necesita de mucha seguridad, va a costar más para ciertas tareas. Al número puro lo voy multiplicando por coeficientes que me permitan transformarlo en un número que aporta algo más de contexto. En el caso de los UCP contempla una tabla de complejidad técnica y una tabla de complejidad ambiental (o factores blandos); una tiene más que ver con los atributos de calidad y otro con la motivación, experiencia, si el equipo se lleva bien, etc. El siguiente paso entonces es: **identificar factores de ajuste y asignar un peso obteniendo un número ajustado que tiene en cuenta el contexto**.