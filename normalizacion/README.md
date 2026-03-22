Se realizó una mejora en el modelo de datos mediante la creación de la tabla intermedia cita_servicio, con el fin de transformar la relación entre las entidades cita y servicio de muchos a uno (N:1) a muchos a muchos (N:M). Este ajuste permite que una cita pueda incluir múltiples servicios, evitando redundancia y aumentando la flexibilidad del sistema. Además, el modelo cumple con las tres primeras formas normales (1FN, 2FN y 3FN), garantizando integridad y consistencia en los datos.

El diccionario de datos desarrollado en este proyecto describe la estructura de la base de datos diseñada para la gestión de clientes, citas, servicios y pagos.

Incluye la definición detallada de las siguientes tablas:

cliente, 
cita, 
servicio, 
cita_servicio, 
pago, 

Para cada una, se especifican sus atributos, tipos de datos y restricciones, tales como claves primarias (PK), claves foráneas (FK) y restricciones de unicidad (UNIQUE).

Este diccionario facilita la comprensión del modelo de datos, asegura la integridad de la información y respalda el cumplimiento de la tercera forma normal (3FN), ya que cada atributo depende únicamente de su clave primaria.
