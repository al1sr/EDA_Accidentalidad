# Análisis de accidentalidad en Madrid (2019-2025)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green?style=for-the-badge)

## Descripción del proyecto
Este proyecto realiza un análisis exhaustivo de los siniestros viales registrados por la Policía Municipal en la ciudad de Madrid durante un periodo de 6 años. El objetivo es consolidar múltiples fuentes de datos, limpiar la información y visualizar patrones temporales y geográficos de la accidentalidad.

**Dataset:** el análisis se basa en los microdatos abiertos del Ayuntamiento de Madrid, consolidando archivos anuales en un único corpus de **312,980 registros**.

## Tecnologías y librerías
* **Python**: procesamiento de datos.
* **Pandas**: unión de datasets (Merge/Concat) y limpieza.
* **Matplotlib / Seaborn**: generación de series temporales y gráficos de barras.

## Puntos clave del análisis

### 1. Consolidación de Big Data local
* **Unión de fuentes**: integración de 4 archivos CSV independientes (2019 a 2025) en un único Dataframe maestro.
* **Tratamiento de nulos**: identificación y gestión de valores faltantes en columnas críticas como `lesividad`.

### 2. Análisis de lesividad y tipología
* **Métricas de seguridad**: clasificación de accidentes por gravedad (desde asistencia sanitaria básica hasta fallecimientos).
* **Tipos de siniestros**: análisis de las causas más comunes (colisiones fronto-laterales, alcances, atropellos).

### 3. Patrones temporales
* **Análisis por horas**: identificación de las "horas punta" de accidentes (destacando el incremento a las 14:00 y las 18:00-19:00).
* **Análisis mensual**: comparativa de la siniestralidad a lo largo del año para detectar estacionalidad.

## ¿Cómo ejecutarlo?

1. Asegúrate de tener los archivos CSV de accidentalidad (2019 a 2025) en la misma carpeta que el notebook.
2. Instala las dependencias:
   ```bash
   pip install pandas matplotlib seaborn
   
3. Ejecuta el archivo `EDA_Accidentalidad.ipynb`

## Contexto académico

Este proyecto forma parte del módulo de Python para Data Science, enfocado en la capacidad de procesar grandes volúmenes de datos municipales y transformarlos en visualizaciones accionables.

**Desarrollado por:** Alicia Santamaría Román 

**Contacto:** https://linkedin.com/in/aliciasantamariaroman


