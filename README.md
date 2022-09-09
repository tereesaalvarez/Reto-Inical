# Reto-Inical

https://github.com/tereesaalvarez/Reto-Inical.git

Trabajo hecho por Esther Rodríguez, Claudia Lozano, Jose Luis Rodríguez y Teresa Álvarez

## Prueba del Caballo

Para resolver esta prueba hemos sacado la funcion que halla el resultado de las posibilidades válidas que hay dependiendo de la cantidad de movimientos.

Llamamos n a la cantidad de movimientos y ans a la solucion de la ecuacion dependiendo de la n. n iría desde 1 hasta 32.

Partimos de que las posibilidades validas para 1 movimiento, que serian 20. (ans=20)

for num in [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32]

La función --> f = 2*ans + 3* (2**num) = ans. Esta variable ans nueva sería la que se usaria para la siguiente funcion con num=2

## Prueba de la Reina

Para resolver esta prueba tenemos que crear una funcion que reciba el numero de reinas (n) y otra que será una matriz de rango n que la llamaremos "tablero".
Una vez que tengamos creado el tablero, tenemos que crear una funcion mediante la cual, con un bucle for i in range que se repita hasta que sea capaz de colocar las n reinas en el tablero
consiguiendo que no puedan "comerse" entre ellas.
Colocaremos la 1a reina mediante una tupla [fila,columna] y asi obligando al resto de reina a ccolocarse en casillas en las cuales no puedan ser comidas por otras. La fichas no pueden coincidir en la misma fila (i), columna (j), ni diagonalmente (i1 - j1 =! i2 - j2).
Una vez colocadas todas las fichas, el programa mediante un bucle for obtendra el número de soluciones tootales.
