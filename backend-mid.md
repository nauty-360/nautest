## Problema 

Se te entregan ${n}$ palabras en una cadena de texto. Algunas palabras pueden repetirse. Por cada palabra, muestra su número de ocurrencias. El orden de salida debe corresponder con el orden de aparición en la cadena de entrada. Para mayor claridad, por favor lee el ejemplo de entradas y salidas en la parte inferior.

**Nota:** cada fin de línea es indicado con un caracter de retorno ("\n")

### Restricciones:

$1 \ge n \ge {10^5}$ 

La suma del largo de todas las palabras no excede $10^6$. Todas las palabras se componen de letras del alfabeto inglés (sin acentos ni ñ).

### Formato de ingreso de datos
La primer linea contiene el número entero, $n$

Las siguientes $n$ líneas contienen una palabra cada una.

### Formato de salida
Debes mostrar 2 líneas de salida.

En la primer linea debes mostrar la cantidad de palabras distintas que hay en la cadena de entrada. 

En la segunda línea, debes mostrar el numero de ocurrencias de cada palabra distinta de acuerdo al orden de aparición en la cadena de entrada.

### Ejemplo de entrada:

6
barco
casa
barco
perro
lote
lote

### Ejemplo de salida

4
2 1 1 2

### Explicación

Hay **4** palabras diferentes. Luego, "barco" aparece dos veces en la cadena de entrada, "casa" aparece una vez, "barco" se omite porque ya se contabilizó antes, luego "perro" aparece una vez, y finalmente "lote" aparece dos veces. El orden de aparición de "barco", "casa", "perro" y "lote" corresponde a la salida.


NOTA: el ejercicio ha sido extraído de [hackerrank.com](https://www.hackerrank.com/)
