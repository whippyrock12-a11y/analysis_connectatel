# Analysis_ConnectaTel

**📱 ConnectaTel: Análisis de Comportamiento y Segmentación de Clientes**
Este repositorio contiene el análisis integral realizado para la empresa de telecomunicaciones ConnectaTel, utilizando datos registrados hasta el año 2024.

El proyecto se enfoca en transformar datos crudos de uso (mensajes y llamadas) en perfiles estadísticos y segmentos estratégicos de clientes para la toma de decisiones.

**📂 Contenido del repositorio**
Analysis_ConectaTel.ipynb → Notebook principal con limpieza de datos, análisis exploratorio (EDA), detección de outliers mediante IQR, segmentación de usuarios e insights ejecutivos.

**▶️ Cómo abrir el notebook en Google Colab**
Haz clic en el siguiente botón para ejecutar el análisis de forma interactiva:
https://colab.research.google.com/drive/1Epk2jtqSyOsl6TdRafWf9-XJYXmc6xky?usp=sharing

**🧠 Objetivo del análisis**
Limpieza de Datos: Identificación y corrección de valores inconsistentes (como edades negativas) y valores faltantes.

Perfilamiento Estadístico: Análisis de la distribución de consumo de servicios (mensajes vs. llamadas).

Control de Calidad: Detección de valores atípicos (outliers) mediante el método del Rango Intercuartílico (IQR).

Segmentación: Clasificación de la base de datos en niveles de uso (Bajo, Medio, Alto) para identificar oportunidades de up-selling.

**📊 Principales Hallazgos (Insights)**
Comportamiento de Consumo: Se detectó una clara preferencia por el texto sobre la voz, con más de 22,000 registros de mensajes frente a 17,900 llamadas.

Anomalías de Datos: Se identificaron y trataron errores de sistema en la variable edad (valores sentinel de -999).

Estrategia Comercial: Se identificó un segmento de 109 usuarios de "Alto Uso" en el plan Básico que representan la oportunidad principal para migración al plan Premium.

Distribución: El consumo de servicios presenta una distribución sesgada a la derecha, indicando que la mayoría de los usuarios son consumidores moderados.

**🛠️ Tecnologías utilizadas**
Python

Pandas: Manipulación y limpieza de datos.

Matplotlib & Seaborn: Visualización de distribuciones y detección de outliers (Boxplots).

NumPy: Lógica de segmentación y operaciones matemáticas.
