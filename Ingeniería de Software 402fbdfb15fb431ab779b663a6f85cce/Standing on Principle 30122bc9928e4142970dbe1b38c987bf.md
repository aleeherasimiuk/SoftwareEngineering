# Standing on Principle

![Untitled](Standing%20on%20Principle%2030122bc9928e4142970dbe1b38c987bf/Untitled.png)

> Ejemplo:
¿cuánto te tomará el proyecto?
> 2 años
¿Que tal 6 meses?
> ... Ok
> 

Podemos comprometernos siempre y cuando sepamos más o menos cuánto podría llevar hacer algo, o costar, pero no adivinar; por lo menos permitirnos esperar un poco a tener los requerimientos más claros para poder dar una estimación más concreta.

El cliente no siempre tiene la razón

> Capaz el cliente quiere que el software tenga una calculadora, pero capaz era mucho más simple tener una calculadora al lado; por lo menos al querer construir un MVP, en donde el tiempo es limitado.
> 

El diagrama de Kiviat representa el síndrome de la frazada corta. No pueden maximizarse todas las dimensiones a la vez. Hay variables que tendrán que ceder en función de otra. Hay que identificar para cada una de estas dimensiones si juega un papel de restricción, o de grado de libertad.

## Roles

- Driver ⇒ Conduce el proyecto, tiene poca o nada de flexibilidad. Puede negociarse un poco
- Constraints ⇒ No tienen flexibilidad. No pueden negociarse. Marcan los límites.
- Grado de libertad ⇒ Incluye las demás dimensiones.

Por lo general, la dimensión de funcionalidad ocupa el rol de **Driver**, es aquello que motiva o impulsa del desarrollo. Tiene cierto grado de flexibilidad. Los **constraints** suelen ser el presupuesto o el calendario

> Ejemplo: a partír del 20 de noviembre todos deben implementar QR Interoperable

Aplicando la teoría, el driver sería la funcionalidad, mientras que el tiempo juega el papel de restricción. La variable restante (costo) pasa a ser grado de libertad. (Teniendo en cuenta el modelo de 3 dimensiones)

Si el costo fuese un constraint, entonces hay que ver si se puede negociar, por ejemplo la fecha, o hacer una “poda” de features; recortar hasta que calce.

Una buena forma de empezar un proyecto con el pie derecho es identificar correctamente cada una de las dimensiones y ubicarlas en los roles correctos.
> 

> Ejemplo día del amigo:

Una empresa de telecomunicaciones implementó los números amigos, pero tenían que largarlo antes de la competencia, con lo cual si bien la web estaba disponible, por detrás todo iba a parar a un log que los operadores manualmente asignaban como números amigos.

En un modelo de 5 variables:

Restricción: Tiempo (Innegociable)
Driver: Funcionalidad que copiamos de la competencia. Tenía algo de flexibilidad.
Grado de libertad: Calidad, Staff y Costo.

En este caso: Se cumplió con el tiempo, con un delívery de funcionalidad que no tenía calidad.

Cumplió con el objetio, con un delivery que cumplía las expectativas. Es una solución ingenieril.
>