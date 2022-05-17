# Software Quality

Si bien en un principio pareciera que la calidad es algo puramente subjetivo, en deberíamos encontrar alguna forma de estandarizar y objetivizar los parámetros de algo que tiene calidad.

Hay varias definiciones de calidad:

- Según Crosby
    - Cumplir con los requerimientos
- Según Weinberg
    - Cumplir con los requerimientos de alguna persona
        - Calidad es valor para alguna persona
        - Valor es aquello que está dispuesto a pagar para obtener sus requerimientos
- Según Juran
    - Adecuación al Uso
        - Satisfacción de las necesidades del cliente
        - Ausencia de deficiencias
- ISO 8402-1986
    - La totalidad de aspectos y características de un producto o servicio que se sustentan en su capacidad de cumplir las necesidades específicadas o implícitas
    

## Visiones de la Calidad

La calidad puede ser percibida desde cinco perspectivas

- La Visión Trascendental
    - La calidad es algo que se puede reconocer pero no se puede definir
    - Es fundamentalmente subjetivo
    - No hay nada contra qué comparar
    - Hay que salir de esta posición, aunque no deja de ser algo válido.
- La visión del usuario
    - La calidad es adecuación al propósito
    - Pone la vista desde el lado del cliente
    - ¿El producto cumple con lo que el usuario necesita?
    - Es subjetiva
- Visión de la manufactura
    - Es objetiva
    - La calidad es conformidad con la especificación
    - El producto tiene calidad de acuerdo al proceso que lo construye.
    - Si el proceso es bueno ⇒ El producto es bueno
    - Entran en esta categoría:
        - ISO 9000|14000
        - Modelos de calidad como CMMI
        - Cualquier modelo que se enfoque sobre el proceso
- Visión del producto
    - Es objetiva
    - La calidad está vinculada a las características inherentes del producto
    - El producto que yo construí, ¿Qué tanto se acerca al producto que yo desearía tener?
    - Cumple con ciertos atributos en cierto grado
        - Usabilidad
        - Seguridad
        - Etc
    - Si bien hay un grado de subjetividad al momento de elegir aquellos atributos a priorizar, es fundamentalmente objetiva cuando se habla sobre esos atributos. Por lo menos hay algo concreto sobre qué comparar.
- Visión basada en el valor
    - La calidad depende de la cantidad de dinero que el usuario está dispuesto a pagar por el producto. (Calidad - Precio)
    - Maximizo la relación Costo|Beneficio
    - Es subjetiva
    

Pregunta: ¿Puede pasar que teniendo un proceso de calidad pueda llegar a un producto que no es de calidad?

> Depende de la visión. Si es desde el punto de vista de la manufactura NO. Si se lo entrego al usuario y no suple sus necesidades, entonces el producto, desde la visión del usuario no tiene calidad.
> 

Las visiones no tienen por qué verse separadas, hay que encontrar cuál es el conjunto de visiones que tenemos que prestar atención de acuerdo al contexto en el que estamos. Algunas visiones pueden ser más importantes de acuerdo al contexto.

## La calidad tiene un costo

El costo de calidad son todas aquellas acciones que voy a realizar para que el producto que yo estoy construyendo cumpla con los objetivos de las visiones que yo establecí.

## La no calidad también

Costos ocultos de la NO-Calidad

- Baja motivación de los equipos de trabajo | Duplicación de esfuerzos
- Over-time constante | Re-trabajo constante (mayor costo monetario)
- Desgaste del equipo de trabajo
- Imagen negativa ante el cliente

![Untitled](Software%20Quality%2062e27010a28f46efa88e56f49d621ad2/Untitled.png)

El costo de la no calidad es medible, y es el costo de aquellas tareas que se tuvieron que hacer para remediar los efectos de la falta de calidad. Por ejemplo refactors, solución de bugs, etc.

Es importante en el proceso tener un momento de medir estos costos para intentar mitigarlos en una próxima etapa. Con esto se puede saber cuánto cuesta por ejemplo no haber hecho una actividad de testing.

## Calidad de Producto

ISO/IEC 25000, conocida como SQuaRE (System and Software Quality Requirements and Evaluation), es una familia de normas que tiene por objetivo la creación de un marco de trabajo común para evaluar la calidad de un producto software

ISO/IEC 2500n: División para la gestión de la calidad:

- ISO/IEC 2501n: División para el modelo de calidad
- ISO/IEC 2502n: División para la medición de calidad
- ISO/IEC 2503n: División para los requisitos de calidad
- ISO/IEC 2504n: División para la evaluación de calidad

## Calidad del Producto Software (ISO 25010)

- Adecuación Funcional:
    
    Representa la capacidad del producto software para proporcionar funciones que satisfacen las necesidades declaradas e implícitas, cuando el producto se usa en las condiciones especificadas
    
    - Completitud Funcional
        - Grado en el cual el conjunto de funcionalidades cubre todas las tareas y los objetivos del usuario especificados
        - Mientras más cobertura, mientras más funcionalidades tenga, entonces es más completo.
    - Corrección funcional
        - Capacidad del producto o sistema para proveer resultados correctos con el nivel de precisión requerido
        - Se habla puntualmente de presición
    - Pertinencia funcional
        - Capacidad del producto software para proporcionar un conjunto apropiado de funciones para tareas y objetivos de usuario especificados
        - Suitability: Cuán adecuado es lo que tengo para cumplir con las funciones.
        
    
    Ejemplo de métrica: Cobertura funcional
    
- Eficiencia de desempeño
    
    Esta característica representa el desempeño relativo a la cantidad de recursos utilizados bajo determinadas condiciones
    
    - Comportamiento temporal
        - Los tiempos de respuesta y procesamiento y los ratios de throughput de un sistema cuando lleva a cabo sus funciones bajo condiciones determinadas en relación con un banco de pruebas (benchmark) establecido
    - Utilización de recursos
        - Las cantidades y tipos de recursos utilizados cuando el software lleva a cabo su función bajo condiciones determinadas
    - Capacidad
        - Grado en que los límites máximos de un parámetro de un producto o sistema software cumplen con los requisitos
    
    Ejemplo de métrica: Cnatidad media de rendimiento o tiempo medio de respuesta
    
- Compatibilidad
    
    Capacidad de dos o más sistemas o componentes para intercambiar información y/o llevar a cabo sus funciones requeridas cuando comparten el mismo entorno hardware o software
    
    - Coexistencia
        - Capacidad del producto para coexistir con otro software independiente, en un entorno común, compartiendo recursos comunes sin detrimento
        - Ej: Que un antivirus no moleste la ejecución de otro programa.
    - Interoperabilidad
        - Capacidad de dos o más sistemas o componentes para intercambiar información y utilizar la información intercambiada
    
- Usabilidad
    
    Capacidad del producto software para ser entendido, aprendido usado y resultar atractivo para el usuario, cuando se usa bajo determinadas condiciones
    
    - Inteligibilidad
    - Aprendizaje
    - Operabilidad
    - Protección frente a errores de usuario
    - Estética
    - Accesibilidad
    
    - Capacidad para reconocer su adecuación
        - Capacidad del producto que permite al usuario entender si el software es adecuado para sus necesidades
        - Todos tienen que saber y reconocer para qué sirve
    - Capacidad de aprendizaje:
        - Capacidad del producto que permite al usuario aprender su aplicación
    - Capacidad para ser usado
        - Capacidad del producto que permite al usuario operarlo y controlarlo con facilidad
    - Protección contra errores de usuario:
        - Capacidad del sistema para proteger a los usuarios de hacer errores
    - Estética de la UI
        - Capacidad de la interfaz de usuario de agradar y satisfacer la interacción con el usuario
    - Accesibilidad
        - Capacidad del producto que permite que sea utilizado por los usuarios con determinadas características y capacidades
    
    Ejemplo: Un abuelo que sabe usar un celular, o un niño que aprende a usar una tablet.
    
- Fiabilidad
    
    Capacidad de un sistema o componente para desempeñar las funciones especificadas, cuando se usa bajo unas condiciones y período de tiempo determinados
    
    - Madurez
        - Capacidad del sistema para satisfacer las necesidades de fiabilidad en condiciones normales
        - Que a medida que pasa el tiempo no revienta.
        - Medido por ejemplo por el tiempo promedio entre fallas
    - Disponibilidad
        - Capacidad del sistema o componente de estar operativo y accesible para su uso cuando se requiere
        - Se mide downtime
    - Tolerancia a Fallos
        - Capacidad del sistema o componente para operar según lo previsto en presencia de fallos hardware o software
        - Si ocurre algo que no estaba previsto, qué capacidad tiene de seguir operando.
    - Capacidad de Recuperación
        - Capacidad del producto software para recuperar los datos directamente afectados y reestablecer el estado deseado del sistema en caso de interrupción o fallo
        - Conceptos a evaluar
            - ¿Cuánta info estamos dispuestos a perder con respecto a lo que se vino trabajando? El último día?, la última hora? los últimos minutos?, etc
            - ¿Cómo quiero volver? Inmediatamente? Curva ascendente? Por ejemplo de 10 personas van arrancando de a uno. O el 10% la primera hora, etc.
            - ¿Cuánto tiempo estoy dispuesto a estar fuera de línea?
    
    Ejemplo de métrica: Tiempo medio de recuperación o tiempo medio entre fallas.
    
- Seguridad
    
    Capacidad de protección de la información y los datos de manera que personas o sistemas no autorizados no puedan leerlos o modificarlos
    
    - Confidencialidad
        - Capacidad de protección contra el acceso de datos e información no autorizados, ya sea accidental o deliberadamente
        - Acceso interno o externo, de adentro de la organización o de afuera.
    - Integridad
        - Capacidad del sistema o componente para prevenir accesos o modificaciones no autorizados a datos o programas de ordenador
        - Nadie sin permiso puede cambiar datos, ni tener acceso a donde no corresponde, etc.
    - No Repudio
        - Capacidad de demostrar las acciones o eventos que han tenido lugar, de manera que dichas acciones o eventos no puedan ser repudiados posteriormente.
        - “Me clavó el visto” ⇒ No se puede negar que lo vió
    - Autenticidad
        - Capacidad de demostrar la identidad de un sujeto o recurso
    - Responsabilidad
        - Capacidad de rastrear de forma unívoca las acciones de una entidad
        - Tener trazabilidad de las acciones que ejecuta alguien.
        - Capacidad de logueo.
    
- Mantenibilidad
    
    Esta característica representa la capacidad del producto software para ser modificado efectiva y eficientemente, debido a necesidades evolutivas, correctivas o perfectivas
    
    - Modularidad
        - Capacidad de un sistema, programa de ordenador (compuesto de componentes discretos) que permite que un cambio en un componente tenga un impacto mínimo en los demás
    - Reusabilidad
        - Capacidad de un activo que permite que sea utilizado en más de un sistema software o en la construcción de otros activos
    - Analizabilidad
        - Facilidad con la que se puede evaluar el impacto de un determinado cambio sobre el resto del software, diagnosticar las deficiencias o causas de fallos en el software, o identificar las pertes a modificar
        - Saber el esfuerzo que me demanda identificar dónde tengo que meter mano.
    - Capacidad de ser modificado
        - Capacidad del producto que permite que sea modificado de forma efectiva y eficiente sin introducir defectos o degradar el desempeño
        - Saber el esfuerzo que me demanda meter mano
    - Capacidad de ser probado
        - Facilidad con la que se pueden establecer criterios de prueba para un sistema o componente y con la que se pueden llevar a cabo las pruebas para determinar si se cumplen dichos criterios.
        - Saber el esfuerzo que me demanda testear
    
    Ejemplo de métrica: Líneas de código, o tiempo medio de reparación (No confundir con recuperación)
    
- Portabilidad
    
    Capacidad del producto o componente de ser transferido de forma efectiva y eficiente de un entorno hardware, software, operacional o de utilización a otro
    
    - Adaptabilidad
        - Capacidad del producto que le permite ser adaptado de forma efectiva y eficiente a diferentes entornos determinados de hardware, software, operacionales o de uso
    - Facilidad de Instalación
        - Facilidad con la que el producto se puede instalar y/o desinstalar de forma exitosa en un determinado entorno
    - Capacidad de ser reemplazado
        - Capacidad del producto para ser utilizado en lugar de otro producto software determinado con el mismo propósito y en el mismo entorno
        - “Vendor locking”
        
    

Esta lista de subatributos es un input para la definición de los requerimientos no funcionales y asociado a eso, las pruebas no funcionales.

Requerimientos funcionales: Qué quiero hacer

Requerimientos no funcionales: Bajo qué condiciones quiero hacer eso

Restricciones: Cosas que no puedo negociar y marcan la cancha.

## Calidad del Proceso

Un proceso es el conjunto de actividades que la gente usa para desarrollar y mantener software y sus productos asociados.

¿Cómo se mide un proceso?

Pueden realizarse auditorías, que evalúan que las actividades del proceso cumplan con algo preestablecido.

Un proceso debería estar predefinido y documentado

Así como en la Calidad del Producto teníamos la ISO 25000, para el caso de la Calidad del Proceso, acá aparece el framework (NO METODOLOGÍAS) que permiten evaluar la MADUREZ de un proceso de software.

Si uno hace las cosas de manera correcta, hay altas chances de que el resultado sea correcto.

Por eso se establecen los niveles de Madurez.

### Madurez

La capacidad organizacional, no individual, de cumplir sistemáticamente con los objetivos

Es el grado en que un proceso está:

- Definido y documentado
- Administrado y controlado
- Medido y es efectivo

CMMI (Uno de los frameworks): Tiene 5 niveles

1. **Caótico**: Todas las organizaciones asumen que están acá al **empezar** a evaluar cómo construir SW.
2. **Repetible**: Empieza a definir qué **prácticas** serían **recomendables** incluir en la construcción de SW correspondiente y para aprender. (Gestión de configuración, gestión de riesgos, gestión de configuración, gestión de planificación, etc.)Trabajas proyecto a proyecto con formas distintas de trabajar.
3. **Definido**: Los distintos proyectos trabajan de **igual forma**, con las mismas herramientas
4. **Administrado - cuantitativo:** Empieza a **medir** todos los trabajos que voy realizando, representado en mediciones, números, etc.
5. **Optimización:** Continuamente voy **retroalimentando** feedback con buenas prácticas, cómo innovar y agregar nuevas tecnologías para mantener el nivel de madurez.

Otros modelos además de CMMI:

- ITIL:
    - Conjunto de buenas prácticas utilizadas para la gestión de servicios de tecnologías de información
        - Provisión & soporte de servicios de IT es lo más importante
- ISO 15504 (Spice)
    - Estándar internacional de evaluación y determinación de la capacidad y mejora contínua de procesos de ingeniería de software
        - Modela procesos para gestionar, controlar, guiar y monitorear el desarrollo del software

### Capacidad de un Proceso

Habilidad inherente de un proceso de Software para producir los resultados planificados

Procesos Maduros

- Soportado por la gerencia
- Definido, documentado, conocido y practicado
- Existe infraestructura adecuada para soportarlo
- Adecuadamente medido
- Adecuadamente controlado
- Presupuestos y plazos realistas
- Riesgo conocido y controlado
- Proactivo
- Es como respirar... institucionalizado

Proceso Inmaduro

- La gerencia dice soportarlo
- Improvisado sobre la marcha
- Aunque esté definido no se sigue rigurosamente
- No hay entrenamiento formal ni herramientas para sustentarlo
- Presupuestos y plazos son generalmente excedidos por estimaciones no realistas
- Es una organización “reactiva”

El nivel de madurez me permite elegir sofware factory, la madurez se nota en el momento que me demuestran cómo van a realizar el delívery. Me da más confianza, es más predecible.

Como colorario: Quiero un framework que me sirva para medirme y saber lo siguiente:

- ¿Dónde estoy parado?
- ¿Dónde quiero ir?
- ¿Qué tengo que hacer para moverme de un lugar a otro?

Un ejemplo podría ser el proceso de gestión de requerimientos, como se cargan en jira, cómo se priorizan, etc.