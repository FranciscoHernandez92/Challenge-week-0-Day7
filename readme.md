## CHALLENGE 07
Juego de Cartas: Mayor o Menor
Recuperamos el juego del challenge anterior para convertirlo en una aplicación web. La idea es que el usuario pueda jugar desde el navegador y que el juego se ejecute mostrando las interacciones necesarias a traves del HTML.

No usaremos los elementos del API de mensajes emergentes:

alert()
prompt()
confirm()
Tampoco le proporcionamos feedback al usuario a través de la consola.

En su lugar, utilizaremos elementos HTML para mostrar mensajes y obtener respuestas del usuario:

inputs
botones
párrafos
outputs
etc.

El objetivo del juego es adivinar si la siguiente carta en el mazo es mayor o menor que la carta actual. Se utiliza un mazo de cartas francesas que consta de 52 cartas, divididas en 4 palos: (espadas), (tréboles), (diamantes) y (corazones). Cada palo tiene 13 cartas con los siguientes valores: 2, 3, 4, 5, 6, 7, 8, 9, 10, J (jota), Q (reina), K (rey) y A (as).

El juego consta de las siguientes funcionalidades:

Generación de cartas: Las cartas se generan combinando los valores y palos disponibles en el mazo de cartas francesas.

Obtención de una carta aleatoria: Se implementa una función para obtener una carta aleatoria del array de cartas generado previamente.

Inicio de un nuevo juego: Se inicia un nuevo juego generando un nuevo array de cartas y barajándolas. Se muestra la carta inicial en la consola, incluyendo su valor. Se solicita al jugador que elija si la siguiente carta será mayor o menor ingresando "mayor" o “menor” para menor. (No puede ser case sensitive).

Verificación de la respuesta del jugador: Cuando el jugador ingresa su elección, se genera una nueva carta y se compara con la carta actual. Si la respuesta del jugador es correcta, se muestra un mensaje indicando que acertó y se actualiza la puntuación. Si la respuesta es incorrecta, se muestra un mensaje indicando que falló y se muestra la carta actual y la nueva carta en la consola. El jugador puede reiniciar un nuevo juego después de cada respuesta.

Fin del juego: Tras cada partida se le pregunta al jugador si quiere terminar la partida y de ser así, se le muestra la puntuación final con las rondas.
