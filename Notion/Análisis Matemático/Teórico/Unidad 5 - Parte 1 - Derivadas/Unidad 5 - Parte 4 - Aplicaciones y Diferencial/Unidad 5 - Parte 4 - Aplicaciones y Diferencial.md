## Diferencial

![[/image 20.png|image 20.png]]

![[/image 1 10.png|image 1 10.png]]

![[/image 2 8.png|image 2 8.png]]

- La recta tangente a la función en el punto P divide a Δy en dos partes
- La función f(x) es continua en [a, b], por definición de derivada: $f'(x) = \lim\limits_{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x}$
    
    - Recordando el Teorema 1 de infinitésimos:
    
    $$y = \alpha(x) + b \implies \lim\limits_{  
    \begin{subarray}{l}  
    x \rightarrow a \\  
    x \rightarrow \infin  
    \end{subarray}  
    } y = b$$
    
    - Podemos reescribir la primera ecuación para obtener α(x): $\alpha(x) = y - b$. Con esto podemos decir que la diferencia entre una función y su límite es un infinitésimo.
- Si $y = \frac{\Delta y}{\Delta x}$ y $b = f'(x)$, entonces

$$\frac{\Delta y}{\Delta x} - f'(x) = \alpha(x) \\  
-----\\  
\frac{\Delta y}{\Delta x} = \alpha(x) + f'(x)\\  
-----\\  
\Delta y = f'(x).\Delta x + \alpha(x).\Delta x$$

- La ecuación $\Delta y = f'(x).\Delta x + \alpha(x).\Delta x$ son las dos partes que la Recta Tangente divide a Δy.

![[/image 3 8.png|image 3 8.png]]

![[/image 4 7.png|image 4 7.png]]

- Trabajando ahora con la tangente del ángulo Beta, nos encontramos con la siguiente igualdad: $tg(\beta) = \frac{Cateto \ Opuesto}{Cateto \ Adyacente} = \frac{Cateto \ Opuesto}{\Delta X} \implies Cateto \ Opuesto = \frac{tg(\beta)}{f'(x)} - \Delta x = f'(x).\Delta (x)$
    - $f'(x).\Delta (x)$ es la parte principal del incremento porque es la parte más grande del gráfico. Es la que contiene a la derivada
    - $\alpha(x).\Delta x$ Es un infinitésimo de orden superior porque tiende a cero mucho más rápido que la otra parte
- Entonces, podemos decir que de la ecuación $\Delta y = f'(x).\Delta x + \alpha(x).\Delta x$
    - La parte $f'(x).\Delta x$ se la denomina diferencial de la función y tiene la notación de “dy”. $dy = f'(x).\Delta x$
- Reescribimos la ecuación que divide a Δy

$$\Delta y = f'(x).\Delta x + \alpha(x).\Delta x \\  
-----\\  
dy = f'(x).\Delta x\\  
-----\\  
\Delta y = dy + \alpha(x).\Delta x$$

- Como “x” es la variable independiente, entonces Δx = dx. Por lo que, la ecuación queda $\Delta y = dy + \alpha(x).d x$
    - Y para cuando $\Delta x \rightarrow 0$, el último término se anula, por lo que $\Delta y \approx dy$, aproximado, pero nunca igual
    - Esto es usado para cálculo aproximados y estimación de errores
- La derivada puede ser considerada como la razón del diferencial de la función respecto al diferencial de la variable independiente “x”

![[1000002056.png]]

![[1000002057.png]]

- Geométricamente, la diferencial $dy$ mide la variación de la recta tangente cuando pasa de un punto al punto incrementado
    - En cambio, $\Delta y$ mide el cambio que hay sobre la curva cuando a “x” se le aplica un incremento $\Delta x$

![[/image 5 6.png|image 5 6.png]]

![[/image 6 5.png|image 6 5.png]]

## Aplicaciones de la derivada

### Aproximación lineal de la recta tangente

![[/image 7 5.png|image 7 5.png]]

- Conozco la pendiente de la recta tangente $m_{RT}= f’(a)$ y un punto P =(a, f(a))
- Tenemos la ecuación de la recta que pasa por el punto: $y-y_1 = m (x-x_1)$ Y los reemplazamos con los datos que tenemos

$$y-f(a) = f'(a)(x-a)\\  
y = f'(a)(x-a)+f(a)\\  
-------\\  
L(x) = f'(a)(x-a)+f(a)$$

- La última ecuación es la linealización de la recta tangente
- Utilizamos la recta tangente en el punto mencionado como una aproximación a la curva de la función cuando “x” está cerca de “a”

![[1000002002.png]]