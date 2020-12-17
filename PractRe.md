_ **Nombre:** _

*Víctor José*

_ **Apellido:** _

*Matos Coss*

_ **ID:** _

*1093812*

_ **Prof:** _

*Lorenzo Solano*

_ **Asignatura:** _

*Programacion II*

**I) Que es recursividad y que es tail recursion**

La recursividad es una técnica muy empleada en la programación informática y consiste en que una función se llame a sí misma.

La recursividad es un concepto que se indica cuando un método se llama a si mismo. Cuando creamos un método recursivo debemos tener en cuenta que este tiene que terminar por lo que dentro del método debemos asegurarnos de que no se está llamando a si mismo todo el rato, Lo que quiere decir que el ciclo es finito.

Tail recursion es un mecanismo que permite tener funciones recursivas sin temer por posibles desbordamientos de pila. A diferencia de la recursividad normal, donde cada llamada recursiva implica la creación de un nuevo frame en la pila de llamadas (y por lo tanto el peligro de desbordar el tamaño de la pila), en la tail recursion es posible realizar dichas llamadas recursivas reaprovechando el frame de pila anterior y evitando así el desbordamiento.

**I.I) Mencione 2 lenguajes que no soportan recursividad**

Fortran 77

COBOL (primeras versiones)

**I.II) Mencione 2 lenguajes que soportan recursividad, pero no pueden sacar provecho del tail-recursion**

Lisp

SCHEME

**I.III) Mencione 2 lenguajes que pueden realizar la optimización conocida como tail-recursion**

Python

JavaScript

**II) De dos ejemplos de algoritmos recursivos (pseudo-codigo)**

**Integer x**

**Función void sumarNumero(x);**

**Mostrar por pantalla x;**

**Condicional: Si x<0**

**{**

**sumarNumero(x+1)**

**}**

**------------------------------------------------------------------------------------------**

**Integer x**

**Funcion void factorial(x);**

**Condicional: Si x = 0**

**{**

**retornar 1**

**}**

**Sino:**

**{**

**retornar = x \* factorial(x-1);**

**}**

**III) Implemente los siguientes algoritmos con y sin tail recursion**

**III.I) Sumatoria de los números del 1 a n : Sum(n)**

[**https://youtu.be/0o7Q_PcH_5o**](https://youtu.be/0o7Q_PcH_5o)

**III.II) Factorial de N (1 \* 2 \* 3 ... \* n)**

[**https://youtu.be/WEPJoG3PDeY**](https://youtu.be/WEPJoG3PDeY)

**III.III) Máximo común divisor (GCD Euclid's algorithm)**

[**https://youtu.be/5e_dEn_Pad0**](https://youtu.be/5e_dEn_Pad0)

**IV) Para cada algoritmo en el punto III, implemente su versión iterativa**

**IV.I) Sumatoria de los números del 1 a n : Sum(n) -> n == 1 ? n : n + Sum(n - 1);**

[**https://youtu.be/ugGaJwxtxXU**](https://youtu.be/ugGaJwxtxXU)

**IV.II) Factorial de N (1 \* 2 \* 3 ... \* n) : Factorial(n) -> n <= 1 ? n : n \* Factorial(n - 1);**

[**https://youtu.be/7IhZa6jW2vo**](https://youtu.be/7IhZa6jW2vo)

**IV.IV) Máximo común divisor (GCD Euclid's algorithm) : GCD(x, y) -> y == 0 ? x : GCD(y, x % y);**

[**https://youtu.be/IwE1DjL-RZ0**](https://youtu.be/IwE1DjL-RZ0)

**Playlist:**

[**https://www.youtube.com/playlist?list=PL5K8kPa4QpEFWJnPREdQi_VxooLGl57m7**](https://www.youtube.com/playlist?list=PL5K8kPa4QpEFWJnPREdQi_VxooLGl57m7)

