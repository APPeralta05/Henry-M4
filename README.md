# Proyecto Integrador M4

## Descripción

Este proyecto es parte del módulo 4 del curso de Data Analytics en Henry. El objetivo es analizar datos relacionados con COVID-19 en países de América Latina, utilizando técnicas de análisis de datos y visualización para obtener insights significativos.

## Contenido del Notebook

1. **Importación de Librerías**: Se importan las librerías necesarias para el análisis, incluyendo pandas, numpy, matplotlib, seaborn, y folium.

2. **Carga y Filtrado de Datos**: 
   - Se cargan los datos de un archivo CSV en fragmentos para optimizar el uso de memoria.
   - Se filtran los datos para incluir solo los países de interés: Argentina, Brasil, Chile, Colombia, México y Perú.

3. **Visualización de Datos**:
   - Se utiliza folium para crear mapas de calor que muestran la distribución geográfica de casos confirmados, muertes, dosis de vacunas administradas y recuperaciones.

4. **Análisis de Datos Faltantes**:
   - Se analiza la cantidad y porcentaje de valores faltantes en cada columna del DataFrame.
   - Se realizan transformaciones iniciales, como la conversión de la columna `date` a tipo datetime.

5. **Preparación de Datos para Power BI**:
   - Se establece la columna `date` como índice para facilitar su uso en Power BI.
   - Se guardan los datos procesados en un archivo CSV llamado `DatosFinalesFiltrado.csv`.

## Requisitos

- Python 3.13.0
- Jupyter Notebook
- Librerías: pandas, numpy, matplotlib, seaborn, folium

## Instrucciones de Instalación

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Python y Jupyter Notebook instalados.
3. Instala las librerías necesarias ejecutando:
   ```bash
   pip install pandas numpy matplotlib seaborn folium
   ```

## Ejecución

1. Abre Jupyter Notebook y navega hasta el archivo `PIDA_M4_Alejo_Nicolas_Peralta_Falconi.ipynb`.
2. Ejecuta las celdas en orden para reproducir el análisis y las visualizaciones.

## Notas

- Asegúrate de tener el archivo `data_latinoamerica.csv` en el mismo directorio que el notebook para cargar los datos correctamente.
- Los resultados del análisis se guardan en `DatosFinalesFiltrado.csv`.

## Autor

Alejo Nicolás Peralta Falconi