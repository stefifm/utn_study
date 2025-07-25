## Interpretación geométrica

![[/image 14.png|image 14.png]]

- Sea f(x) continua en el intervalo cerrado [a, b]. Sea $P = (x, f(x))$ un punto sobre la curva y $Q = (x+\Delta x, f(x+\Delta x))$ un punto móvil cercano a P en esa curva
- Entre los puntos P y Q será posible trazar una recta que será la ==Recta Secante== a la curva y que denominaremos ==RS==

![[/image 1 4.png|image 1 4.png]]

- La recta secante forma un ángulo α con el semieje positivo de las “x” y tiene una pendiente que viene dada por la tangente trigonométrica del ángulo α $m_{RS} = tg(\alpha)$

- Haremos que $\Delta x$ tienda a cero. A medida que sucede esto, el punto Q se va trasladando sobre la curva y = f(x) hacia el punto P, formándose otras rectas secantes

![[/image 2 5.png|image 2 5.png]]

![[/image 3 5.png|image 3 5.png]]

![[/image 4 4.png|image 4 4.png]]

- Las nuevas rectas tangentes tendrán sus correspondientes pendientes que vendrán dadas al modificar el ángulo alpha.
- El punto Q podrá aproximarse a P tanto como quisiéramos, utilizando el concepto de límites con $\Delta x$ tendiendo a cero.
    - Podemos acercarnos tanto al punto P y que los dos puntos se confundan en uno
- Si ambos puntos se confundan en uno, geométricamente significará que la recta ya no será la Secante a la curva, sino que será la ==Recta Tangente== a la curva en el punto P que denominaremos ==RT==

![[/image 5 4.png|image 5 4.png]]

- La recta tangente forma con el semieje positivo de las “x” un ángulo Beta.
    - La pendiente de RT será la tangente trigonométrica del ángulo Beta $m_{RT} = tg(\beta)$

![[/image 6 3.png|image 6 3.png]]

- Podemos decir que la recta tangente en el punto P es la posición límite de la recta secante cuando Q se mueve hacia P

- Ahora agregamos los incrementos y cociente incremental $\Delta x \ ; \ \Delta y = f(x + \Delta x) - f(x)$
    - Partiendo desde el punto P, podemos incrementar la variable independiente un Δx, obteniendo en abscisas el punto x + Δx
    - La función a partir del punto f(x) se incrementa un Δy, obteniendo en el eje de las ordenadas el punto f(x + Δx)

![[/image 7 3.png|image 7 3.png]]

- Con esto surge el concepto de Cociente incremental $\frac{\Delta y}{\Delta x}$
    - Es la variación de los valores de la función por unidad de variación de la variable independiente “x”. $m_{RS} = tg(\alpha) = \frac{\Delta y}{\Delta x}$
- Si tomamos límite de $\Delta x \rightarrow 0$, tenemos la siguiente igualdad

$$m_{RT} = \lim\limits_{\Delta x \rightarrow 0} m_{RS} = \lim\limits_{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x} = \lim\limits_{\Delta x \rightarrow 0} \frac{f(x+\Delta x) - f(x)}{\Delta x}$$

![[/image 8 3.png|image 8 3.png]]

- Por todo lo anterior, decimos los siguiente

> **Definición de derivada**  
>   
> La derivada de una función es el límite del cociente incremental, cuando el incremento de la variable independiente “x” tiende a cero

$$f'(x) = \lim\limits_{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x}$$

![[2025-06-10_20_00_06-7_Derivada_de_una_funcin_definicin._Interpretacin_geomtrica_y_fsica_de_la_d.jpg]]

$$f'(x) = \lim\limits_{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x} = \lim\limits_{\Delta x \rightarrow 0} tg(\alpha) = \lim\limits_{\alpha \rightarrow \beta} tg(\beta) = m_{RT}$$

- Por lo tanto, la derivada representa el valor de la pendiente de la recta tangente a la curva en el punto considerado

![[/image 9 3.png|image 9 3.png]]

- La tangente del ángulo Beta es le valor número de la función derivada en el punto P y lo definiremos como
    - La derivada de la función en el punto P es el valor de la tangente trigonométrica del ángulo que forma la recta tangente geométrica a la curva respecto a la dirección positiva de las “x”

![[/image 10 2.png|image 10 2.png]]

## Procedimiento general para obtener la derivada de una función

![[2025-06-10_20_05_49-7_Derivada_de_una_funcin_definicin._Interpretacin_geomtrica_y_fsica_de_la_d.jpg]]

- Si el límite existe, lo que se obtiene es la derivada de la función f’(x).

[[Unidad 5 - Parte 2 - Derivadas-Demostraciones]]

[[Unidad 5 - Parte 3 - Derivación Logarítmica-Método de la cadena]]

[[Unidad 5 - Parte 4 - Aplicaciones y Diferencial]]

[[Unidad 5 - Parte 6 - Continuidad-Derivabilidad]]

[[Unidad 5 - Parte 7 - Teoremas]]

[[Unidad 5 - Parte 8 - Derivadas en el Análisis de funciones]]

[[Unidad 5 - Parte 9 - Concavidad-Convexidad]]