Verificador de Número Armstrong

Este es un programa diseñado para determinar si un número entero ingresado por el usuario es un Número Armstrong.

 ¿Qué es un Número Armstrong?

Un Número Armstrong (también conocido como número narcisista) es aquel entero que es igual a la suma de sus propios dígitos elevados a la potencia del número total de dígitos que tiene.

Ejemplo

Para el número 153:

    Tiene 3 dígitos (n=3).

    La verificación es: 13+53+33

    Cálculo: 1+125+27=153

    Como 153 es igual a la suma, es un Número Armstrong.

 Cómo Funciona el Código

El programa utiliza la función num_armstrong para encapsular toda la lógica de la verificación:

    Conteo de Dígitos: El número se convierte a una cadena (str(num)) para poder determinar  la potencia n (número de dígitos) usando len().

    Iteración y Sumatoria: Se utiliza un bucle for para recorrer cada dígito del número.

        Cada dígito se convierte a entero.

        Ese entero se eleva a la potencia n (digitos).

        El resultado de la potencia se acumula en sumatoria.

    Comparación Final: La función compara la sumatoria con el número original (num).

        Si son iguales, devuelve True.

        Si son diferentes, devuelve False.