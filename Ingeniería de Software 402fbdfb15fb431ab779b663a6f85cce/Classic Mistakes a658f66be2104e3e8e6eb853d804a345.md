# Classic Mistakes

## Mencionados en clase

- Gurúes:
    - Dependemos de ellos
    - Si cambian de rol o se van el proyecto entra en problemas
    - Problemático en empresas con rotación de talento
- Estimaciones pobres y sin fundamentos
- Ignorancia de los riesgos
- Se asumen compromisos imposibles de cumplir
- Requerimientos no claros
- Code & Fix: “Ir conduciendo un tren en llamas mientras vas poniendo los rieles adelante”
- Incrementar cantidad de desarrolladores para resolver más rápido
    - No todas las tareas se pueden hacer más rápido por agregar más recursos
    - Agregar gente a un proyecto:
        - Habría que revisar las dependencias de las tareas
        - Ver el grado de comunicación necesario
        - Experiencia en la ejecución
- Cambiar las herramientas de trabajo a la mitad del proyecto
- Heroics: De hecho puede no ser una persona sino una consultora

Queremos que un proyecto sea exitoso y para eso como manager tengo que ver qué cosas podrían complicar el desarrollo normal del proyecto, para poder evitarlos.

> Da para pensar si realmente practicamos una ingeniería donde todo el proceso se encuentra controlado o estandarizado en búsqueda de una mejora contínua, o si en realidad es más bien una artesanía en donde voy atando todo con alambres dejando deuda técnica constantemente. ¿Será que el try & error es muy barato? pensar en cómo era en la época de las tarjetas perforadas, o qué tan trágico sería equivocarse durante el proceso de la ingeniería de la construcción del avión.
> 

## Diagrama de Causa - Efecto

Existen técnicas que nos ayudan a identificar las causas de los problemas, uno de las más conocidas es el diagrama de Causa - Efecto:

![Untitled](Classic%20Mistakes%20a658f66be2104e3e8e6eb853d804a345/Untitled.png)

El diagrama consiste en identificar el problema en la cabeza o base del diagrama, por ejemplo Heroics.

> En el incidente de la semana pasada tuvimos que depender de que Marcelo esté, sin él no lo podríamos resolver.
> 

Luego hay que identificar qué causas llevan a que eso haya sucedido.

> ¿Por qué necesitamos a Marcelo?
> Justo el que estaba de guardia no podía estar
> La actividad no estaba documentada y no sabíamos cómo proceder
> 

Todas esas acciones las agrupamos en temas, (por ejemplo métodos, máquinas, materiales)

> Para el tema “Equipo” hubo un problema de asignación de guardias, o el guardia no sabía ejecutar la acción.
El problema de asignación de guardias existió porque no se tuvo en cuenta que era un fin de semana largo.
...
> 

En síntesis, nos permite hacer las preguntas orientadas a aquellas situaciones que nos generaron el problema. Tratar de entender la causa raíz.

En general se utiliza la técnica de los 5 por qué.

- Se pregunta por qué se produjo ese problema
- Y luego se pregunta por qué se llegó a esa situación

[Classic Mistakes](Classic%20Mistakes%20a658f66be2104e3e8e6eb853d804a345/Classic%20Mistakes%20b97c3dfbb4a6412a945b419fc741c7b4.csv)