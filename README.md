# Capstone-Project.
Trabajo final de Análisis de datos
Integrantes
Luis Alejandro Zavala Zavala
Estructura de archivos y carpetas
data: en esta carpeta se encuentran las bases de datos utilizadas en el proyecto

1.1. raw: esta carpeta contiene las bases de datos sin procesar

1.2. processed: esta carpeta contiene las bases de datos procesadas

notebooks: esta carpeta contiene los notebooks utilizados para el procesamiento de las bases de datos y el análisis

2.1 1_limpieza.ipynb: este archivo contiene el procedimiento para la limpieza de los datos

2.2. 2_analisis.ipynb: este notebook contiene los distintos análisis realizados con los datos ya limpios

2.3. 3_reporte.ipynb: este notebook corresponde al informe final. Describe el contexto general de los datos, el proceso de limpieza, los modelos probados y el modelo escogido, el chequeo de supuestos y la interpretación del modelo. Por último, se presentan las conclusiones y limitaciones finales.

Descripción del proyecto
El estudio busca explicar el precio según el resto de variables de la data seleccionada, para poder lograrlo se deberá pasar por un proceso de limpieza de datos, de analisis yfinalmente se correrá la regreción seleccionada.

Instrucciones
Todas las bases de datos utilizadas están disponibles en este repositorio. Para replicar los resultados, se deben ejecutar los notebook en el siguiente orden: 1_limpieza.ipynb, 2_analisis.ipynb y 3_reporte.ipynb.

Las siguientes librerías son necesarias para ejecutar los notebook:

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn import metrics
Por lo tanto, es importante asegurarse de haberlas instalado antes de replicar los notebook
