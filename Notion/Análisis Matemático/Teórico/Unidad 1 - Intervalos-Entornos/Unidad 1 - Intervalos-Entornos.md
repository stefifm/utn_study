# Clasificación de los números

- Conjunto de los complejos
    - Imaginarios
    - Reales
        - Racionales
            - Enteros
                - Naturales
                - Cero
                - Negativos
            - Fraccionarios
        - Irracionales

# Representación de los números reales

- Se pueden representar como puntos en una recta numérica, llamada recta real
- Existe una correspondencia biunívoca, es decir doble y única, entre números reales y puntos sobre la recta real.
    - Cada número real ocupa una posición en la recta real y cada punto le corresponde uno y solo un número real

# Axiomas de los números reales

## Concepto de Axioma

- Axioma es un principio fundamental cuya verdad se admite sin pruebas, es decir, una afirmación.

## Axiomas

Dados dos números reales cuales quiera a y b se define la suma a + b € R y el producto ab € R que satisfacen los siguientes axiomas

- Axioma 1: Propiedad conmutativa de la suma: $a + b = b +a$
- Axioma 2: Propiedad asociativa de la suma: $a + (b+c) = (a+b)+c$
- Axioma 3: Existencia del neutro aditivo. Existe el = € R tal que $a+0=a$
- Axioma 4: Existencia de inversos aditivos. Para todo número real a existe -a € R, tal que $a+(-a)=0$. Asociado a la resta.
- Axioma 5: Propiedad conmutativa del producto. $ab=ba$
- Axioma 6: Propiedad asociativa del producto. $a(bc)=(ab)c$
- Axioma 7: Existencia del neutro multiplicativo. Existe el 1 € R tal que $a * 1 = a$
- Axioma 8: Existencia de inversos multiplicativos. Para todo número real a ≠ 0 existe $a^{-1}$ € R tal que $a * a^{-1} = 1$. Esto esta asociado al cociente.
- Axioma 9: Propiedad distributiva. $a(b+c) = ab + ac$

# Propiedades de los números reales

- Algebraicas
- Orden
    - Los números reales están ordenados. Se dice que a es menor que b y se escribe a < b si $b - a$ es un número positivo. Geométricamente, esto significa que a se sitúa a la izquierda de b en la recta real.
- Completitud
    - Es la propiedad es esencial para la idea de límite
    - De manera informal, se refiere a que existen suficientes números reales para completar la recta, en el sentido de que no existen agujeros o huecos en ella.

# Intervalos

- Conjunto de puntos limitado por dos extremos a y b que pertenecen a los reales siendo a < b.
- Los extremos también se llama puntos frontera ya que conforman la frontera del intervalo.

## Finitos

- Intervalo abierto: no incluye los extremos
- Intervalo cerrado: incluye los extremos
- Intervalos semiabiertos o semicerrados: incluye uno de los extremos, pero no el otro.
- Cota inferior: h es cota inferior de un conjunto S de números reales si y sólo si h es un número real menor o igual a todos los elementos del conjunto S.
- Conjunto minorante: El conjunto minorante del conjunto S es el conjunto formado por todas las cotas inferiores
- Ínfimo: Es el mayor de las cotas inferiores
- Mínimo: si el extremo inferior pertenece al conjunto S entonces es el mínimo del conjunto
- Cota Superior: k es una cota superior de un conjunto S de números reales si y sólo si k es un número real mayor o igual a todos los elementos del conjunto S.
- Conjunto mayorante: el conjunto mayorante del conjunto S es el conjunto formado por todas las cotas superiores.
- Supremo: es la menor de todas las cotas superiores.
- Máximo: si el supremo pertenece al conjunto S entonces es el máximo del conjunto.
- Nota: es un intervalo abierto no hay ni mínimos ni máximos ya que siempre habrá un número cercano a m en el intervalo abierto (m,n). Lo mismo sucede con n.

## Infinitos

![[2025-04-02_19_29_16-1_Introduccin_Intervalos_Valor_absoluto.pdf_-_Brave.png]]

# Valor absoluto

- El valor absoluto de un número x, denotado como |x| se define cómo:

$$x = \begin{cases}  
x &\text{si } x >= 0 \\  
-x &\text{si } x <= 0  
\end{cases}$$

- Geométricamente: el valor absoluto de x es la distancia de x al origen de la recta real.
- Las distancias siempre son positivas o nulas
- $|x-y|$ representa la distancia entre estos dos números
- $|x-y| = |y - x|$

![[2025-04-02_19_56_43-1_Introduccin_Intervalos_Valor_absoluto.pdf_-_Brave.png]]

![[2025-04-02_19_57_11-1_Introduccin_Intervalos_Valor_absoluto.pdf_-_Brave.png]]

# Entornos

- Si a es un número real cualquiera y $\delta$ un número positivo, se llama entorno de centro a y radio o amplitud $\delta$ al conjunto de puntos que están a una distancia de a mayor o igual 0 y menor que $\delta$. Es decir, es el intervalo abierto $(a - \delta; a + \delta)$
- Notación: $|x-a|<\delta; E_{(a,\delta)}$
    - Se lee: entorno con centro a y radio o amplitud $\delta$.
    - Todos los valores estarán comprendidos en el intervalo abierto.

## Entorno reducido

- Es el conjunto de puntos del intervalo abierto $(a - \delta; a + \delta)$ del cual se excluye el punto a.
- Notación: $0<|x-a|<\delta; \ E'_{(a,\delta)} ; \ E^*_{(a,\delta)}$
    - $0<|x-a|$ equivale exigir que $x \not = a$ pues $|x-a| = 0 \iff x = a$

## Punto de acumulación

- Si C es un conjunto de puntos de la recta real, un punto a es un punto de acumulación de C si a todo entorno reducido de a pertenece por lo menos a un punto de C.
- El punto a puede pertenecer o no al conjunto C
- a es un punto de acumulación de $C \iff \forall E'_{(a,\delta)}:\exists x/(x \in C \land x \in 0 < |x-a| < \delta)$
- Cuestiones
    - Si el conjunto C es un intervalo cerrado: todos sus puntos son de acumulación
    - SI el conjunto C es un intervalo abierto: todos sus puntos son de acumulación y también los extremos aunque no pertenezcan al conjunto
    - El conjunto N (números naturales) no tiene puntos de acumulación.

## Puntos aislados

- Un punto a que pertenece al conjunto C es un punto aislado si y solo si, existe un entorno reducido de a al cual no pertenece a ningún punto del conjunto de C.
- a es un punto aislado del conjunto $C \iff a \in C \land \exists E'_{(a,\delta)} / E'_{(a, \delta)} \cap C = \emptyset$
- Ejemplos
    
    - Cada número natural es un punto aislado
    - La función $f_{(x)} = \sqrt{x^4 -x^2}$
    
      
    
    ![[2025-04-02_20_56_28-Calculadora_grfica_-_GeoGebra_-_Brave.png]]