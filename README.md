# sprint7-final-project
Analisis de ConnectaTel donde se analizaron los copmpartamientos de los clientes de la empresa, detectando en los archivos: datos nulos, sentinels, evaluando la correcta imputacion, eliminacion o descarte de los mismos.
Descripción del Proyecto

Este proyecto consiste en un análisis exploratorio de datos (EDA) para ConnectaTel, una empresa de telecomunicaciones que ofrece planes de telefonía móvil a sus clientes.

El objetivo principal es comprender los patrones de uso de los clientes, identificar problemas de calidad de datos, detectar segmentos de usuarios y generar recomendaciones que ayuden a optimizar la oferta de planes comerciales.

Objetivos
Evaluar la calidad de los datos disponibles.
Detectar y corregir valores faltantes, sentinels y fechas inválidas.
Analizar el comportamiento de uso de los clientes.
Identificar segmentos de clientes según edad y nivel de consumo.
Detectar valores atípicos (outliers) relevantes para el negocio.
Proponer recomendaciones para mejorar la estrategia de planes de ConnectaTel.
Datasets Utilizados
plans.csv
usage.csv

Etapas del Análisis
1. Carga y exploración de datos
Importación de datasets.
Revisión de estructura, dimensiones y tipos de datos.
Exploración inicial de columnas.
2. Calidad de datos
Identificación de valores nulos.
Detección de sentinels.
Revisión de valores inválidos.
Validación de fechas.
Corrección de inconsistencias.
3. Transformación de datos
Agregación de métricas de uso por usuario.
Construcción de variables:
cant_mensajes
cant_llamadas
cant_minutos_llamada

Integración de información mediante joins.
4. Análisis exploratorio
Estadísticas descriptivas.
Distribución de clientes por plan.
Distribución de edad.
Distribución de mensajes.
Distribución de llamadas.
Distribución de minutos consumidos.
5. Detección de outliers
Visualización mediante boxplots.
Cálculo de límites utilizando el método IQR.
Evaluación del impacto de valores extremos.
6. Segmentación de clientes
Segmentación por grupo de edad.
Segmentación por nivel de uso:
Bajo uso
Uso medio
Alto uso
7. Recomendaciones de negocio
Identificación de clientes de alto valor.
Propuestas para optimizar los planes actuales.
Recomendaciones para nuevos productos y estrategias de segmentación.
Principales Hallazgos
Se identificaron problemas de calidad de datos relacionados con sentinels, valores faltantes y fechas fuera de rango.
La mayoría de los clientes pertenece al segmento de uso medio.
Los usuarios de alto consumo representan una oportunidad para planes premium.
No se observaron diferencias significativas de comportamiento por edad.
Los outliers detectados corresponden principalmente a usuarios intensivos y no a errores de captura.
Tecnologías Utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Cómo Ejecutar el Proyecto
Descarga o clona este repositorio:
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
Ingresa a Google Colab:
https://colab.research.google.com
Selecciona:
Archivo → Subir notebook
Carga el archivo:
S7 Version-Estudiante-Project-ConnectaTel.ipynb
Sube también los datasets:
plans.csv
users_latam.csv
usage.csv
Ejecuta las celdas en orden desde el inicio hasta el final.
Autor

Oscar Perez

Proyecto desarrollado como parte de mi portafolio de análisis de datos utilizando Python, Pandas y técnicas de Exploratory Data Analysis (EDA).
