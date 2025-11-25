 Calculadora de Mínimo Común Múltiplo (MCM)

Este programa en Python calcula el Mínimo Común Múltiplo (MCM) de dos números enteros positivos utilizando el método de sumas sucesivas (también conocido como generación de múltiplos).

¿Qué es el MCM?

El Mínimo Común Múltiplo (MCM) de dos o más números es el número positivo más pequeño que es múltiplo de todos ellos.

Ejemplo: El MCM de 4 y 6 es 12, porque 12 es el primer número que aparece en la lista de múltiplos de ambos:

    Múltiplos de 4: 4, 8, 12, 16, 20, ...

    Múltiplos de 6: 6, 12, 18, 24, ...

 Cómo Funciona el Código

El programa utiliza una función llamada calcularmcm que implementa la estrategia de "carrera de múltiplos":

    Inicialización: Dos variables (suma1 y suma2) se inicializan con los valores de num1 y num2. Estos son los primeros múltiplos.

    Bucle while: El programa entra en un bucle que se ejecuta hasta que suma1 y suma2 sean iguales.

    Incremento: En cada iteración, se verifica qué variable (suma1 o suma2) tiene el valor menor. El valor menor es incrementado sumándole su número original. Esto garantiza que el valor más pequeño "alcance" al otro, encontrando el primer punto de coincidencia.

    Resultado: Cuando suma1 == suma2, ese valor es el MCM y es devuelto por la función.
    