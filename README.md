# Examen de JS

## Ejercicio 1
Crea una función que acepte un array de números y devuelva la suma de los números pares del array.

## Ejercicio 2
Usando un bucle `for`, escribe una función que acepte un número y muestre por consola la lista de números desde el 0 al valor tecleado.

## Ejercicio 3
Escribe una función que acepte un número y muestre por consola una cuenta atrás, es decir, una lista de numeros desde el número tecleado hasta el 0.

## Ejercicio 4
Escribe una función que acepte un número y devuelva la lista de todos los números pares del 0 al número introducido.

## Ejercicio 5
Escribe una función que acepte un número e imprima por consola la tabla de multiplicar de dicho número (del 0 al 10) siguiendo este patrón:
```javascript
num x 0 = 0
num x 1 = ...
num x 2 = ...
// etc.
```

## Ejercicio 6
Escribe una función que acepte un número e imprima por consola todos los números del 0 a dicho número que sean múltiplos de 3. Recuerda: un número es múltiplo de N cuando al dividirlo por N el resto es 0.

## Ejericio 7
El cálculo de la letra del Documento Nacional de Identidad (DNI) es un proceso matemático sencillo que se basa en obtener el resto de la división entera del número de DNI y el número 23. A partir del resto de la división, se obtiene la letra seleccionándola dentro de un array de letras.

El array de letras es:
```javascript
const letras = ['T', 'R', 'W', 'A', 'G', 'M', 'Y', 'F', 'P', 'D', 'X', 'B', 'N', 'J', 'Z', 'S', 'Q', 'V', 'H', 'L', 'C', 'K', 'E', 'T'];
```
  
Por tanto si el resto de la división es `0`, la letra del DNI es la `T` y si el resto es `3` la letra es la `A`. Con estos datos, elabora una función que:

1. Acepte como parámetros un número y una letra de DNI.

2. Almacene en una variable el número y letra de DNI indicado por el usuario.

3. En primer lugar (y en una sola instrucción), se debe comprobar si el número es menor que `0`o mayor que `99999999`. Si ese es el caso, se mostrará un mensaje al usuario indicando que el número proporcionado no es válido, y el programa no muestra más mensajes.

4. Si el número es válido, se calcula la letra que le corresponde según el método explicado anteriormente.

5. Una vez calculada la letra, se debe comparar con la letra indicada por el usuario. Si no coinciden, se mostrará un mensaje al usuario diciéndole que la letra que ha indicado no es correcta. En caso contrario, se mostrará un mensaje indicando que el número y la letra de DNI son correctos.
