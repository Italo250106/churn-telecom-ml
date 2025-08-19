📂 Carpeta data/

Esta carpeta contiene los datasets utilizados en el modelo de churn para telecomunicaciones. Incluye datos originales, procesados y transformados para distintos fines del proyecto.

📊 Archivos incluidos
Archivo	Descripción
telecom_std.csv	Dataset estándar con datos originales.
telecom_tratado.csv	Dataset preprocesado con limpieza básica.
df_model_churn.csv	Dataset principal usado en el modelado de churn.
telecom_encoded.csv	Dataset con variables codificadas para análisis.
telecom_encoded_ml.csv	Dataset preparado para entrenamiento de modelos de ML.
telecom_minmax.csv	Dataset normalizado con MinMaxScaler.
🛠️ Uso en Python

Ejemplo de cómo cargar los datasets en un entorno de trabajo con pandas:

import pandas as pd

# Cargar dataset principal
df = pd.read_csv("data/df_model_churn.csv")

# Revisar primeras filas
print(df.head())

🔎 Notas importantes

Todos los archivos están en formato CSV con codificación UTF-8.

El dataset df_model_churn.csv es el principal para entrenar y evaluar modelos.

Los demás archivos corresponden a etapas intermedias de preprocesamiento y transformación.
