# Software Engineering Approaches

## ¿Qué es un proyecto?

> *Es un esfuerzo temporal emprendido para crear un producto o servicio **único** para lograr un objetivo.*
> 

Aunque sea el mismo producto, hay distintos calendarios, presupuestos, requerimientos, etc.

Una tarea operativa no tiene un objetivo como tal, se repite en varias ocaciones, etc.

Proyecto:

- Tiene un objetivo o beneficio a obtener que guía el proyecto
- Temporal: Tiene principio y fin
- Único: No es recurrente, cada proyecto es diferente a otro.
- Posee recursos limitados
- Consta de una sucesión de actividades o fases en las que se coordinan los distintos recursos

## ¿Qué es project management?

> *La administración de proyectos es una disciplina que consiste en planificar, organizar, obtener y controlar recursos, utilizando herramientas y técnicas para lograr que el proyecto logre sus objetivos en tiempo y forma.*

Así como teníamos el CMMI, para el caso de project management existe el PM Book como marco de referencia.
> 

## Dimensiones de un proyecto de software

- No se pueden cumplir todas a la vez.
- Cada dimensión puede ser:
    - Driver: Objetivo vital a lograr, tiene poco o nada de flexibilidad
    - Restricción: No está bajo nuestro control directo y también tiene poca o nula flexibilidad.
    - Grado de libertad: Libertad para fijar objetivos. Existe flexibilidad para manejar esta variable
    

![Untitled](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Untitled.png)

En un proyecto personal puede ser que el costo  y el esfuerzo (alcance) sean grado de libertad, pensemos que no me tengo que pagar a mi mismo. Y la restricción serían los recursos, capaz soy yo solo, o somos 2, con lo cual el tiempo también se extendería bastante.

Todo el equipo tiene que involucrarse y saber cuáles son las dimensiones y sus roles.

## Roles en el proyecto

- Stakeholder
    - Es toda persona involucrada en el proyecto
    - Tiene poder de decisión con capacidad de influir en la marcha del proyecto
- Sponsor
    - Es el **owner** del proyecto
    - Es el que tiene la autoridad para llevar adelante el proyecto
    - Pone la plata
- Usuario campeón
    - Experto en el dominio del problema del proyecto
    - Asegurar su capacidad para la función y su disponibilidad (Son muy demandados)
- Usuarios directos
    - Interactúan directamente con el sistema
- Usuarios indirectos
    - Hacen uso del sistema, aunque no necesariamente lo operan
    
    > Ejemplo:
    
    En ventanilla del banco, el usuario directo del sistema es el cajero humano del sistema del banco, el cliente juega un papel de usuario indirecto; al momento de hacer el delívery tengo que pensar en el cajero y cómo va a usar el sistema. Al cajero humano le importa que sea rápido para agilizar su trabajo, capaz no importa la UX.
    
    En un homebanking, el usuario directo pasa a ser el usuario de la aplicación.
    
    El champion user es el loco que tiene todo en la cabeza, sabe perfectamente que si vas a hacer una transferencia a tal provicia hay que retener tal cosa para la afip o lo que sea. Se sabe toda la normativa del BCRA, AFIP, etc. Capaz es el tipo del mantenimiento que hace 20 años que mantiene el mísmo código COBOL que por saber leerlo y conocerlo se sabe todas las reglas de negocio.
    > 
    
    ## Cynefin
    
    Es un modelo que compara características de ~~cinco~~ cuatro dominios de complejidad:
    
    - Simple
        - Significa que la situación es estable y existen reglas probadas para aplicar. Las **mejores prácticas** son métodos o técnicas superiores a cualquier otra alternativa que produce los mejores resultados que utilizando otros medios
        - La relación entre causa y efecto es clara: Si se realiza X ⇒ Se espera Y
        - En este dominio se establecen lo hechos, se categorizan y se responde con una regla o se aplica una mejor práctica (sense-categorize-respond)
    - Complicado
        - El dominio complicado implica que la relación causa y efecto requiere análisis o experiencia; existen múltiples respuestas correctas. Las **buenas prácticas** son métodos o técnicas que pueden aplicarse según la decisión de un experto
        - Se evalúan los hechos, se analizan y se aplica una buena práctica (sense-analyze-respond). Es posible trabajar racionalmente hacia una decisión pero requiere un juicio refinado y con experiencia.
        - Necesito un experto para saber por qué camino voy, que me ayude a tomar decisiones. Hay que decidir por una buena práctica, porque pueden haber varias.
    - Complejo
        - En el dominio complejo la relación causa y efecto sólo puede ser vista en retrospectiva. No hay respuestas correctas. Los **Diseños Útiles e Informativos** pueden desarrollarse. Se pueden considerar experimentos para encontrar una solución a los problemas. Las soluciones son adaptativas
        - Se exploran soluciones, se analizan y se responde al problema (probe-sense-respond). No es predecible el resultado de las acciones propestas. El ámbito donde nos encontramos es desconocido y el cambio es constante lo que no permite anticipar todos los resultados.
        - Estoy en un contexto de incertidumbre ⇒ Prácticas emergentes. Voy probando para ver si funciona. Acá conviene usar Scrum.
        - Por ejemplo: un banco tiene mucha incertidumbre.
    - Caótico
        - En el dominio caótico la relación causa y efecto es incierta. Los eventos en este dominio son muy confusos para esperar una respuesta basada en el conocimiento. **Cualquier acción** es la respuesta apropiada. Nos encontramos frente a una crisis donde lo importante es actuar.
        - Se actúa para establecer el orden, se analiza lo que tiene algo de estabilidad y se responde para transformar el caos en complejidad (act-sense-respond)
    
    Sirven para saber en qué contexto me encuentro y de acuerdo a eso elegir un framework o metodología.
    
    Por ejemplo, capaz Scrum no sirve en un contexto simple, en donde Scrum es todo a prueba y error para ver qué cosas aportan más valor.
    
    ![Untitled](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Untitled%201.png)
    

El lado derecho será el lado “ordenado”, ya sé lo que tengo que resolver, que puede ser complicado o simple.

Del otro lado estoy en un contexto más desordenado, que puede ser complejo, en donde necesito prácticas emergentes donde necesito hacer prueba y error para ver si funciona o no; o bien caótico donde NO puedo ponerme a perder tiempo en plannings, etc, acá scrum no sirve; necesito salir lo antes posible del contexto caótico.

![Untitled](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Untitled%202.png)

[Scrum](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Scrum%20869929b298f642018fb4956d1da50cf4.md)

[Kanban](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Kanban%2074171e4e7ffb43e793a263460ee74e24.md)

[Lean](Software%20Engineering%20Approaches%20ebe78ecc39e54b928061aea55698bc8e/Lean%20c693ad08c7c3434ab75df632fcd81a78.md)