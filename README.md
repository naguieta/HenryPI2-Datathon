# HenryPI2-Datathon
## Análisis de precios de propiedades de Estados Unidos

En Base a dos archivos en formato Parquet, que contiene datos sobre las caracteristicas de propiedades, se nos pidió implementar un modelo con aprendizaje supervisado, que nos permita clasificar el precio de las propiedades en venta y un modelo con aprendizaje no supervisado para agrupar las propiedades en 3 categorias.

Para realizar esta tarea, se inicio con el archivo EDA.ipynb, en el cual se realizó el análisis exploratorio de datos.

Luego, dentro de la carpeta Limpieza, se encuentran dos archivos utilizados para limpiar los datos, la diferencia entre estos es que el primero elimina filas conteniendo valores nulos y el segundo no realiza este cambio.

Continuamos con la carpeta Proceso, el cual contiene los archivos con los modelos utilizados, separados por orden de entrega e indicando en los ultimos caracteres de su nombre si son modelos Supervisados (los nombres terminan con la letra S) o si son modelos no supervisados (los nombres terminan con las letras NS).

Finalmente en la carpeta Datasets, tenemos dos archivos con formato csv, que se obtuvieron luego de realizar la limpieza.
Seis archivos generados con el modelo supervisado en formato csv, los cuales se distinguen por contener en su nombre el formato "S#" al final (el # indica el orden en el cual fueron generados y entregados).
Tres archviso generados con el modelo no supervisado en formato csv, los cuales se distinguen por contener en su nombre el formato "NS#" al final (el # indica el orden en el cual fueron generados y entregados).

En este repositorio no se incluyen los archivos en formato parquet debido a su gran tamaño.
Los archivos parquet y los requerimientos del proyecto se pueden encontrar en el siguiente link https://github.com/soyHenry/Datathon 

