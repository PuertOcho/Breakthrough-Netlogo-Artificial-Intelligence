
# Definición y funcionamiento de Breakthrough

Gran Avance es un abstracto juego de estrategia inventado por Dan Troyka en el año 2000. En el 2001 ganó la Competición de Diseño de Juegos 8x8 y tiene cierta similitud con las damas, pero la estrategia es completamente diferente. Se juega sobre un tablero de 8x8 casillas con fichas blancas y negras. El objetivo del juego consiste en alcanzar la fila principal del adversario - la más alejada respecto del jugador. Esto significa que el jugador blanco debe alcanzar la octava fila y que el negro debe alcanzar la primera fila para ganar la partida. Cada jugador mueve una ficha por turno. Una ficha puede ser movida una casilla hacia delante frontal o diagonalmente siempre y cuando la casilla de destino esté libre. Una ficha puede también ser movida a una casilla ocupada por otra del rival siempre y cuando esté una casilla delante diagonalmente. La partida finaliza si uno de los jugadores alcanza la fila principal del adversario.

![](images/granAvanceView.png)


# Como se usa

Para usarlo haz click en el boton HvsH en caso de que quieran jugar dos jugadors humanos o si prefieres jugar contra una inteligencia aritficial haz click en HvsIA. Trás esto haz click en setup.
Ahora solo tienes que hacer click en la ficha que quieras mover en caso de que el juego muestre tu turno y arrastrarla a la casilla donde se desee moverla.
Una vez finalizada la partida se mostrará un cartel donde se indique que jugador ha ganado, trás esto puedes volver a hacer click en setup para reinciar la partida y volver a jugar.

### Ejemplo 1


* El **primer parámetro** hará referencia a la cantidad de información mínima que se necesita en cualquiera de las ramas para seguir desarrollando hacia abajo, si no se llega a este tamaño mínimo que nosotros pongamos esa rama dará lugar a un nodo hoja con el resultado expresado en porcentaje. Este porcentaje se consigue viendo sobre cada entrada correspondiente a una rama en concreto y viendo el resultado que obtenemos como respuesta.

  Con **tamaño mínimo** 6 si una rama dada no contiene al menos 6 entradas de datos, devolvemos los porcentajes correspondientes a la respuesta que obtenemos hasta esa parte.


* El **segundo parámetro** indicará la **profundidad máxima** del árbol, de forma que cuando una rama se expanda hasta llegar al límite puesto por el parámetro dará un resultado en forma de porcentaje al igual que en el parámetro anterior.

  Con **profundidad** 2 estamos obligando a las ramas a tener hasta profundidad 2 del árbol, lo que significa que cortamos lo que seguiría de la rama y colocamos directamente los porcentajes al igual que el primer parámetro.





# Bibliografía

http://www.cs.us.es/~fsancho/?e=104