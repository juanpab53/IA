# Sesión 01 - Ordenamiento de tres números

## Descripción

Esta sesión trabaja con la lógica de ordenamiento de tres números utilizando dos enfoques distintos en pseudocódigo:

- una solución con condicionales,
- y otra con ciclos.

La actividad tiene como objetivo mostrar cómo se pueden resolver el mismo problema con distintas estructuras de control, comparando claridad, eficiencia y estilo de programación.

## Archivos incluidos

- `OrdenarTresNumeros(Condicionales).psc`: implementación que compara pares de números de forma secuencial con condiciones.
- `OrdenarTresNumeros(Ciclos).psc`: versión equivalente que usa bucles para automatizar las comparaciones.

## Objetivo

Ordenar tres números ingresados por el usuario de menor a mayor, mostrando:

- la lista inicial,
- las comparaciones realizadas,
- los intercambios realizados cuando corresponden,
- y el resultado final.

## Lógica del problema

El algoritmo recibe tres valores y revisa las relaciones entre ellos para colocar el menor primero, luego el intermedio y finalmente el mayor.

Se realizan comparaciones entre:

- el primer y segundo valor,
- el segundo y tercer valor,
- y una segunda revisión para asegurar que el orden final quede correcto.

## Implementación con condicionales

La versión con condicionales hace cada comparación explícitamente usando `Si ... Entonces`.

Se destacan estas características:

- lectura de los tres números,
- comparación directa entre pares,
- intercambio de valores mediante una variable auxiliar,
- impresión de cada paso del proceso,
- y resultado final ordenado.

Este enfoque es útil para aprender la lógica del ordenamiento paso a paso y comprender cómo se comparan y reorganizan los valores.

## Implementación con ciclos

La versión con ciclos reutiliza la estructura repetitiva para realizar varias comparaciones sin repetir código.

Se utilizan:

- un arreglo para guardar los tres números,
- un ciclo `Para` para recorrer las pasadas,
- un segundo ciclo para comparar cada par de elementos,
- y una variable auxiliar para intercambiar valores.

Este enfoque es más compacto y refleja mejor la idea de algoritmos de ordenamiento más generales.
