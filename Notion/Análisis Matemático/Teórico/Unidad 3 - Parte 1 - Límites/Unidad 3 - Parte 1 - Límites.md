## Idea intuitiva de Límites

Tenemos la siguiente función

$$f_{x} = \frac{x^2-1}{x-1}$$

Si analizamos detalladamente, el denominador no puede ser cero. Por lo que el dominio será todos los números reales excepto el número 1.

$$Dom\ f = \R\ -\{1\}\\  
x-1 \neq 0 \\  
x \neq 1$$

**Y cómo se comporta la función cerca del 1?**

|   |   |   |
|---|---|---|
|x|f(x)||
|0.99|1.99|Se acerca a 2|
|0.999|1.999|Se acerca a 2|
|0.9999|1.9999|Se acerca a 2|
|1|No existe|Tiene que ser un punto de acumulación|
|1.001|2.001|Se acerca a 2|
|1.0001|2.0001|Se acerca a 2|
|1.00001|2.00001|Se acerca a 2|

La tabla nos dice que cuanto más nos aproximamos al 1 por izquierda y derecha, nos estamos acercando al número 2. Es decir, cuando el límite de la función tiende a 1, su valor será 2. Nos acercamos a 1 pero nunca toma dicho valor.

$$\lim\limits_{x\rightarrow 1} \frac{x^2 +1}{x-1} = 2$$

La gráfica queda de la siguiente manera

![[2025-05-30_17_31_06-Suite_Calculadora_-_GeoGebra.jpg]]

Podemos decir lo siguiente:

- El número 2 en el eje y es el valor de la ordenada que determina el límite de la función
- Y los resultados son más chicos que 2
- También se comprueba que, si nos acercamos por izquierda y por derecha a 1, el límite será igual a 2.

Entonces

Si f(x) está definida en un intervalo abierto alrededor de “a”, excepto en “a”, es decir, el entorno reducido de “a”, y está arbitrariamente cerca de L para toda “x” suficientemente cercana a “a”, decimos que f(x) se aproxima al límite ==L== cuando “x” tiende a “a”:

  

$$\boxed{\lim\limits_{x \rightarrow a} f(x) = L}$$

![[/image 12.png|image 12.png]]

En las tres gráficas observamos que

- En el a), La función f(a) = L existe y si tomamos límite en el punto “a” será igual a L.
- En el inciso c), la función en el punto “a” (g(a)) no existe, sin embargo, si tomamos límite en ese punto será también igual a L.
- Y en el inciso b), h(a) existe y es distinto al valor de L.
- Aún así, queda como
    
    $$\lim\limits_{x \rightarrow a} f(x) = \lim\limits_{x \rightarrow a} h(x) = \lim\limits_{x \rightarrow a} g(x) = L$$
    

## Definición precisa de Límites Finitos

- Límites finitos ya que se obtiene un valor real

![[1000001623.png]]

Del gráfico

- Tenemos una función f(x)
- Entre $a-\delta$ y $a + \delta$ se genera entornos reducidos.
- El valor tan cerca de L es llamado ε (épsilon)
- δ dependen de ε.
- ε Representa un número positivo pequeño. Cuando f(x) se acerca arbitrariamente a L, significa que f(x) pertenece al intervalo (L-ε, L+ε). Al usar la noción de valor absoluto, esto se lo puede escribir como

$$|f(x) - L| < \epsilon$$

- Cuando “x” se aproxima a “a”, quiere decir que existe un número positivo δ tal que “x” pertenece al intervalo (a-δ, a+δ), esto se puede se puede expresar de manera precisa de la siguiente forma:

$$0 < |x-a| < \delta$$

- La primera desigualdad $0 < |x-a|$ indica que la distancia entre “x” y “a” es mayor a 0 y que “x” es distinto a “a”
- La segunda desigualdad $|x-a|<\delta$ dice que “x” está a menos de δ unidades de “a”.

### Definición de límite

> Sea f una función definida en un intervalo abierto que contiene el entorno reducido de “a” y L un número real, el límite de x que tiende a “a” de f(x) será igual a L si y solo si, para todo ε que sea mayor a 0, exista un δ mayor a 0 tal que, si elegimos un punto “x” dentro del entorno reducido de “a”, entonces la distancia de la función al límite sea menor que épsilon.

$$\lim\limits_{x\rightarrow a} f(x) \iff \forall \epsilon > 0 \ \exists \delta>0 \ / \ 0<|x-a|<\delta \implies |f(x)-L| < \epsilon$$

Para cualquier valor de épsilon (tan pequeño como se quiera) se debe cumplir que todas las imágenes de los valores de “x” dentro del entorno reducido de “a” están contenidas dentro del entorno de L. Si eso ocurre, el límite existe.

  

**Comprobación de la dependencia entre delta y épsilon**

![[1000001628.png]]

![[1000001629.png]]

![[16631e05-f452-49d1-bf6c-51a748d228a2.png]]

## Propiedades de Límites

1. El límite de la suma de funciones es igual a la suma de los límites
2. El límite de la diferencia de funciones es igual a la diferencia de los límites
3. El límite de una constante por una función es igual a la constante multiplicado por el límite de la función
4. El límite del producto de funciones es igual al producto de los límites
5. El límite del cociente de funciones es igual al cociente de los límites donde el denominador es distinto a cero.
6. Límite de una potencia: El límite de una función elevada a la n es igual al límite de la función elevada a esa n.
7. El límite de una constante es igual a la constante
8. El límite de la función identidad es igual a “a”
9. El límite de una función polinomial es igual a “a” elevada a la n.
10. El límite de una función exponencial compuesta es igual al límite de la función elevada al límite de la función exponencial
11. El límite del logaritmo de una función es igual al logaritmo del límite de esa función

![[/image 1 2.png|image 1 2.png]]

![[/image 2 3.png|image 2 3.png]]

![[/image 3 3.png|image 3 3.png]]

![[/image 4 2.png|image 4 2.png]]

![[/image 5 2.png|image 5 2.png]]

![[2025-05-31_10_47_45-4_idea_intuitiva_limites.pdf_-_Microsoft_PowerPoint_-_4_Idea_intuitiva_de_lmit.jpg]]

![[2025-05-31_10_47_51-4_idea_intuitiva_limites.pdf_-_Microsoft_PowerPoint_-_4_Idea_intuitiva_de_lmit.jpg]]

  

## Límites Laterales

### Límite lateral derecho

![[1000001712.png]]

- El límite lateral derecho significa que “x” se aproxima a “a” por valores superiores a “a”
- Habrá límite lateral derecho igual a L si para todo épsilon mayor a cero existe un delta mayor a cero tal que si “x” se encuentra dentro del intervalo $(a, a+\delta)$, entonces la distancia entre la función y el límite sea menor a épsilon

$$\lim\limits_{x \rightarrow a^+} \iff \forall \epsilon > 0 \ \exists \ \delta>0 / a<x<a+\delta \implies |f(x)-L| < \epsilon$$

### Límite Lateral Izquierdo

![[1000001713.png]]

- El límite lateral izquierdo significa que “x” se aproxima a “a” por valores inferiores a “a”.
- Habrá límite lateral izquierdo igual a L si para todo épsilon mayor a cero existe un número delta mayor a cero tal que si “x” está dentro del intervalo $(a-\delta, a)$, entonces la diferencia entre la función y el límite será menor a épsilon.

$$\lim\limits_{x \rightarrow a^-} \iff \forall \epsilon > 0 \ \exists \ \delta>0 / a-\delta<x<a \implies |f(x)-L| < \epsilon$$

### Teorema

Una función f(x) tiene un límite cuando x se aproxima a “a” si y sólo si existen los límites laterales izquierdo y derecho, y además estos límites laterales son iguales.

![[1000001739.png]]

![[1000001740.png]]

![[1000001741.png]]

![[1000001742.png]]

[[Unidad 3 - Parte 2 - Límites-Cálculo-Asíntotas]]

[[Unidad 3 - Parte 3 - Infinitésimos-Notables]]