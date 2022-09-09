# Reto-Inical

https://github.com/tereesaalvarez/Reto-Inical.git

Trabajo hecho por Esther Rodríguez, Claudia Lozano, Jose Luis Rodríguez y Teresa Álvarez

## Prueba del Caballo

Para resolver esta prueba hemos sacado la funcion que halla el resultado de las posibilidades válidas que hay dependiendo de la cantidad de movimientos.

Llamamos n a la cantidad de movimientos y ans a la solucion de la ecuacion dependiendo de la n. n iría desde 1 hasta 32.

Partimos de que las posibilidades validas para 1 movimiento, que serian 20. (ans=20)

for num in [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32]

La función --> f = 2*ans + 3* (2**num) = ans. Esta variable ans nueva sería la que se usaria para la siguiente funcion con num=2
