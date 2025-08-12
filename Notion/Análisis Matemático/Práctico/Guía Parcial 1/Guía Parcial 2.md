## Análisis de funciones

### Dominio

- Para el caso de funciones con cocientes
    - Mirar cuándo el denominador se hace cero

### Ceros o raíces

- Cortes en el eje x
    - Tenemos que hacer $y = 0$ y despejar los valores de “x”
    - Verificar que siempre pertenezcan al dominio
    - La coordenada de $CEX = (a; 0)$

### Ordenada al Origen

- Son los cortes sobre el eje y
- Para obtenerlos
    - Reemplazar las “x” por ceros.
    - Verificar que x = 0 pertenezca al dominio. En ese caso, no habrá ordenada al origen
- La coordenada de $CEY = (0; b)$

### Polos

- Aquellos valores exceptuados del dominio
- Relacionado con las asíntotas verticales

### Signos

- Dónde estará nuestra función
- Los intervalos estarán constituidos por
    - Valores excluidos del dominio,
    - Los cortes en el eje “x”
    - $-\infty$ y $+\infty$ para delimitar los intervalos
    - Los intervalos son abiertos. Sus extremos no son tomados en cuenta
- Armamos como una tablita
- Si en un intervalo la función es negativa, aparecerá por debajo del eje “x”
- Si en un intervalo la función es positiva, aparecerá por encima del eje “x”

### Asíntotas

**Asíntota Horizontal**

- Plantear la función dada para cuando x tiende al $\infty$ o $-\infty$
- Si el resultado es un valor finito, entonces hay una asíntota horizontal.
- Si el resultado es infinito, no existe la asíntota horizontal
- Se debe calcular por derecha y por izquierda
- Cuando es $-\infty$, las “x” pasan a tener signo negativo: $\lim\limits_{x \rightarrow -\infty} f(x) = \lim\limits_{x \rightarrow +\infty} f(-x)$
- Por derecha: $\lim\limits_{x \rightarrow \infty} f(x) = k$
- Por izquierda: $\lim\limits_{x \rightarrow -\infty} f(x) = k$
- Se puede utilizar la Regla de L’Hopital

**Asíntota Oblicua**

- En caso de no haber AH, buscamos si hay una asíntota oblicua
- Calcular la pendiente y su ordenada al origen tanto por izquierda como por derecha
- Cálculo de la pendiente por derecha

$$a = \lim\limits_{x \rightarrow \infty} \Bigg[\frac{f(x)}{x}\Bigg]  
\implies a = \begin{cases}  
0 \rightarrow \nexists AO; \ \exists AH\\  
k \neq 0 \rightarrow \exists AO\\  
± \infty \rightarrow \nexists AO; \ \nexists AH  
\end{cases}$$

- Cálculo de la ordenada “b”

$$b = \lim\limits_{x \rightarrow \infty} [f(x) - ax]$$

> [!important]
> 
> 1. Debemos calcular “a”. Si diera infinito o 0, entonces no se puede calcular “b” ya que no hay pendiente
> 2. Luego procedemos a calcular “b”

- Para el caso de la asíntota oblicua por izquierda, se debe tomar $-\infty$, el procedimiento de cálculo es el mismo solo que, al momento de pasar a $+\infty$, las “x” tendrán signo negativo
- La ecuación de la AO: $y = ax + b$

**Asíntota Vertical**

- Aquí se plantea el límite cuando “x” tiende a un valor finito “a”
    - El valor “a” son todos los valores excluidos del dominio
    - También son los valores de los polos
- El cálculo es con los límites laterales.
- Si el resultado de ambos límites laterales es $±\infty$, entonces existe la asíntota vertical. $\lim\limits_{x \rightarrow a} f(x) = ± \infty$
- Si el resultado es un valor finito, entonces no existe la AV pero si un punto vacío en $(x;y) = (a;k)$. $\lim\limits_{x \rightarrow a} f(x) = k$
- El signo determina hacia dónde va la función. Si es positivo, sube por la AV, si es negativo, la función baja por la AV

### Puntos Críticos y Puntos de Inflexión

### Máximos y mínimos

#### Criterio de la primera derivada
> [!important]
> 1. Calcular la derivada primera $f'(x)$
> 2. $f'(x)=0$ para calcular las raíces
> 3. Las raíces de la primera derivada son los **Puntos Críticos** y por ende, posibles Máximos y mínimos
> 4. Calcular la segunda derivada $f''(x)$
> 5. Valuar la segunda derivada con los puntos críticos $f''(pc)$. Según la concavidad, voy a calificar mi extremo relativo en:
> 	1. $f''(pc)>0\to mínimo$
> 	2. $f''(pc)<0\to Máximo$
> 	3. $f''(pc)=0\to Punto\:Inflexión$.
> 6. Calcular el valor de "y", reemplazando los valor de los Puntos Críticos en la ==función original==


### Puntos de inflexión

>[!nota]
>1. Calcular la segunda derivada $f''(x)$
>2. Igualar la segunda derivada a 0 para buscar las raíces $f''(x)=0$
>3. Las raíces son los **Puntos de Inflexión**
>4. Calcular el valor de "y", reemplazando los valores de los Puntos de Inflexión en la ==función original==

### Continuidad

- Se usarán los cálculos de la AV
- Condición de continuidad
    1. La función debe existir en un punto: $\exists f(a)$
    2. Los límites laterales son finitos e iguales, por ende existe el límite en ese punto: $\lim\limits_{x \rightarrow a^-} f(x) = \lim\limits_{x \rightarrow a^+} f(x) \implies \exists \lim\limits_{x \rightarrow a} f(x) = L$
    3. Si el valor de la función en el punto y el límite son iguales: $f(a) = \lim\limits_{x \rightarrow a} f(x)$
- Si no se cumplen alguna de las condiciones, entonces hay una discontinuidad
- Discontinuidad Evitable: cumple con la existencia de límite pero
    1. No existe la función en el punto. $\nexists f(a)$
    2. Existe la función en el punto pero es diferente al límite. $f(a) \neq \lim\limits_{x \rightarrow a} f(x)$
- Discontinuidad No evitable de Primera Especie: surge de la no existencia de límite en el punto
    - Salto finito: Los límites laterales existen pero son distintos y tienen valores finitos distintos
    - Salto infinito: Solo uno de los límites laterales da como resultado un valor infinito
    - Asintótica: Ambos límites laterales son infinitos y hay presencia de AV.
- Discontinuidad No Evitable de Segunda Especie: Uno o ambos límites laterales no existen.


### Propiedades de los logaritmos

![[/image 15.png|image 15.png]]

## Despejar x con logaritmos

![[2025-06-13_19_16_52-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]

![[2025-06-13_19_17_18-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]

![[2025-06-13_19_17_39-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]


