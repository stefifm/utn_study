# Funciones

- Una función f es una regla que asigna a cada elemento x de un conjunto A exactamente un elemento, llamado $f_{(x)}$, de un conjunto B.

![[2025-04-02_21_24_13-2_Entorno__Entorno_Reducido__Punto_de_Acumulacin_-_Punto_Aislado_-_Relaciones.png]]

- Cada elemento del Dominio tendrá tan solo una imagen
    - Un elemento del conjunto de llegada puede ser imagen de más de un elemento del conjunto de partida.
- Dominio
    - es el conjunto de todas las posibles entradas para la función
    - Es el dominio de la expresión algebraica: el conjunto de todos los números reales para los cuales la expresión está definida como un número real
- El rango o imagen de f está formado por todas las posibles salidas de f.
- Una función f de A en B es una asignación única de elementos de A en elementos de B
- Notación de función
    - $f : A \rightarrow B$
    - $f: A(Dominio) \rightarrow B(Imagen) / y = f_{(x)}$
        - Con $x \in Dominio \land y \in Imagen$
- Función es una relación entre dos conjuntos numéricos, donde A y B están incluidos en los números reales que asigna a cada elemento x del conjunto A un solo o único elemento y del conjunto B.

## Gráfica de una función

- El eje de las ordenadas o vertical representa los valores de la imagen.
    - El punto donde la curva interseca al eje y se obtiene $x = 0$ siempre que $x \in Dom f$
        - Se le llama ordenada al origen
    - La curva de una función no puede intersecar al eje y en más de un punto.
- El eje de las abscisas u Horizontal representará los valores del Dominio.
    - Los ceros o raíces de una función son llamados así a los valores de x para los cuales la función se anulan: $x / f_(x) = 0$
    - Representan los puntos donde la curva interseca al eje x

  

## Funciones elementales

### Función constante

![[2025-04-06_23_26_23-Suite_Calculadora_-_GeoGebra_-_Brave.jpg]]

- Dominio: todo el eje x
- Imagen: es la constante k
- $f_{(x)} = k$

### Función identidad

![[2025-04-06_23_28_43-Suite_Calculadora_-_GeoGebra_-_Brave.jpg]]

- Función $f_{(x)} = x$
- Tiene la forma de una recta
- Formula: $ax + b$
    - a es la pendiente de la recta
    - b es la origen donde curta la recta en y
- Dominio: toma el valor de la imagen
- El ángulo que se forma es de 45º

### Función valor absoluto

![[2025-04-06_23_30_47-Suite_Calculadora_-_GeoGebra_-_Brave.jpg]]

- Por definición de valor absoluto, la función $f_{(x)} = |x|$ toma dos valores:
    - Para todos los x positivos
    - Para todos los x negativos
- El dominio: todos los reales
- Imagen: R ≥ 0

### Función Signo

![[/image 3.png|image 3.png]]

- El dominio son todos los reales excepto el 0

### Función cúbica

![[image 1.png]]

- Tiene 3 raíces
- Es elemental porque las raíces valen 0
- Dominio e Imagen: todos los reales

### Función raíz cuadrada

![[/image 2 2.png|image 2 2.png]]

- El dominio no tiene cualquier valor ya que la raíz par no admite negativos
- Por ende, el dominio: x >= 0

### Función racional

![[/image 3 2.png|image 3 2.png]]

- El dominio no puede ser 0
- Tiene asíntotas verticales y horizontales. Aquí valen 0.
    - Son rectas en donde la función se aproxima

### Función exponencial

![[image 4.png]]

- Por x eleva a la base (a, e)
- Aquí, la base tiene que ser mayor a 1.
    - Esto es porque cualquier número elevado a la 1 será el mismo valor

### Función logarítmica

![[image 5.png]]

  
• La base del logaritmo tiene que ser mayor a 1 o distinto de 1.  

### Función seno y coseno

![[image 6.png]]

- La imagen va entre [-1, 1]
- EL dominio: todos los valores de x
- Función seno
    - La función corta el eje "x" en -π, π y 2π
    - Los puntos máximos son -π/2, π/2, 3π/2
- Función coseno
    - La función corta en el eje "x" en -π/2, π/2
    - Los puntos máximos: -2π, 2π
    - Los puntos mínimos:

## Transformaciones de las funciones

![[image 7.png]]

![[image 8.png]]

![[2025-06-12_18_08_56-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

## Funciones Definidas por Tramos

![[image 9.png]]

![[2025-06-12_18_09_51-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

![[2025-06-12_18_10_53-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

## Funciones inyectivas

- Aquellas funciones donde los distintos valores del dominio se relacionan con distintos valores de la imagen
- A distinto “x” le corresponde distinto “y”
    - Cada valor de “y” perteneciente al rango le corresponde exactamente un valor “x” del dominio
- Si la función no es inyectiva, podemos restringir su dominio de manera que la función pase a ser inyectiva

![[2025-06-12_18_12_35-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

## Funciones sobreyectivas

- La imagen debe coincidir con el codominio
- El codominio es el mayor conjunto admisible
- Se dice que una función es sobreyectiva si su rango son todos los “y”

![[2025-06-12_18_16_06-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

## Funciones biyectivas

- Funciones que simultáneamente son inyectivas y sobreyectivas.
- Son las únicas que admiten inversa, sin restricciones

![[2025-06-12_18_17_26-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

## Funciones compuestas

- Dos funciones f y g
- Inicie con un número x del dominio de g y su imagen g(x)
- Si el número g(x) está en el dominio de f, podemos calcula el valor de f(g(x)) y su resultado será una nueva función h(x) que se obtiene de sustituir g(x) en f.

![[image 10.png]]

![[2025-06-12_18_20_33-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

![[image 11.png]]

## Función inversa

![[2025-06-12_18_22_07-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]

![[2025-06-12_18_22_23-3_Funcin_inyectiva_suryectiva_y_biyectiva_-_Algebra_de_funciones_-_Funcin_com.jpg]]