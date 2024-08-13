## factorial de un numero 
Hoy vamos a ver cómo se calcula el factorial de un número. Calcular factoriales es muy sencillo, vamos a ver en qué consiste:

#### ¿Qué es la función factorial?

La función factorial se representa con un signo de exclamación "!" detrás de un número. Esta exclamación quiere decir que hay que multiplicar todos los números enteros positivos que hay entre ese número y el 1.
Por ejemplo:

---

6! = 1 x 2 x 3x4x5x6= 720
---
A este número, 6! le llamamos generalmente "6 factorial", aunque también es correcto decir "factorial de 6".

En tu calculadora podrás ver una tecla con "n!" o "x!". Esta tecla te servirá para calcular directamente el factorial del número que quieras.

Algunos ejemplos de factoriales

Vamos a ver algunos ejemplos más de factoriales:

---
4! 1 x 2 x 3 x 4 = 24
---
10! 1 x 2 x x 9 x 10 = 3628800
---
100! 1 x 2 x 3 x x 98 x 99 x 100 ≈ 9,33 x 10157
---
Como ves, 100! es enorme...

Y, ¿qué hacemos con los números más pequeños? 1 factorial es, lógicamente, 1, ya que multiplicamos 1 x 1:

Como ves, 100! es enorme...

Y, ¿qué hacemos con los números más pequeños? 1 factorial es, lógicamente, 1, ya que multiplicamos 1 x 1:

---
1! = 1
---

Pero, ¿cómo podemos calcular el 0 factorial? Bueno, esto no tiene sentido cuando aplicamos la norma de que hay que multiplicar todos los números enteros positivos entre el 0 y el 1, ya que 0 x 1 es 0.

Al final, por convenio se ha acordado que lo más útil es que el 0 factorial sea igual a 1. Así que recuerda:

---
0! = 1
---

### En Kotlin seria de esta forma:

fun factorial(n: Int): Long

{

if (n <= 1)

{ return 1

} return n factorial(n-1)

} fun main()

{

val number 5

println("El factorial de $number es ${factorial(number)}")

}

Este codigo en Kotlin calcula el factorial de un numero utilizando recursividad.

Funcion factorial
