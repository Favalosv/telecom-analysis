# Análisis de Clientes de ConnectaTel

## Objetivo del Proyecto
Analizar el comportamiento de los clientes de ConnectaTel. El análisis trata en la segmentación de clientes, patrones de uso, y recomendaciones de optimización de planes.

## Datasets Utilizados
Se utilizaron tres datasets:
1. **plans.csv**: Información sobre los planes actuales, incluyendo precio, minutos, GB y costos por extras.
2. **users_latam.csv**: Información de los clientes, como edad, ciudad, fecha de registro, plan y churn.
3. **usage.csv**: Detalles sobre el uso real de los servicios, como llamadas y mensajes.

## Etapas del Análisis Realizado
El análisis se realizó en las siguientes etapas:
1. **Exploración inicial de datos**: Carga y revisión de los datasets, identificando problemas en los datos y registros faltantes.
2. **Detección de valores inválidos y sentinels**: Identificación de valores con errores o fuera de rango y corrección de los mismos.
3. **Revisión y estandarización de fechas**: Asegurar que las columnas de fecha tuvieran el formato correcto y ademas revisar años imposibles.
4. **Análisis descriptivo**: Cálculo de estadísticas descriptivas de las columnas relevantes, incluyendo medidas de tendencia central y dispersión.
5. **Visualización de distribuciones y outliers**: Creación de histogramas y boxplots para entender las distribuciones de uso.
6. **Segmentación de clientes**: Creación de segmentos de clientes en base al uso de los servicios (Bajo, Medio, Alto) y por edad (Joven, Adulto, Adulto Mayor).
7. **Generación de insights**: Generación de conclusiones ejecutivas basadas en los patrones de uso y segmentación, con recomendaciones para mejorar los planes.

## Cómo Ejecutar el Notebook

1. Abrir el notebook en **Google Colab** o en entorno de Jupyter.
2. Asegúrate de tener las librerías necesarias instaladas.
  
   Librerías:

```bash
pip install pandas matplotlib seaborn numpy
