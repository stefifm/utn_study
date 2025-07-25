## Continuidad de una función en un punto

> **Definición**  
>   
> Sea f(x) una función y “a” un punto que pertenece a su dominio, f(x) es continua en x=a si y solo si se cumplen las siguientes condiciones:  
>   
> 1) Exista la función: $\exists f(a)$  
> 2) Exista el límite de la función en ese punto: $\exists \lim\limits_{x \rightarrow a} f(x) \implies \lim\limits_{x \rightarrow a^+} f(x) = \lim\limits_{x \rightarrow a^-} f(x) = L$  
> 3) Y que el límite sea igual a la ordenada f(a): $\lim\limits_{x \rightarrow a} f(x) = f(a)$

![[/image 13.png|image 13.png]]

- Si una función es continua en un punto, incrementos infinitesimales en la variable independiente producen incrementos infinitesimales en la función.
    - Es decir, en ese punto la gráfica de la función no presentará saltos, interrupciones ni cambios bruscos.

## Discontinuidad

- Sucede cuando no se cumple ninguna de las condiciones de continuidad.

### Discontinuidad evitable

- Tiene lugar si existe el límite $\exists \lim\limits_{x \rightarrow a} f(x) = L$, sin embargo, la función no está definida en x = a $\nexists f(a)$
- Puede que la función este definida en ese punto, pero su imagen no coincide con el límite L $f(a) \neq L$
- Se le llama evitable porque es posible redefinir la función f de forma tal que $f(a) = L$
    
    - Se hace construyendo una nueva función.
    
    $$f^*(x)=\begin{cases}  
    f(x) &\text{si } x\neq a\\  
    L &\text{si } x = a  
    \end{cases}$$
    

**Ejemplo**

![[/image 1 3.png|image 1 3.png]]

- g(x) es discontinua evitable en x = 1
- Redefino la función

$g^*(x)=\begin{cases} \frac{x^2 -1}{x-1} &\text{si } x\neq 1\\ 2 &\text{si } x = 1 \end{cases}$

**Otro ejemplo**

$$f(x) = \frac{sen(x)}{x}$$

1. El dominio de la función son todos los reales menos el cero, por ende

$$f(0) = \frac{sen(0)}{0} = \nexists$$

1. Por límite notable, el $\lim\limits_{x \rightarrow 0} \frac{sen(x)}{x} (\frac{0}{0}) = 1$
    1. Por ende, es discontinua en $x = 0$
    2. Redefino la función $g^*(x)=\begin{cases} \frac{sen(x)}{x} &\text{si } x\neq 0\\ 1 &\text{si } x = 0 \end{cases}$

### Discontinuidad no evitable

- Surge a partir de la no existencia del límite de la función en el punto “a” $\nexists \lim\limits_{x \rightarrow a} f(x)$, tenga o no imagen en ese punto.
- Se divide en primera especie y segunda especie

==**Primera Especie**==

**Salto finito**

- Surge si los límites laterales $\lim\limits_{x \rightarrow a^+} f(x) \neq \lim\limits_{x \rightarrow a^-} f(x)$ existen pero son diferentes, por lo que el límite no existe en $x = a$
- No se puede redefinir la función

![[/image 2 4.png|image 2 4.png]]

![[/image 3 4.png|image 3 4.png]]

- $\lim\limits_{x \rightarrow 0^+} f(x) = L$, $\lim\limits_{x \rightarrow 0^-} f(x) = -1$, entonces $\nexists \lim\limits_{x \rightarrow 0} f(x)$
    - Por lo que la función f(c) es discontinua no evitable de primera especie con salto finito en $x = 0$

**Salto Infinito**

- Tiene lugar si alguno de los límites laterales es $± \infin$, es decir, $\lim\limits_{x \rightarrow a^+} f(x) = ± \infin$ o $\lim\limits_{x \rightarrow a^-} f(x) = ± \infin$
- Imposible redefinir la función f

![[/image 4 3.png|image 4 3.png]]

**Asintótica**

- Se da cuando los dos límites laterales tienen como resultado el $± \infin$, es decir, $\lim\limits_{x \rightarrow a^+} f(x) = ± \infin$ y $\lim\limits_{x \rightarrow a^-} f(x) = ± \infin$
- Indica que hay una asíntota vertical
    
    ![[/image 5 3.png|image 5 3.png]]
    

==**Segunda especie**==

- Al menos un límite lateral no existe
- Ejemplo: $f(x) = sen(\frac{1}{x})$
    
    - Como el límite lateral derecho de la función está comprendido entre [-1,1], entonces ese límite lateral no existe ya que debe ser único y finito. Lo mismo sucede con el límite lateral izquierdo
    
    $$\nexists \lim\limits_{  
    \begin{subarray}{l}  
    x\rightarrow 0^+\\  
    x \rightarrow 0^-  
    \end{subarray}}  
    sen(\frac{1}{x}) \implies [-1,1]$$
    

![[/image 6 2.png|image 6 2.png]]

  

**Funciones definidas por tramos**

![[/image 7 2.png|image 7 2.png]]

![[/image 8 2.png|image 8 2.png]]

## Propiedades de la continuidad

![[2025-06-10_18_39_11-6_Continuidad._Continuidad_en_un_punto_y_en_un_intervalo._Discontinuidades._Prop.jpg]]

## Continuidad en un intervalo cerrado

![[1000001974.png]]

- El gráfico es continuo en el intervalo cerrado de a y b
- Para que la función f(x) sea continua en el intervalo cerrado $[a,b]$, tiene que ser continua en el intervalo abierto $(a,b)$ y la función en el punto $a$ $f(a)$ debe coincidir con el límite derecho de $f(x)$ y la función en el punto $b$ debe ser igual al lateral izquierdo

![[/image 9 2.png|image 9 2.png]]

- De la gráfica
    - Tomamos un punto c que pertenece al intervalo abierto (a, b) y verificamos que
        - Existe la función en el punto c
        - Los límites laterales derechos e izquierdos son iguales, por ende, existe el límite
        - La función en el punto c es igual al límite de la función de x que tiende al punto c
    - Dicho esto, la función en el punto c es continua en el abierto
- Respecto a la condición $f(a) = \lim\limits_{x \rightarrow a^+} f(x)$
    - Debido a que el intervalo es cerrado, solo nos podemos acercar al punto “a” por la derecha.
    - Misma situación para $f(a) = \lim\limits_{x \rightarrow a^-} f(x)$, pero acercando al punto “b” por la izquierda

## Teorema del valor medio

> Si f es continua en el intervalo cerrado [a, b], y “k” es cualquier número entre f(a) y f(b), entonces existe al menos un número “c” en [a, b] tal que $f(c) = k$

![[1000001975.png]]

- Este teorema no proporciona una forma de obtener el punto “c”
- Si “k” es igual a 0, el valor de “c” será la raíz de la función.
- El teorema se basa en la propiedad de completitud de los números reales
    - Para que la función sea continua, si “x” recorre todos los valores desde “a” hasta “b”, entonces f(x) debe asumir todos los valores entre f(a) y f(b)
- No sirve para funciones discontinuas ya que “k” podría no encontrar un valor asociado a “c”