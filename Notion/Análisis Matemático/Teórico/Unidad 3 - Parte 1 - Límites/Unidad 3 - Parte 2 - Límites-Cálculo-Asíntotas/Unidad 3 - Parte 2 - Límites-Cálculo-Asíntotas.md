## Cálculo analítico de límites

- El límite de f(x) cuando se aproxima a “a” no depende del valor de f en x = a
- Pero puede darse el caso de que el límite sea f(a)
- Cuando esto sucede, se puede evaluar el límite por sustitución directa

$$\lim\limits_{x \rightarrow a} f(x) = f(a)$$

- Las funciones que tienen este comportamiento son continuas en x = a
- La sustitución directa es válida para funciones polinomiales y racionales cuyos denominadores no se anulen en el punto considerado

![[Captura_de_pantalla_2025-06-04_215357.png]]

### Teorema

> **Funciones que coinciden en todo, salvo en el punto**  
>   
> Sea “c” un número real y f(x) = g(x) para todo x distinto de “c” en un intervalo abierto que contiene a “c”. Si existe el límite de g(x) cuando x se aproxima a c, entonces también existe el límite de f(x) y

$$\lim\limits_{x \rightarrow c} f(x) = \lim\limits_{x \rightarrow c} g(x)$$

![[/image 16.png|image 16.png]]

![[/image 1 6.png|image 1 6.png]]

![[/image 2 6.png|image 2 6.png]]

## Límite infinito

Sucede cuando

$$\lim\limits_{x \rightarrow a} f(x) = \infin$$

> **Definición:** Sea f una función definida en ambos lados de “a”, excepto posiblemente en “a”, el límite de “x” que tiende a “a” será igual al infinito si y sólo si para todo M > 0 exista un delta positivo tal que si “x” esta en el entorno reducido de “a” entonces la distancia de f(x) es mayor a “M”.  
>   
> Significa que los valores de f(x) se pueden hacer arbitrariamente grandes haciendo que “x” se acerque suficientemente a “a”, pero no es igual a “a”  

$$\lim\limits_{x \rightarrow a} f(x) = \infin \ \iff \forall M > 0 \ \exists \delta > 0 /0<|x-a|<\delta \implies |f(x)| > M$$

- Valor absoluto de f(x) porque puede ser positivo o negativo o $+\infin \ o \ -\infin$

- **Para los límites infinito, puede que el límite no exista. Por el contrario, indica la razón de su no existencia al expresar el comportamiento de la función. Ésta se vuelve más y más grande, es decir, se incrementa sin límite a medida que “x” se acerca más y más a “a”.**

- En vez de épsilon aparece M y estará lo más arriba del eje “y”

![[1000001893.png]]

  

### Asíntotas verticales

- Con el uso de límites infinitos, podremos calcular las asíntotas verticales de una función

> Si f(x) tiende a infinito cuando x tiende a “a” por la derecha o por la izquierda, se dice que la recta x = a es una asíntota vertical de la función

![[/image 3 6.png|image 3 6.png]]

![[1000001894.png]]

- Para calcular las asíntotas verticales, se tiene que evaluar la función por izquierda y por derecha
- Se puede llegar tan alto como se desee, tomando “x” suficientemente cercana a 0. No importa que tan alto está M, la gráfica va más alto
- Se puede llegar tan bajo como se desee, tomando “x” suficientemente cercana a 0. No importa que tan bajo está -M, la gráfica va más bajo

![[1000001895.png]]

![[1000001896.png]]

![[1000001897.png]]

![[1000001898.png]]

## Límite en el infinito

- Se refiere cuando $\lim\limits_{x \rightarrow ±\infin} f(x) = L$

> Sea f una función definida en algún intervalo (a, [∞](https://en.wikipedia.org/wiki/%E2%88%9E)). Entonces, el $\lim\limits_{x \rightarrow \infin} f(x) = L$, significa que los valores de f(x) se pueden aproximar a L tanto como desee, si escoge una “x” suficientemente grande.

> Habrá un $\lim\limits_{x \rightarrow \infin} f(x) = L$ si y sólo si para todo épsilon mayor a cero existirá un número N tal que si x es mayor a N, entonces la distancia entre la función y el límite es menor a épsilon.

$$\lim\limits_{x \rightarrow \infin} f(x) = L \iff \forall \epsilon > 0 \ \exists N/x>N \implies |f(x) - L| < \epsilon$$

![[1000001899.png]]

- Las asíntotas horizontales se pueden cortar mientras las asíntotas verticales no.
- N es el último corte a la función que hace algunas de las proyecciones de L (L + épsilon; L - épsilon)
- Solo se cumple si “x” es mayor a N. Si es menor a N, entonces la condición no se cumple ya que $|f(x) - L|$ será mayor que épsilon

![[/image 4 5.png|image 4 5.png]]

- Esto nos permitirá calcula las asíntotas horizontales

![[/image 5 5.png|image 5 5.png]]

![[/image 6 4.png|image 6 4.png]]

![[/image 7 4.png|image 7 4.png]]

![[1000001900.png]]

![[1000001901.png]]

![[1000001902.png]]

![[1000001903.png]]

![[1000001904.png]]

![[2025-06-06_21_01_18-Suite_Calculadora_-_GeoGebra.jpg]]

## Asíntotas oblicuas

> **Definición de asíntota**  
> Si la distancia entre una recta y un punto M variable sobre la curva tiende a cero, cuando el punto M tiende al infinito, esta recta recibe el nombre de asíntota de la curva  

- Las asíntotas oblicuas aparecen en funciones racionales donde el grado del numerador es 1 grado más grande que el del denominador.

![[/image 8 4.png|image 8 4.png]]

- Sea $M(x,y)$ un punto en la curva y $N(x_1,\overline{y})$ un punto en la asíntota

![[/image 9 4.png|image 9 4.png]]

![[/image 10 3.png|image 10 3.png]]

- M y N más van a acercar mientras avanzan por la función hacia la derecha
- La ecuación de la recta marcada en puntos es $y = ax+b$ y será una asíntota oblicua de la función f(x) si y solo si, si tomamos límite de “x” que tiende al infinito de la diferencia entre la función f(x) y la ecuación de la recta con M y N más cerca, sea igual a cero

$$\lim\limits_{x \rightarrow \infin} [f(x)-(ax+b)] = 0$$

### Cálculo de a y b

![[2025-06-10_13_13_59-6_Continuidad._Continuidad_en_un_punto_y_en_un_intervalo._Discontinuidades._Prop.jpg]]

![[2025-06-10_13_14_11-6_Continuidad._Continuidad_en_un_punto_y_en_un_intervalo._Discontinuidades._Prop.jpg]]

- Si uno de los límites no existe, la función no tendrá asíntota
- Si hay asíntota horizontal, no habrá oblicua y viceversa.
- El cálculo de la asíntota oblicua por izquierda es similar al de la derecha, solo que $x \rightarrow -\infin$.
    - Luego, deberemos volver al infinito positivo y para ello, todas las x cambian de signo.

![[/image 11 2.png|image 11 2.png]]

![[/image 12 2.png|image 12 2.png]]