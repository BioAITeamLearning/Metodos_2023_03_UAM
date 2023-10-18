---
title: Unidad 5
---
# Unidad 5: Diferenciación e Integración

## Contenido de la unidad

<img src="https://github.com/BioAITeamLearning/Metodos_2023_03_UAM/blob/main/images/contenidoU5.png?raw=true"/>

## Formulas de diferenciación: Recordemos

La derivada de una función $f(t)$ en un punto $t$ se define como:

$$ f'(t) = \frac{f(t+\Delta t)-f(t)}{\Delta t} $$

Donde $\Delta t$ es un número pequeño. Este numero lo llamaremos h y debe ser muy pequeño sin ser explicitamente cero.


$$ f'(t) = \frac{f(t+h)-f(t)}{h} $$


Se puede ver como una ecuación iterativa

$$ f'(t_i) = \frac{f(t_{i+1})-f(t_i)}{h} $$

h es el incremento (normalmente pequeño)

$$h = \frac{[max(t) - min(t)]}{lenght(t)}$$
