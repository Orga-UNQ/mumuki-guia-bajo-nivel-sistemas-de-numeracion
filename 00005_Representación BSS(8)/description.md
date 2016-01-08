Para representar valores mediante cadenas binarias, se deben realizar divisiones sucesivas por la base 2 hasta obtener un cociente igual a cero, **tomando cada resto como bits de la cadena**. Por ejemplo. si se necesita representar el número 6:
1. Se divide 6%2 dando un cociente de 3 y un resto 0
2. Se divide 3%2 dando un cociente de 1 y un resto 1
3. Se divide 1%2 dando un cociente de 0 y un resto 1
4. Se construye la cadena desde el ultimo hasta el primer resto: 110


¿Cómo es la cadena que representa al valor 4 en un sistema BSS(8)?