- Al compilar o implementar una aplicación en la nube, dos de las consideraciones más importantes son:
    - Tiempo de actividad (o la disponibilidad)
    - Capacidad de controlar la demanda (o escala).

## Alta disponibilidad

- Es importante que los recursos estén disponibles cuando sea necesario
- La alta disponibilidad se centra en garantizar la máxima disponibilidad, independientemente de las interrupciones o eventos que puedan producirse
- Al diseñar la solución, deberá tener en cuenta las garantías de disponibilidad del servicio
- Azure es un entorno de nube de alta disponibilidad con garantías de tiempo de actividad en función del servicio
- Las garantías forman parte de contratos de nivel de servicio
- Contratos de nivel de servicio
    - Es un acuerdo formal entre el proveedor de servicios y el cliente
    - Garantiza al cliente un nivel de servicio establecido
    - El proveedor puede ser
        - Una empresa comercial que proporciona el servicio (Microsoft con Azure)
    - También se puede aplicar dentro de la misma organización: acuerdo entre el departamento TI y usuarios comerciales
- Acuerdos de nivel de servicio en Azure
    - Se representan como un porcentaje relacionado con la disponibilidad del servicio o aplicación
    - La disponibilidad es conocida como tiempo de actividad
    - Si el servicio siempre estaba disponible para su uso: significa que está a un 100% de tiempo de actividad
    - También incluye detalles como
        - el tiempo de inactividad, cuando el servicio no está disponible
        - Y cualquier crédito al que pueda tener derecho si no se cumple el acuerdo de nivel de servicio
    - Un tiempo de actividad del 100% es costoso y difícil de conseguir
        - No hay tiempo suficiente para desconectar el servicio por mantenimiento o actualizaciones
        - Requiere duplicar cada componente en caso de que alguno falle
        - Los componentes de copia de seguridad deben retomar el servicio sin interrupción para el cliente
    - Los acuerdos más comunes: 99%, 99,9%, 99,5%
    - Diferencias entre un acuerdo de 99% y 99,9%
        - El de 99% puede no estar disponible hasta 1,6 horas a la semana, o 7,2 horas al mes
            - El tiempo es acumulativo: se puede sumar a lo largo de diferentes incidentes en los que el servicio no esté disponible
        - El de 99,9% puede no estar disponible durante 10 minutos a la semana o 43,2 minutos al mes
    - Cada servicio de Azure tiene su propio acuerdo de servicio
        - Hay que entender cada uno de ellos para garantizar la optimización de la disponibilidad según las necesidades del negocio

## **Escalabilidad**

- Hace referencia a la capacidad de ajustar los recursos para satisfacer la demanda
- Implica que puede agregar más recursos para controlar mejor la mayor demanda
- No se está pagando de más por los servicios
    - Esto es debido a que la nube es un modelo basado en el consumo, solo se paga por lo que se usa
- Dos variedades de escalabilidad
    - Vertical
        - se centra en aumentar o disminuir las capacidades de los recursos
        - Se puede agregar verticalmente más CPU o RAM a una máquina virtual
        - Se puede disminuir verticalmente las especificaciones de RAM o CPU
        - Dependerá de si necesita más potencia de procesamiento
    - Horizontal
        - Agrega o resta el número de recursos
        - Se pueden agregar o disminuir la cantidad máquinas virtuales o contenedores adicionales dependiendo de la demanda