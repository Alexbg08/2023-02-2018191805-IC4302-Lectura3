# 2023-02-2018191805-IC4302-Lectura3

Alexander Brenes Garita - 2018191805

---------------------------------------------------------------------------------------------

1. ¿Es posible utilizar una base de datos SQL como una base de datos key-value?, ¿Cómo la implementaría? Comente las implicaciones de rendimiento

Sí, es posible utilizar una base de datos SQL como una base de datos key-value. Para eso, se puede crear una tabla con dos columnas: una columna para la clave y otra columna para el valor. Las claves deben ser únicas para cada registro.

Para implementar una base de datos SQL como una base de datos key-value, se pueden utilizar las siguientes instrucciones:

CREATE TABLE para crear la tabla.
INSERT INTO para insertar registros en la tabla.
SELECT para recuperar registros de la tabla.

Las implicaciones de rendimiento de utilizar una base de datos SQL como una base de datos key-value dependen de la aplicación específica. En general, las bases de datos SQL no están optimizadas para operaciones key-value, como las búsquedas y las actualizaciones por clave. Por eso, el rendimiento puede verse afectado.

2. ¿En qué consisten los datos polimórficos? Explique la razón por la cual estos son un buen caso de uso en bases de datos documentales.

Los datos polimórficos son aquellos que pueden tener diferentes tipos. Por ejemplo, un documento puede contener texto, imágenes, archivos adjuntos.
Las bases de datos documentales son un buen caso de uso para los datos polimórficos porque permiten almacenar diferentes tipos de datos en el mismo documento. Esto facilita la gestión de datos complejos y heterogéneos.
Por ejemplo, una base de datos documental podría utilizarse para almacenar los datos de un sitio web. En este caso, los documentos podrían contener texto, imágenes, videos, etc. Esto permitiría a los usuarios buscar y visualizar los datos de diferentes maneras.

3. Presente 5 ejemplos de sistemas/casos de uso que podrían soportar consistencia eventual, Explique

- Sistemas de recomendación: Los sistemas de recomendación suelen utilizar algoritmos de aprendizaje automático para generar recomendaciones a los usuarios. Estos algoritmos se ejecutan en diferentes nodos de un sistema distribuido. Es posible que las recomendaciones no sean consistentes en todos los nodos en todo momento, pero esto no afecta la funcionalidad del sistema.
- Sistemas de chat: Los sistemas de chat suelen utilizar un modelo de consistencia eventual para gestionar los mensajes. Los mensajes se envían a todos los usuarios en el chat, pero es posible que no se reciban todos los mensajes de inmediato. Esto no afecta la funcionalidad del chat, ya que los usuarios pueden ver los mensajes que se han enviado en el momento en que se han recibido.
- Sistemas de gestión de inventario: Los sistemas de gestión de inventario suelen utilizar un modelo de consistencia eventual para actualizar el inventario. Los cambios en el inventario se envían a todos los nodos del sistema, pero es posible que no se apliquen inmediatamente a todos los nodos. Esto no afecta la funcionalidad del sistema, ya que los usuarios siempre pueden ver el inventario más reciente.
- Sistemas de seguimiento de ubicación: Los sistemas de seguimiento de ubicación suelen utilizar un modelo de consistencia eventual para actualizar la ubicación de los objetos. Las actualizaciones de ubicación se envían a todos los nodos del sistema, pero es posible que no se apliquen inmediatamente a todos los nodos. Esto no afecta la funcionalidad del sistema, ya que los usuarios siempre pueden ver la ubicación más reciente de los objetos.
- Sistemas de análisis de datos: Los sistemas de análisis de datos suelen utilizar un modelo de consistencia eventual para actualizar los datos. Los cambios en los datos se envían a todos los nodos del sistema, pero es posible que no se apliquen inmediatamente a todos los nodos. Esto no afecta la funcionalidad del sistema, ya que los usuarios siempre pueden ver los datos más recientes.

4. ¿Por qué es importante que nativamente una base de datos NoSQL implemente un REST API?

API REST ofrecen una serie de ventajas que hacen que sean una opción importante para la interacción con bases de datos NoSQL como ejemplo, la Flexibilidad, Escalabilidad y Mantenimiento.

5. ¿Por qué la geo localización de la bases de datos NoSQL pueden ayudar a mantener leyes de Data sovereignty?

En general, la geolocalización de las bases de datos NoSQL puede ser una herramienta útil para las empresas que desean cumplir con las leyes de soberanía de datos. Al almacenar los datos en un país o región específico, las empresas pueden ayudar a garantizar que los datos se almacenen y procesen de manera segura y conforme a la ley.
