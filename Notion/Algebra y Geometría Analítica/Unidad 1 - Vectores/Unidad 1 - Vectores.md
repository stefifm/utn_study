# Notas de la clase

## Vectores

- Segmento orientado que se utiliza para representar las magnitudes vectoriales
    - Segmento: Porción de recta que tiene un principio y un final
    - Orientado: tiene una punta de flecha en cualquiera de sus extremos
- Elementos de un vector
    - Módulo: La longitud del segmento que lo representa.
        - Dirección: es la inclinación del vector. Es el ángulo que está formada por la recta de acción y el eje x
            - Ángulo: abertura entre dos segmentos
            - Se dibuja tomando la recta donde esta el vector y el eje x.
        - Sentido: Es donde apunta la flecha del vector

### Suma entre vectores: método analítico

- $\vec{a} + \vec{b} = (a_x, a_y) + (b_x, b_y)$
- $\vec{a} + \vec{b} = (a_x + b_x) + (a_y, b_y)$
- $\vec{a} + \vec{b} = (a_x + b_x,...,a_n+b_n)$
- La suma de dos o más vectores da como resultado otro rector
- Cómo sumar
    - Se suman componentes homólogas de los vectores sumandos y se obtiene el vector suma
    - Homólogas: referidas al mismo eje coordenado

### Suma entre vectores: geográficamente

- Método del paralelogramo. La suma de $\vec{a} + \vec{b}$ es la diagonal mayor del paralelogramo

![[2025-03-27_11_38_45-Diagrama_sin_ttulo_-_draw.io_-_Brave.jpg]]

- Método del polígono

![[2025-03-27_11_41_40-Diagrama_sin_ttulo_-_draw.io_-_Brave.jpg]]

### Resta de vectores

- Se suma el opuesto del sustraendo, igual módulo y dirección pero distinto sentido
- $\vec{a} - \vec{b} = \vec{a} + (-\vec{b})$
- Método del paralelogramo: La resta de $\vec{a} - \vec{b}$ es la diagonal menor del paralelogramo

![[2025-03-27_11_51_09-Diagrama_sin_ttulo_-_draw.io_-_Brave.jpg]]

- Método del polígono

![[2025-03-27_11_54_57-Diagrama_sin_ttulo_-_draw.io_-_Brave.jpg]]

### Producto de un vector por un escalar

- Cuando multiplicamos un vector por un escalar ( $\lambda$ ), obtenemos otro vector en el que cambia
    - Sólo el módulo, $\lambda$ veces, si el escalar es positivo.
        - Si $\lambda$ es igual a 1, se mantiene la magnitud
        - Si $\lambda > 1$, se estira el vector resultante
    - El módulo y el sentido si el escalar es negativo.
        - Para cambiar el sentido, $\lambda < 0$
        - Para que el vector resultante se achique: $\lambda < 1$
- Fórmula del producto escalar
    - $\lambda * \vec{a} = (\lambda * a_x;\ \lambda * a_y)$

### Componentes de un vector en el plano $R^2$

![[2025-03-27_12_10_13-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

- Si se proyecta el vector sobre los ejes tenemos las componentes
    
    - Origen: $A(x_0; y_0)$
    - Extremo: $B(x_1; y_1)$
    - Siendo:
    
    $$a_1 = x_1 - x_0\\  
    a_2 = y_1 - y_0$$
    
    - Entonces: $\vec{a} = (a_1;a_2)$
- Versor: Tiene igual dirección que los ejes y módulo unitario. Hay dos versores especiales
    
    - i versor sobre el eje x; $\vec{i} = (1;0)$
    - j versor sobre el eje en y; $\vec{j} = (0;1)$
    - Entonces:
    
    $$Expresión\ cartesiana\ del\ vector\ en\ R^2\\  
    \vec{a} = a_1.\vec{i} + a_2.\vec{j}$$
    
    - Cálculo del vector unitario asociado a un vector
        
        $$\u{v} = \pm \frac{\vec{v}}{||v||}$$
        
- Cálculo del módulo en $R^2$ : $||v|| = \sqrt{a_1^2+a_2^2}$

### Componentes del vector en el espacio $R^3$

![[2025-03-27_14_07_09-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

- Si se proyecta el vector sobre los ejes tenemos las componentes
    
    - Origen: $A(x_0; y_0; z_0)$
    - Extremo: $B(x_1; y_1; z_1)$
    - Siendo:
    
    $$a_1 = x_1 - x_0\\  
    a_2 = y_1 - y_0\\  
    a_3 = z_1 - z_0$$
    
    - Entonces: $\vec{a} = (a_1;a_2;a_3)$
- Versor: Tiene igual dirección que los ejes y módulo unitario. Hay dos versores especiales
    
    - i versor sobre el eje x; $\vec{i} = (1;0;0)$
    - j versor sobre el eje en y; $\vec{j} = (0;1;0)$
    - k versor sobre el eje en x; $\vec{k} = (0;0;1)$
    - Entonces:
    
    $$Expresión\ cartesiana\ del\ vector\ en\ R^3\\  
    \vec{a} = a_1.\vec{i} + a_2.\vec{j} + a_3.\vec{k}$$
    
    - Cálculo del módulo en $R^3$ : $||v|| = \sqrt{a_1^2+a_2^2+a_3^2}$

### Ángulos y cosenos directores

- Un vector queda completamente determinado por el módulo, dirección y sentidos, y las componentes me determinan el vector.

![[2025-03-27_14_10_52-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

- $\alpha\ y\ \beta$ son los ángulos que forma el vector con cada uno de los ejes y se los llama ángulos directores. Para calcularlos

$$\alpha = arccos\ \frac{a_1}{||a||}\\  
\beta = arccos\ \frac{a_2}{||a||}$$

- Los cosenos directores son los cosenos de los mencionados ángulos.

$$cos\ \alpha = \frac{a_1}{||a||}\\  
cos\ \beta = \frac{a_2}{||a||}$$

- Gozan de la siguiente propiedad

$$cos \alpha^2 = \frac{a_1^2}{||v||^2}\  
\ \ \ cos \beta^2 = \frac{a_2^2}{||v||^2}\\  
cos\alpha^2 + cos\beta^2 = \frac{a_x^2 + a_y^2}{||a||^2} = \frac{||a||^2}{||a||^2} = 1\\  
cos\alpha^2 + cos\beta^2 = 1$$

**Para el espacio**

![[2025-03-27_14_26_15-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

$$\alpha = arccos\ \frac{a_1}{||a||}\\  
\beta = arccos\ \frac{a_2}{||a||}\\  
\gamma = arccos\ \frac{a_3}{||a||}$$

- Los cosenos directores son los cosenos de los mencionados ángulos.

$$cos\ \alpha = \frac{a_1}{||a||}\\  
cos\ \beta = \frac{a_2}{||a||}\\  
cos\ \gamma = \frac{a_3}{||a||}$$

- Gozan de la siguiente propiedad

$$cos\alpha^2 + cos\beta^2 + cos\gamma^2 = 1$$

### Igualdad entre vectores

- Dos vectores serán iguales cuando tienen el mismo módulo, la misma dirección y el mismo sentido. Es decir, cuando tienen las mismas componentes en cualquier sistema de coordenadas.

### Paralelos

- Dos vectores serán paralelos cuando los cosenos directores sean iguales. Hay dos casos de paralelismo

![[2025-03-27_14_32_38-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

![[2025-03-27_14_33_36-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

![[2025-03-27_14_34_56-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

- La condición necesaria y suficiente para que dos vectores sean paralelos es que sus componentes homólogas sean proporcionales

![[2025-03-27_14_35_37-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

  

### Combinación lineal de vectores

- Dado tres vectores $\vec{h}, \vec{g}\ y\ \vec{e}$ pertenecientes a un plano y que no son paralelos entre sí. Se dibuja un vector a sobre los vectores mencionados anteriormente y tenemos

![[2025-03-27_14_40_30-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

![[2025-03-27_14_41_07-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]

- Por lo que podemos escribir la primera ecuación: $\vec{a} = \vec{a_1} + \vec{a_2} + \vec{a_3}$
- Luego, podemos decir que $\vec{a_1}$ tiene la misma dirección y mismo sentido que el vector $\vec{e}$, lo mismo $\vec{a_1}$ con el vector $\vec{g}$ y $\vec{a_3}$ con el vector $\vec{h}$. Por ende, son proporcionales y en consecuencia, paralelos, por lo que podemos escribir a esos vectores proyectados de $\vec{a}$ de la siguiente manera

$$\vec{a_1} = p.\vec{e}\\  
\vec{a_2} = q.\vec{g}\\  
\vec{a_3} = r.\vec{h}$$

- Si agarramos la ecuación anterior y lo reemplazamos en la primera ecuación, nos queda: $\vec{a} = p.\vec{e} + q.\vec{g} + r.\vec{h}$
    - De esta manera, expresamos al vector $\vec{a}$ como una combinación lineal de los vectores $\vec{e}, \vec{g}\ y\ \vec{h}$.. Esto lo hacemos mediante los escalares $p,q\ y\ r$.

### Dependencia o Independencia lineal

- Está basado en el vector nulo
- Los vectores $\vec{e}, \vec{g}\ y\ \vec{h}$ serán linealmente independientes cuando la única posibilidad de expresar al vector nulo como combinación lineal de ellos es mediante escalares nulos. Es decir que $p,q\ y\ r$ deben valer cero.
- Formas de dependencia lineal
    
    - Si llegamos al vector nulo con coeficientes distintos de cero. Es decir, los escalares no son iguales a ceros
    - Si existe alguna combinación lineal con coeficientes no nulos que me den el vector nulo.
    - Geométricamente, esos vectores tienen la misma dirección y son paralelos.
    
    ![[2025-03-27_14_56_27-Terico_-_Unidad_N1_-_Clase_1_-_YouTube_-_Brave.jpg]]
    

  

$$\boxed{\alpha = \arccos\left( \frac{v_1}{|\mathbf{v}|} \right) \quad \text{y} \quad \beta = \arccos\left( \frac{v_2}{|\mathbf{v}|} \right)}$$