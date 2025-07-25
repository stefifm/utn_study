## Continuidad y Derivabilidad

- Recordamos sobre el concepto de continuidad de una función y la definición de derivada:

![[2025-06-11_15_25_11-9_Derivada_de_funciones_inversas._Aplicaciones_de_la_derivada._Derivabilidad_y_c.jpg]]

![[2025-06-11_15_25_22-9_Derivada_de_funciones_inversas._Aplicaciones_de_la_derivada._Derivabilidad_y_c.jpg]]

- Aplicamos la derivada en el punto “c” de la función: $f'(c) = \lim\limits_{\Delta x \rightarrow 0} \frac{f(c+\Delta x ) -f(c)}{\Delta x}$
- Si realizamos la siguiente sustitución: $x=c+\Delta x;\ \Delta x=x-c \implies \Delta x \rightarrow 0;\ x\rightarrow c$
- Entonces, la derivada de la función en el punto c queda como: $f'(c) = \lim\limits_{ x \rightarrow c} \frac{f(c+\Delta x )-f(c)}{\Delta x}$
    - Siempre que el límite $x \rightarrow c$ exista
- Por lo que, si lo expresamos como límites laterales, nos quedará como las derivadas de los laterales. Y para que halla continuidad, las derivadas laterales deben ser iguales

$$f'(c) = \lim\limits_{ x \rightarrow c^+} \frac{f(c+\Delta x )-f(c)}{\Delta x} = \lim\limits_{ x \rightarrow c^-} \frac{f(c+\Delta x )-f(c)}{\Delta x}$$

### Qué significa que una función sea derivable?

- Una función es derivable en x = c si la derivada es continua en x = c

![[/image 21.png|image 21.png]]

![[/image 1 11.png|image 1 11.png]]

![[/image 2 9.png|image 2 9.png]]

![[/image 3 9.png|image 3 9.png]]

![[/image 4 8.png|image 4 8.png]]

> [!important] Una función es derivable cuando
> 
> - La función existe en el punto x = c
> - Los límites laterales en x = c existen y son iguales
> - La ordenada f(c) es igual al límite en ese punto
> - Las derivadas laterales existen y son iguales.

### Por qué deja de ser derivable una función?

- Cuando su gráfica cambia de dirección repentinamente
    
    - Si la gráfica de una función tiene esquinas o picos, la gráfica de f no tiene recta tangente en esos puntos y f no es derivable allí.
    - Si calculamos la derivada allí, los límites laterales serán diferentes
    
    ![[/image 5 7.png|image 5 7.png]]
    
- Si f no es continua en x = c, entonces f no es derivable en x = c
    
    - En cualquier discontinuidad, f no es derivable
    
    ![[/image 6 6.png|image 6 6.png]]
    
- La curva tenga una recta tangente vertical cuando x = c: $\lim\limits_{x \rightarrow c} f'(x) = \infin$

![[/image 7 6.png|image 7 6.png]]

### Continuidad vs Derivabilidad

- Si una función es continua en x = c, NO necesariamente es derivable en x = c

![[/image 8 5.png|image 8 5.png]]

- Ahora, si la función es derivable en x = c, entonces la función si es continua en x = c

![[2025-06-11_15_48_17-9_Derivada_de_funciones_inversas._Aplicaciones_de_la_derivada._Derivabilidad_y_c.jpg]]

![[/image 9 5.png|image 9 5.png]]