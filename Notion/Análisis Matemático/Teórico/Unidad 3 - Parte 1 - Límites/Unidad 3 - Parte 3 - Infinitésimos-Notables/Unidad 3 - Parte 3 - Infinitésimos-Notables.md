## Indeterminaciones

- $\frac{0}{0}$ Cociente de dos infinitésimos. Puede tener cualquier límite según sean las funciones f(x) y g(x). Es por ello que el cociente de dos infinitésimos es un caso de indeterminación del límite
- $\frac{\infin}{\infin}$ Cociente de infinitos
- $\infin - \infin$ Suma algebraica de infinitos
- $0 * \infin$ Producto de un infinitésimo por infinito
- $0^0\ ; \infin^0 \ ; 1^\infin$ Indeterminaciones exponenciales

## Infinitésimo

- Son funciones que tienden a cero cuando la variable independiente varía de una forma determinada
- La idea es darle un sentido a las indeterminaciones

> Definición: la función $\alpha = \alpha(x)$ se denomina infinitésimo cuando $x \rightarrow a$ o $x \rightarrow \infin$ si $\lim\limits_{x \rightarrow a} \alpha(x) = 0$ o $\lim\limits_{x \rightarrow \infin} \alpha(x) = 0$

- De la definición de límite se deduce que
    - Si $\lim\limits_{x \rightarrow a} \alpha(x) = 0$ significa que, para cualquier número positivo épsilon prefijado y arbitrariamente pequeño, se encontrará un δ > 0 tal que para todos los “x” que satisfacen la condición |x-a| < δ, se verifique la condición |α(x)| < ε

  

### Teoremas

**Teorema 1:** Si una función se puede expresar como una suma entre un número “b” y un infinitésimo α(x), si tomo límite, esto será igual a ese número “b”.

$$\lim\limits_{  
\begin{subarray}{l}  
x\rightarrow a\\  
x \rightarrow \infin  
\end{subarray}} \alpha(x) = b$$

![[1000001905.png]]

**Teorema 2:** Si α(x) tiende a cero cuando $x \rightarrow a$ o $x \rightarrow \infin$, si genero una función $\frac{1}{\alpha(x)}$, entonces éste tenderá al infinito.

![[1000001906.png]]

  

![[/image 17.png|image 17.png]]

- La nueva función donde anteriormente se anulaba, ahora tenderá a infinito.
- Aquí obtenemos una asíntota vertical porque no deja de crecer

**Teorema 3:** La suma algebraica de infinitésimos da como resultado otro infinitésimo

**Teorema 4:** El producto de un infinitésimo por una función acotada es un infinitésimo, cuando $x \rightarrow a \ o \ x \rightarrow \infin$

**Teorema 5:** El cociente de un infinitésimo y una función cuyo límite es distinto de cero es un infinitésimo

$$\frac{\alpha(x)}{f(x)} \implies \alpha(x) = 0 \ \ \land \ \ \lim\limits_{x \rightarrow a} f(x) \neq 0$$

## Comparación de magnitudes infinitesimales

Tenemos lo siguiente:

![[2025-06-10_11_01_35-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

### Definición 1

- Si el cociente $\frac{f(x)}{g(x)}$ tiene un límite finito y distinto de cero, es decir que $\lim\limits_{ \begin{subarray}{l} x\rightarrow a\\ x \rightarrow \infin \end{subarray}} \frac{f(x)}{g(x)} = A \neq 0$ y su recíproca $\lim\limits_{ \begin{subarray}{l} x\rightarrow a\\ x \rightarrow \infin \end{subarray}} \frac{g(x)}{f(x)} = \frac{1}{A} \neq 0$ se dicen que f(x) y g(x) son infinitésimos del mismo orden.
- Significa que ambos infinitésimos tienden a cero, aproximadamente con la misma rapidez cuando “x” se aproxima a “a”

![[2025-06-10_11_12_45-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

  

### Definición 2

- Si el límite de los cocientes es igual a cero $\lim\limits_{ \begin{subarray}{l} x\rightarrow a\\ x \rightarrow \infin \end{subarray}} \frac{f(x)}{g(x)} = 0$ y su recíproca es igual a infinito $\lim\limits_{ \begin{subarray}{l} x\rightarrow a\\ x \rightarrow \infin \end{subarray}} \frac{g(x)}{f(x)} = \infin$, entonces f(x) es un infinitésimo de orden superior respecto a g(x).
- Se interpreta que f(x) tiende a cero con mayor velocidad de lo que hace g(x) cuando “x” se aproxima a “a”

![[2025-06-10_11_18_15-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

- En todas las indeterminaciones hay los resultados pueden ser: distinto de cero, cero o infinito.

  

## Comparación de infinitos ( $\frac{\infin}{\infin}$ )

Para el caso

![[2025-06-10_11_28_26-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

### Caso 1

- Grado del numerador es mayor al denominador, entonces el resultado dará infinito
- El numerador crece más rápido que el numerador

![[2025-06-10_11_33_12-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

### Caso 2

- Grado del numerador es menor al denominador, su resultado será igual a cero
- El denominador crece más rápido que el numerador

![[2025-06-10_11_35_53-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

### Caso 3

- Los grados del numerador y denominador son iguales, el resultado será igual a los coeficientes principales
- Aquí la rapidez es la misma solo que la pendiente es la que varia.

![[2025-06-10_11_38_14-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

![[/image 1 7.png|image 1 7.png]]

## Límites Notables

- Se llama así porque la forma de trabajarlo es diferente
- Se dividen en dos grupos
    - Trigonométricos: seno y tangente
    - Exponenciales

### Límites Notables Trigonométricos

- Vamos a tener que $\lim\limits_{x \rightarrow 0} \frac{sen(x)}{x} (\frac{0}{0}) = 1$ y será extensivo para $\lim\limits_{x \rightarrow 0} \frac{sen(ax)}{ax} (\frac{0}{0}) = 1$, $\lim\limits_{x \rightarrow 0} \frac{sen(f(x))}{f(x)} (\frac{0}{0}) = 1$ y la recíproca $\lim\limits_{x \rightarrow 0} \frac{x}{sen(x)} (\frac{0}{0}) = 1$
- Lo mismo para la tangente $\lim\limits_{x \rightarrow 0} \frac{tg(x)}{x} (\frac{0}{0}) = 1$
- La función que esté en el seno o tangente debe estar en el denominador
- El resultado siempre será 1 cuando sea tangente o seno

**Demostración del límite notable del seno**

- Partimos de una circunferencia donde tomamos un ángulo en radianes.

![[/image 2 7.png|image 2 7.png]]

- Luego hacemos lo mismo pero armando un círculo en el eje de las coordenadas

![[/image 3 7.png|image 3 7.png]]

- Allí marcamos dos rectas: MB y CA donde
    - MB es el seno
    - CA es la tangente ya que está casi sobre la circunferencia
- MA es el arco que se forma entre los puntos A y M. Su longitud es igual al radio, es decir, es igual a 1.
- Bajo estos dibujos, podemos decir que para obtener el seno: $sen(x)=\frac{cateto \ opuesto}{hipotenusa}$ y como la hipotenusa se mide en radianes y éste vale 1 porque el arco que se forma es igual al radio, entonces quedará $sen(x) = cateto \ opuesto$
- A su vez, el valor de “x” será mayor a 0 y menor a pi/2: $0<x<\frac{\pi}{2}$
- Como el arco $s = r .\alpha$ donde r es el radio y alpha es el ángulo, entonces la ecuación del cálculo del arco queda:

$$\widehat{x} = 1.x[radianes] \\  
\widehat{x} = x$$

- Con esta información tenemos lo siguiente

![[2025-06-10_12_07_45-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

- Dividimos los tres miembros por sen(x) y nos queda

![[2025-06-10_12_17_41-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

- Por el momento, el sentido de la desigualdad no cambia ya que estamos trabajando con $0<x<\frac{\pi}{2}$ con $sen(x) > 0$.
- Sin embargo estamos buscando $\frac{sen(x)}{x}$, es decir, la recíproca de $\frac{x}{sen(x)}$, por ende, el sentido de la desigualdad va a cambiar

![[2025-06-10_12_21_04-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

- Ahora mencionaremos la teoría de la comprensión:
    
    - Si se puede calcular el límite en f(x) cuando “x” tiende a “a”, entonces dará L
    - Si se puede calcular el límite en h(x) cuando “x” tiende a “a”, entonces dará L
    - Por ende, el límite en g(x) cuando “x” tiende a “a” será igual a L
    
    ![[2025-06-10_12_24_22-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]
    
- La desigualdad es doble porque debe ser igual a L
- Por ende, si $\lim\limits_{x \rightarrow 0} 1 = 1$ y $\lim\limits_{x \rightarrow 0} cos(x) = 1$, por teoría de comprensión: $\lim\limits_{x \rightarrow 0} \frac{sen(x)}{x} = 1$

![[/image 4 6.png|image 4 6.png]]

- Con la tangente pasa algo similar

![[2025-06-10_12_27_40-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

### Límites notables en Exponenciales

![[2025-06-10_12_29_38-5_Extensin_del_concepto_de_lmite._Indeterminaciones._Lmites_Notables.pdf_-_M.jpg]]

- f(x) debe repetirse en el denominador del exponente
- Debe aparecer siempre la indeterminación $1^\infin$
- Y el resultado siempre será el número “e”