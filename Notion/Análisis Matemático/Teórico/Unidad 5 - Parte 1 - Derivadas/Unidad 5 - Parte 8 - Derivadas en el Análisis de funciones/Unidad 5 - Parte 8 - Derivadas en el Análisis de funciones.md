## Extremos de una función

![[/image 23.png|image 23.png]]

- En la gráfica se observa que la función crece entre los puntos A y B
    - Decrece entre B y C
    - Y vuelve a crecer entre C y D
- Tomamos los intervalos
    - La función crece en el intervalo cerrado [a, b]
    - En el intervalo [b, c] la función decrece
    - Y en [c, d], la función vuelve a crecer
- Del intervalo [a, b]
    - Si tomamos dos valores de $x_1$ y $x_2$, donde $x_1$ es menor a $x_2$. Si encontramos que la función valuada en $x_1$ $f(x_1)$ es menor a la función valuada en $x_2$ $f(x_2)$, concluimos que la función es creciente.
- Del intervalo [b, c]
    - Volvemos a tomar dos valores de $x_1$ y $x_2$. En esta ocasión, $x_1 > x_2$ y por ende, la función $f(x_1) > f(x_2)$ y en conclusión, la función es decreciente.

![[/image 1 13.png|image 1 13.png]]

### Funciones monótonas

- Una función es estrictamente monótona en un intervalo si es creciente o decreciente sobre todo el intervalo

![[/image 2 10.png|image 2 10.png]]

![[/image 3 10.png|image 3 10.png]]

- Para el caso de $x^3$, la función es estrictamente monótona en todo su dominio

**Funciones monótonas en un intervalo**

![[/image 4 9.png|image 4 9.png]]

### Funciones monótonas y la derivada

- $f’(x)$ representa a la pendiente de la tangente trigonométrica en un punto $(x, f(x))$ y nos dará la siguiente información
    - La dirección de la curva cuando avanza la recta en cada punto
    - Si la función es creciente o decreciente
- Si la pendiente de la recta tangente es positiva
    - La función es creciente
    - $f’(x) > 0$
- Si la pendiente de la recta tangente es negativa
    - La función decrece
    - $f’(x) < 0$
- Si la pendiente de la recta tangente es 0
    - Entonces, $f’(x) = 0$

**Demostración con el uso del teorema de Lagrange**

- Tomamos dos valores de $x_1$ y $x_2$ dentro del intervalo [a, b], con $x_1 < x_2$ y $f(x_1) < f(x_2)$
- Lagrange decía que la pendiente de la recta secante $\frac{f(b)-f(a)}{b-a}$ tiene que ser igual a la pendiente de la recta tangente $f’(c)$
- Aplicando el teorema de Lagrange en el intervalo cerrado [a, b], la ecuación queda:
    - $\frac{f(x_2)-f(x_1)}{x_2-x_1} = f’(c)$
    - Y si queremos saber el numerador: $f(x_2)-f(x_1) = f’(c)(x_2-x_1)$
    - $f’(c)$ tiene que ser positivo ya que las rectas tangentes tienen pendiente positiva en todo el intervalo
    - $(x_2-x_1)$ también dará un número positivo ya que $x_1 < x_2$
    - Por ende, todo el lado derecho de la igualdad es positivo, entonces $f(x_2)-f(x_1) >0$ y si despejamos, $f(x_2) > f(x_1)$ o que es lo mismo, $f(x_1) < f(x_2)$

![[/image 5 8.png|image 5 8.png]]

**La recta tangente y determinación gráfica de la primera derivada**

![[2025-06-12_11_40_30-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

- Dividimos el gráfico en intervalos
- Buscamos un punto extremo. De encontrarlo, será la raíz de la primera derivada
- Dibujamos rectas tangentes en ciertos puntos de los intervalos.
    - Si las pendientes son positivas, entonces la curva de la primera derivada estará por encima del eje “x”
    - Si las pendientes son negativas, entonces la curva de la primera derivada estará por debajo del eje “x”

### Extremos Absolutos y Relativos o Locales

- Máximo local o relativo: Sea c un número que pertenece al dominio D de una función f, entonces f(c) es máximo local o relativo si existe un intervalo abierto j que contiene al punto c tal que la función en ese punto sea mayor en todo ese intervalo.
- Mínimo local o relativo: Habrá un mínimo local o relativo en c si existe un intervalo abierto l que lo contenga tal que la función valuada en ese punto sea el menor en todo ese intervalo.
- Máximo absoluto: es el mayor valor de toda la función
- Mínimo absoluto: es el menor valor de toda la función

![[/image 6 7.png|image 6 7.png]]

![[2025-06-12_12_05_58-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

### Teorema de Fermat

> Si f tiene un extremo local en c y si existe la derivada en c f’(c), entonces la derivada f’(c) es igual a 0

- Si se presenta un extremo en x = c y la función es derivable en ese punto, la recta tangente a la curva en ese punto es horizontal

![[/image 7 7.png|image 7 7.png]]

**Número crítico**

- x = c es un número crítico de una función si c pertenece al dominio de la función tal que la derivada en ese punto sea 0 o no exista
- Los extremos relativos solo se presentan en puntos críticos

> [!important] **Condición necesaria y no suficiente para la existencia de extremos relativos**<br><br>Dada la función y = f(x), la condición necesaria y no suficiente para que exista un máximo o mínimo relativo en el punto x= c, es que la derivada primera en ese punto sea nula ya que la curva allí no crece ni decrece.<br>Desde el punto de vista geométrico, la tangente es horizontal.<br>Los puntos donde la derivada primera se anula se llaman puntos críticos<br>

> [!important] **Condición suficiente para la existencia de extremos relativos**<br>**1) Criterio de la Derivada Primera**<br>
> 
> ![[/image 8 6.png|image 8 6.png]]
> 
> ![[/image 9 6.png|image 9 6.png]]

> [!important]
> 
> 1. **Criterio de la Segunda Derivada**
> 
> ![[/image 10 4.png|image 10 4.png]]
> 
> - Esta prueba es incierta cuando f’’(c) = ya que puede haber un máximo, un mínimo o podría no haber máximo/mínimo. También falla cuando f’’(c) no existe
>     - Por esta razón, se debe usar la prueba de la primera derivada ya que no tiene fallas y es la más fácil de implementar

> [!important] **Procedimiento para el cálculo de extremos**
> 
> 1. Derivar la función: $y’ = f’(x)$
> 2. Condición necesaria:
>     1. $f'(x) = 0 \implies \begin{cases} x_{c1}\\ x_{c2}\\ ...\\ x_{cn} \end{cases} \implies Raíces \ de \ la \ primera \ derivada$
> 3. Condición suficiente
>     1. Criterio de la primera derivada
>     2. Criterio de la segunda derivada
> 4. Reemplazar los puntos críticos en la función para determinar sus coordenadas
> 
> ![[1000002026.png]]
> 
> ![[1000002027.png]]