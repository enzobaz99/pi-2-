# pi-2-
para el proyecto nos pidieron hacer:
Implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición. ​ Para esto debe crear la columna category_price, en la cual se consideran las categorías
'low': Para precios entre 0 y 999 dólares (debe tomar valor 1 en el archivo con las predicciones).
'medium': Para precios entre 1000 y 1999 dólares (debe tomar valor 0 en el archivo con las predicciones).
'high': Para precios desde 2000 dólares en adelante (debe tomar valor 0 en el archivo con las predicciones). ​ considerando esta categorización, el objetivo es predecir si una propiedad pertenece a la categoría de precios bajos (low). ​
Implementar un modelo de clasificación con aprendizaje no supervisado, utilizando clustering que agrupe las propiedades por segun las 3 categorias a las que pueden pertenecer. Para ello, solo usaran el conjunto de datos de prueba proporcionado, eliminando previamente las caracteristicas que presentaban nulos. 
y nos dieron estos data:
Se proveen los siguientes archivos en formato parquet:
'tren.parquet': Contiene 346479 registros y 22 dimensiones, el cual incluye la información numérica del precio en la columna price.
'test.csv': Contiene 38498 registros y 21 dimensiones, el cual no incluye la información del precio.
Enlace al conjunto de datos: https://drive.google.com/drive/folders/1nJ9ZMj6E6zh6McC9NwCA6KopfUIOG_1O 
