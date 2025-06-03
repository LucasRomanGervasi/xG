*****SE PUEDE PREDECIR UN GOL MEDIANTE UN REMATE? *****


***OBJETIVO***

El objetivo de este trabajo es desarrollar un modelo de clasificación para predecir la probabilidad de gol a partir de remates registrados en partidos de fútbol. Utilizando un conjunto de datos de eventos de remates, se analiza información relevante como la distancia al arco, el ángulo del remate, el tipo de remate y la posición del arquero. Logramos limpiar y explorar el dataset que brinda statsbomb, identificando variables claves que servirán de base para el desarrollo del modelo predictivo en las siguientes etapas.

📝 **Pasos para reproducir el proyecto**

📁 Ir a datastatsbomb/

En esta carpeta normalmente se realiza la descarga de los datos desde la API de StatsBomb.

En este caso, ya contamos con los archivos necesarios descargados. 
(https://drive.google.com/file/d/1OULWoGzLQpyvjNkvGCM7G1hAgJg3I3SV/view?usp=drive_link)

Por lo tanto, dirigirse directamente a la sección (CAJA nro 6) donde se carga el archivo eventosremates.csv y comenzar con el proceso de limpieza.

🧹 **Limpiar el dataset**
En el archivo correspondiente dentro de datastatsbomb/, realizar:

Filtrado de eventos específicos relacionados a remates.

Se unió el dataset de información de jugadores, por lo tanto se necesita este dataset para continuar https://drive.google.com/file/d/11ANTD4yiwfjHVQTIKQinDCbxso87Zp9W/view?usp=sharing

Eliminación de columnas irrelevantes.

Creación de variables.

El resultado de esta limpieza será utilizado en el siguiente paso.

ACÁ ESTÁ EL DATASET FINAL https://drive.google.com/file/d/1l48s6PF40nay0seLMyFLStLkHeahZGnf/view?usp=drive_link

📂 Ir a dataremates/

En esta carpeta ya se trabaja con el dataset limpio.

Nos divertimos un poco con los gráficos para entender mejor los datos, explorando cómo se distribuyen los remates y qué variables podrían influir en el resultado del disparo.

📁 Ir a modeloremates/
En esta carpeta se encuentra el modelo de regresión logística.

Se entrena el modelo utilizando el dataset generado.

Se evalúa el rendimiento del modelo y se muestran métricas.
