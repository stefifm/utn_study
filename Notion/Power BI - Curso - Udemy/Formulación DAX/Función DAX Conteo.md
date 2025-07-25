- Sirve para conocer la cantidad de celdas o columnas
- Se trata de COUNT()
- COUNT() es para contar números en una columna. Si en esa columna hay valores vacíos o alfanuméricos, no se van a contar
- COUNTA() es para contar la cantidad de registros independientemente de si tienen valores vacíos o alfanuméricos

## Diferencia entre hacer una función DAX y hacer la suma/conteo/promedio desde el propio gráfico

- Al hacer un cálculo desde el propio gráfico, es tomado como una máscara y está viviendo en la memoria temporal de Power BI. Ese recuento no se puede reutilizar
- La función DAX se puede usar en cualquier objeto visual y se puede combinar con otra DAX para enriquecer otros objetos visuales. Siempre se recomienda estas funciones para hacer los cálculos.