Ya dijimos que la **interpretación** es el proceso por el cual se obtiene el valor de una cadena dada, en un **sistema de numeración** determinado.

La interpretación en hexa debe manejar la base 16 (hexadecimal), la interpretación sería la suma de **pesos en base 16**. 

Hasta ahí parece sencillo, pero no nos olvidemos de un detalle, cada peso va multiplicado por el valor del dígito, y eso era fácil en binario pues puede ser 0 ó 1. 

Como vimos, el sistema hexadecimal usa caracteres alfabéticos para denotar unidades (en ese sistema) mayores a 9 y menores a 16. Entonces esos caracteres deben traducirse a su valor y multiplicar por el peso que corresponde a su posición.

Veamos un ejemplo: supongamos un sistema hexadecimar de 2 caracteres. Entonces, si la cadena es `01` entonces la interpretación i es `16^0`

Veamos otro ejemplo: supongamos un sistema hexadecimar de 3 caracteres. Entonces, si la cadena es `0A` entonces la interpretación i es `10*16^0`

>¿Cuál es la interpretación de la cadena _'A0'_?