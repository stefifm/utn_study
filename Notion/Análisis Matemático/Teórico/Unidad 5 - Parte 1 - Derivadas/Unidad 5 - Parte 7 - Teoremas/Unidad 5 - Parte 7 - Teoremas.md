## Teorema de Rolle

> Si una función f(x) es continua en el intervalo cerrado [a, b] y derivable en el intervalo abierto (a, b) y la función valuada en el extremo inferior del intervalo es igual a la función valuada en el extremo superior del mismo (f(a) = f(b)), entonces existe al menos un punto interior $c \in (a,b)$ en el cual la derivada en ese punto sea igual a cero: $f'(c) = 0$

![[2025-06-11_16_35_30-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]

![[2025-06-11_16_35_41-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]

![[2025-06-11_16_37_23-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

## Teorema de Langrage o del Valor Medio del Cálculo Diferencial

> Si una función y = f(x) es continua en el intervalo cerrado [a, b] y derivable en el intervalo abierto (a, b), entonces existe al menos un punto interior $c \in (a,b)$ que verifica lo siguiente: $\frac{f(b)-f(a)}{b-a} = f'(c)$

![[/image 22.png|image 22.png]]

- Mirando la gráfica, podemos decir que la parte de la ecuación $\frac{f(b)-f(a)}{b-a}$ es la pendiente de la recta secante
- Mientras que $f'(c)$ es un número que representa la pendiente de la recta tangente
- Con esta información, podemos redefinir el teorema de Langrage

> Si una función y = f(x) es continua en el intervalo cerrado [a, b] y derivable en el intervalo abierto (a, b), entonces existe al menos un punto interior $c \in (a,b)$ en donde la pendiente de la recta secante sea igual a la pendiente de la recta tangente

- Bajo esta nueva definición, las rectas tangentes y secantes son paralelas.
- Puede haber más de un punto que pertenezcan al intervalo (a, b) y por supuesto, las pendientes de las rectas secantes y tangentes son iguales en esos dos.

![[2025-06-11_16_51_51-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

![[2025-06-11_16_54_10-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

## Teorema de Cauchy

> Si f y g son funciones continuas en el intervalo cerrado [a, b] y derivables en el intervalo abierto (a, b) y para todo x que pertenezca a ese intervalo abierto, bajo la condición de que la derivada de “g” sea distinto de cero, entonces existe un punto “c” que pertenece al intervalo (a, b) tal que: el cociente de las diferencias de f(b), f(a) y g(b), g(a) sean iguales al cociente de sus respectivas derivadas en el punto “c”

$$\frac{f(b)-f(a)}{g(b)-g(a)} = \frac{f'(c)}{g'(c)}$$

![[2025-06-11_17_03_19-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

![[2025-06-11_17_09_25-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

![[2025-06-11_17_10_11-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

![[2025-06-11_17_12_30-video1496086341.mp4_-_Google_Drive_-_Brave.jpg]]

- Este teorema sirve de base para trabajar con la Regla de L’Hopital

## Regla de L’Hopital

- Se aplica de forma directa para las determinaciones $\frac{0}{0}$ y $\frac{\infin}{\infin}$
- Para el resto de indeterminaciones, se necesitan algunos procedimientos algebraicos extras.
- No cualquier límite se puede trabajar normalmente con límites normales o límites notables.
- Condiciones
    - f y g funciones derivables
    - g’(x) debe ser distinto de cero
    - Intervalo abierto que contiene al punto “a” (excepto posiblemente en a)
    - Y que $\lim\limits_{x \rightarrow a} f(x) = 0; \ \lim\limits_{x \rightarrow a} g(x) = 0$
- Entonces: $\lim\limits_{x \rightarrow a} \frac{f(x)}{g(x)} = \lim\limits_{x \rightarrow a} \frac{f'(x)}{g'(x)} = L$, siempre que el límite exista
    - Esto producirá una indeterminación $\frac{0}{0}$ y se debe derivar al numerador y denominador por separado.
    - Si se vuelve a producir la indeterminación, se vuelve a derivar numerador y denominador.
    - Se seguirá con este proceso hasta levantar la indeterminación.
- Este procedimiento también es válido para la indeterminación $\frac{\infin}{\infin}$

### Interpretación geométrica de la Regla de L’Hopital

- Se aplica la derivada del numerador y denominador por separado porque esta basado en Cauchy y por el concepto de linealización de la recta tangente: es más fácil trabajar con rectas que con curvas
    - La linealización sirve para un entorno de un determinado punto y no para cualquier valor de “x”

![[/image 1 12.png|image 1 12.png]]

- Tomando la ecuación de la recta en un punto para f y g

$$y-f(a) = f'(a)(x-a)\\  
------- \\  
y-g(a) = g'(a)(x-a)$$

- Sabiendo que f(a) y g(a) valen cero, y despejando “y”, entonces nos queda la siguiente ecuación

$$y = f'(a)(x-a)\\  
------- \\  
y = g'(a)(x-a)$$

- Y teniendo en cuenta que las derivadas de las funciones en el punto “a” representan la pendiente de la recta tangente, nos queda así

$$y = m_1(x-a)\\  
------- \\  
y = m_2(x-a)\\  
--------\\  
m_1 = f'(a); \ m_2 = g'(a)$$

- Si reemplazo el cociente de las funciones por las linealizaciones, obtenemos la relación de sus derivadas o cociente de las pendientes

$$\frac{m_1(x-a)}{m_2(x-a)} = \frac{m_1}{m_2}$$

![[2025-06-11_19_15_43-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]

### Procedimiento para el resto de indeterminaciones

Para la indeterminación $(0.\infin); \ (\infin - \infin)$

![[2025-06-11_19_27_40-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]

![[2025-06-11_19_27_50-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]

- El factor que debe pasar al denominador dependerá de lo sencillo que sea fácil para levantar la indeterminación.

**Para las indeterminaciones** $1^\infin; \ 0^0; \ \infin^0$

- Se procede con la utilización de logaritmo natural

![[2025-06-11_19_58_42-10_Derivadas_sucesivas._Teoremas_sobre_las_funciones_derivables._Funciones_creci.jpg]]