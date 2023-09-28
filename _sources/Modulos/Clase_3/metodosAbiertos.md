---
title: "Métodos abiertos"
---

# Métodos abiertos

Los métodos abiertos suelen ser más eficientes que los métodos cerrados, además tiene la ventaja de no tener que saber el intérvalo en el que se encuentra la raíz. Sin embargo, estos métodos no garantizan la convergencia a la raíz, por lo que se debe tener cuidado al utilizarlos.

::::{grid}
:gutter: 3

:::{grid-item-card}
:class-body: text-right
:class-header: bg-light text-center
```{dropdown} Métodos cerrados
* Parten desde un intérvalo que contiene la raíz
* Son convergentes
* Bisección
* Falsa posición  
```
:::

:::{grid-item-card}
:class-body: text-right
:class-header: bg-light text-center
```{dropdown} Métodos abiertos
* Parten de 1 o 2 valores iniciales
* Pueden ser convergentes o divergentes
* Método de Newton-Raphson
* Método de iteración de punto fijo
* Método de la secante
```
:::

::::

<img src="../../_static/images/Met_abiertos_cerrados.png"/>