# Proyecto_ia_2048

# Definición del ambiente
  El ambiente es de tipo observable, estocástico, episódico, estático, discreto y agente singular. Los estados del juego pueden ser descritos por una matriz cuadrada de  potencias de 2 excluyendo el 1. El juego comienza con un bloque 2 en la matriz, al hacer movimentos aparecen un bloque 2 o 4 para remplazar uno vacio estócásticamente, cuando sucede un movimiento en un eje donde hay 2 bloques del mismo valor sin otros bloques con valor entre ellos, se unen en un bloque que contiene la suma de los bloques colapsados. El juego termina si es que hay un bloque con valor 2048 o no hay más movimientos posibles, lo que determina victoria o derrota, respectivamente.

# Descripción del agente
 El agente tiene un espacio de acciones discreto que consiste en [ ←, →, ↓, ↑].
