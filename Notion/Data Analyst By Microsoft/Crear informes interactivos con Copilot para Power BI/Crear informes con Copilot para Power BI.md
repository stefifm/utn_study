Ahora comprende el valor de los datos preparados y cómo diseñar un modelo semántico basado en las necesidades de sus informes. A continuación, exploramos cómo visualizar los datos y proporcionar información para la toma de decisiones basada en datos.

## **Crear informes con Power BI Desktop**

Power BI Desktop es la principal herramienta de desarrollo de informes. Puede conectarse, transformar, modelar y visualizar datos desde esta aplicación. Exploremos cómo Copilot puede ayudarle a crear imágenes e informes en Power BI Desktop.

**Nota**

Debe iniciar sesión con una cuenta que tenga acceso a un espacio de trabajo antes de poder usar Copilot.

La experiencia de Copilot es coherente con la de otros productos de Microsoft Copilot: seleccione el botón de Copilot y se abrirá un nuevo panel con sugerencias de solicitudes y capacidades de chat.

Algunas de las indicaciones que puede probar son:

- Crear una nueva página de informes.
- Sugerir contenido para una nueva página de informes.
- Responda a esta pregunta sobre los datos… (luego inserte su pregunta en el chat).

[![](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/copilot-pane.png)](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/copilot-pane.png)

El siguiente ejemplo se ha generado mediante la solicitud sugerida **Crear una nueva página de informe**. Copilot pidió el nombre y la descripción, y luego creó los elementos del informe, que incluyen:

- Encabezado con segmentaciones para el producto y el comercial.
- Objetos visuales de tarjeta para las sumas de ventas, coste y medida de ganancias (ventas menos coste).
- Gráficos de área que evalúan las ventas, los costes y las ganancias a lo largo del tiempo.
- Gráficos de columna que evalúan las ventas, los costes y las ganancias por producto.
- Un objeto visual de mapa de ventas por región.

Este informe y todos los elementos se generaron en un tema coherente y se crearon rápidamente.

[![](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/copilot-generated-report.png#lightbox)](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/copilot-generated-report.png#lightbox)

## **Crear informes con el servicio Power BI**

Cuando crea informes en Power BI Desktop, puede publicarlos en el servicio Power BI o Fabric para colaboración y distribución. Cuando publica el informe, se crean dos elementos dentro de un espacio de trabajo: un **modelo semántico** y el **informe**.

- El informe es la representación visual que ha creado en la vista de informe en Power BI Desktop.
- El modelo semántico son los datos subyacentes, incluidas las relaciones y las medidas.

Para crear informes a través del servicio Power BI, primero seleccione los puntos suspensivos (…) del modelo semántico y luego **Crear informe**.

[![](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/create-reports-1.png)](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/create-reports-1.png)

Seleccione el botón Copilot y vea una experiencia similar con las solicitudes sugeridas y el campo de chat.

[![](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/service-copilot-pane.png)](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/service-copilot-pane.png)

**Sugerencia**

Si no ve Copilot, es posible que sus administradores no lo hayan habilitado o que no haya seleccionado un modelo semántico.

Para este ejemplo, vemos que se ofrecen varias posibilidades, que incluyen:

- Rendimiento de ventas por comercial
- Análisis de ventas regionales
- Coste y rentabilidad del producto

En la siguiente captura de pantalla, seleccionamos la solicitud _Coste y rentabilidad del producto_ para generar una nueva página de informe. Esta página tiene un diseño similar al que se creó con Power BI Desktop. Hay objetos visuales de tarjeta, gráficos de barras y columnas y gráficos de área para ayudar a analizar el coste y la rentabilidad de diferentes productos, incluido el coste estándar, las ganancias y el margen de beneficio.

[![](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/service-generated-report.png#lightbox)](https://learn.microsoft.com/es-es/training/modules/power-bi-copilot/media/service-generated-report.png#lightbox)

### **Crear páginas con solicitudes personalizadas**

También puede proporcionar sus propias indicaciones en función de su conocimiento de los datos y los requisitos comerciales para el informe. Puede haber limitaciones en lo que Copilot puede crear según sus solicitudes. Algunas ideas para nuestro modelo son:

- Crear una página que muestre los 10 productos principales por ventas.
- Crear un objeto visual en una nueva página que muestre los tres colores principales en todos los productos vendidos.

**Sugerencia**

Para obtener más información, consulte **[Escribir indicaciones de Copilot que produzcan resultados en Power BI](https://learn.microsoft.com/es-es/power-bi/create-reports/copilot-prompts-report-pages)**.

### **Consideraciones finales**

Al utilizar Copilot, debe tener en cuenta que es su primer borrador, lo que requiere su revisión antes de finalizar. Aunque puede mantener los objetos visuales tal y como están, puede que quiera cambiar los colores o las etiquetas de otros. Recuerde:

- Las actualizaciones se hacen continuamente, así que espere mejoras.
- Las respuestas de Copilot se generan con IA y pueden cometer errores. Revise siempre su trabajo.

**Nota**

Las capturas de pantalla y las sugerencias en su entorno pueden diferir de las que se generaron en el momento en que se escribió esta unidad.

Para nuestros ejemplos, publicamos un modelo semántico en el servicio Power BI basado en la base de datos de AdventureWorks.