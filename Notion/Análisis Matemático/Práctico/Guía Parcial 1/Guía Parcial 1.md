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
    - $-\infin$ y $\infin$ para delimitar los intervalos
    - Los intervalos son abiertos. Sus extremos no son tomados en cuenta
- Armamos como una tablita
- Si en un intervalo la función es negativa, aparecerá por debajo del eje “x”
- Si en un intervalo la función es positiva, aparecerá por encima del eje “x”

### Asíntotas

**Asíntota Horizontal**

- Plantear la función dada para cuando x tiende al $\infin$ o $-\infin$
- Si el resultado es un valor finito, entonces hay una asíntota horizontal.
- Si el resultado es infinito, no existe la asíntota horizontal
- Se debe calcular por derecha y por izquierda
- Cuando es $-\infin$, las “x” pasan a tener signo negativo: $\lim\limits_{x \rightarrow -\infin} f(x) = \lim\limits_{x \rightarrow +\infin} f(-x)$
- Por derecha: $\lim\limits_{x \rightarrow \infin} f(x) = k$
- Por izquierda: $\lim\limits_{x \rightarrow -\infin} f(x) = k$
- Se puede utilizar la Regla de L’Hopital

**Asíntota Oblicua**

- En caso de no haber AH, buscamos si hay una asíntota oblicua
- Calcular la pendiente y su ordenada al origen tanto por izquierda como por derecha
- Cálculo de la pendiente por derecha

$$a = \lim\limits_{x \rightarrow \infin} \Bigg[\frac{f(x)}{x}\Bigg]  
\implies a = \begin{cases}  
0 \rightarrow \nexists AO; \ \exists AH\\  
k \neq 0 \rightarrow \exists AO\\  
± \infin \rightarrow \nexists AO; \ \nexists AH  
\end{cases}$$

- Cálculo de la ordenada “b”

$$b = \lim\limits_{x \rightarrow \infin} [f(x) - ax]$$

> [!important]
> 
> 1. Debemos calcular “a”. Si diera infinito o 0, entonces no se puede calcular “b” ya que no hay pendiente
> 2. Luego procedemos a calcular “b”

- Para el caso de la asíntota oblicua por izquierda, se debe tomar $-\infin$, el procedimiento de cálculo es el mismo solo que, al momento de pasar a $+\infin$, las “x” tendrán signo negativo
- La ecuación de la AO: $y = ax + b$

**Asíntota Vertical**

- Aquí se plantea el límite cuando “x” tiende a un valor finito “a”
    - El valor “a” son todos los valores excluidos del dominio
    - También son los valores de los polos
- El cálculo es con los límites laterales.
- Si el resultado de ambos límites laterales es $±\infin$, entonces existe la asíntota vertical. $\lim\limits_{x \rightarrow a} f(x) = ± \infin$
- Si el resultado es un valor finito, entonces no existe la AV pero si un punto vacío en $(x;y) = (a;k)$. $\lim\limits_{x \rightarrow a} f(x) = k$
- El signo determina hacia dónde va la función. Si es positivo, sube por la AV, si es negativo, la función baja por la AV

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

## Derivadas

- Recordar tablas

### Propiedades de los logaritmos

![[/image 15.png|image 15.png]]

### Método de derivación logarítmico

- Tomar logaritmos en ambos miembros y utilizar las propiedades de logaritmos que se pueda
- Derivar los dos miembros
- Despejar y’

![[2025-06-13_19_04_46-MTODO_DE_DERIVACIN_LOGARTMICA_-_Brave.jpg]]

## Indeterminaciones

- $\frac{0}{0}$ Cociente de dos infinitésimos. Puede tener cualquier límite según sean las funciones f(x) y g(x). Es por ello que el cociente de dos infinitésimos es un caso de indeterminación del límite
- $\frac{\infin}{\infin}$ Cociente de infinitos
- $\infin - \infin$ Suma algebraica de infinitos
- $0 * \infin$ Producto de un infinitésimo por infinito
- $0^0\ ; \infin^0 \ ; 1^\infin$ Indeterminaciones exponenciales

## No son indeterminaciones

- $\lim\limits_{x \rightarrow a} \frac{± k}{± \infin} = 0$
- $\lim\limits_{x \rightarrow a} \frac{± k}{0} = \infin$
- $\lim\limits_{x \rightarrow a} \frac{\infin}{0} = \infin$
- $\lim\limits_{x \rightarrow a} \frac{0}{\infin} = 0$
- $\lim\limits_{x \rightarrow a} e^\infin = \infin$
- $\lim\limits_{x \rightarrow a} e^{-\infin} = 0$

## Despejar x con logaritmos

![[2025-06-13_19_16_52-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]

![[2025-06-13_19_17_18-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]

![[2025-06-13_19_17_39-Resolviendo_Ecuaciones_Exponenciales_y_Logartmicas_-_Brave.jpg]]

## Regla de L’Hopital

### Caso $\frac{0}{0}$ y $\frac{\infin}{\infin}$

- Se aplica la regla directamente
- Pasos
    - Tomo límite y veo cuál es la indeterminación
    - Derivar numerador y denominador de forma separada
    - Tomar límite
    - Si sigue la indeterminación, volver a derivar hasta levantarla
- Para el caso de que entremos en un loop
    - Focalizar el factor que produce constantemente la indeterminación
    - Realizo cálculos auxiliares hasta levantar la indeterminación

### Caso $0.\infin$

- Hay dos casos:
    - Pasar a “g” al denominador como 1/g: $f.g = \frac{f}{\frac{1}{g}}$
        - Pasa a ser una indeterminación $\frac{0}{0}$
    - Pasar a “f” como 1/f: $f.g = \frac{g}{\frac{1}{f}}$
        - Pasa a ser una indeterminación $\frac{\infin}{\infin}$
- Después de haber hecho, se aplica la Regla de L’Hopital

### Caso $\infin - \infin$

- Escribir el límite y sacamos común denominador para resolver la resta entre las dos funciones para llegar a una de las indeterminaciones $\frac{0}{0}$, $\frac{\infin}{\infin}$
- Luego de resolver la resta, aplico la Regla de L’Hopital

### Caso 1$^\infin$, $\infin^0$, $0^0$

1. Encontrar el valor “y” de todo el límite: $y = \lim\limits_{x \rightarrow 1} [cos(x-1)]^{\frac{1}{x^3 + x -2}}$
2. Aplico Logaritmo Neperiano en ambo de los miembros

$$Ln (y) = Ln[\lim\limits_{x \rightarrow 1} [cos(x-1)]^{\frac{1}{x^3 + x -2}}]$$

1. Aplico propiedad de límites de un logaritmo

$$Ln (y) = \lim\limits_{x \rightarrow 1} Ln[cos(x-1)]^{\frac{1}{x^3 + x -2}}$$

1. Aplico propiedad de logaritmo para bajar la potencia

$$Ln (y) = \lim\limits_{x \rightarrow 1} \frac{1}{x^3 + x -2}. Ln[cos(x-1)] = \infin . 0$$

1. Aplicamos los pasos para el caso $0.\infin$ para obtener una indeterminación $\frac{0}{0}$, $\frac{\infin}{\infin}$
2. Aplico Regla de L’Hopital y encontraremos un valor.
3. Resolver $Ln(y)$, el cual siempre dará $e$ y el valor que encontramos en el paso anterior es a cuánto estará elevado $e$. Ese será el resultado final. Ejemplo: $e^1$, $e^5$

## Resultados de los límites cuando $x \rightarrow \infin$ en cocientes de polinomios

$$\frac{P(x)}{Q(x)} = \frac{a^m+a^{m-1}}{b^n+n^{n-1}} \\  
-----\\  
\lim\limits_{x \rightarrow \infin} f(x) = \begin{cases}  
m = n \implies \frac{a}{b} \ coeficientes \ principales\\  
m>n \implies \infin\\  
m<n \implies 0  
\end{cases}$$

## Continuidad

- Condiciones para que una función sea c

1. Exista la función: $\exists f(a)$
2. Exista el límite de la función en ese punto: $\exists \lim\limits_{x \rightarrow a} f(x) \implies \lim\limits_{x \rightarrow a^+} f(x) = \lim\limits_{x \rightarrow a^-} f(x) = L$
3. Y que el límite sea igual a la ordenada f(a): $\lim\limits_{x \rightarrow a} f(x) = f(a)$

## Discontinuidad

- Sucede cuando no se cumple alguna de las condiciones de continuidad

### Discontinuidad evitable

- Tiene lugar si existe el límite $\exists \lim\limits_{x \rightarrow a} f(x) = L$, sin embargo, la función no está definida en x = a $\nexists f(a)$
- Puede que la función este definida en ese punto, pero su imagen no coincide con el límite L $f(a) \neq L$

### Discontinuidad no evitable

- Surge a partir de la no existencia del límite de la función en el punto “a” $\nexists \lim\limits_{x \rightarrow a} f(x)$, tenga o no imagen en ese punto.
- Se divide en primera especie y segunda especie

==**Primera Especie**==

**Salto finito**

- Surge si los límites laterales $\lim\limits_{x \rightarrow a^+} f(x) \neq \lim\limits_{x \rightarrow a^-} f(x)$ existen pero son diferentes, por lo que el límite no existe en $x = a$

**Salto Infinito**

- Tiene lugar si alguno de los límites laterales es $± \infin$, es decir, $\lim\limits_{x \rightarrow a^+} f(x) = ± \infin$ o $\lim\limits_{x \rightarrow a^-} f(x) = ± \infin$

**Asintótica**

- Se da cuando los dos límites laterales tienen como resultado el $± \infin$, es decir, $\lim\limits_{x \rightarrow a^+} f(x) = ± \infin$ y $\lim\limits_{x \rightarrow a^-} f(x) = ± \infin$

==**Segunda especie**==

- Al menos un límite lateral no existe

## Límites Notables

## Exponenciales

![[/image 1 5.png|image 1 5.png]]

![[2025-06-22_19_34_21-LIMITES_NOTABLES_GUIA.pdf_-_SumatraPDF.jpg]]