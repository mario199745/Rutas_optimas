# Análisis de Ruta Óptima Utilizando DEM en Python

Este repositorio contiene el Jupyter Notebook `route_optimal.ipynb`, el cual demuestra cómo calcular rutas óptimas considerando la elevación del terreno, utilizando un Modelo Digital de Elevación (DEM) para la provincia de Chumbivilcas.

## Objetivos

El notebook tiene como objetivo:
- Cargar y procesar un DEM para la provincia de Chumbivilcas.
- Identificar pares de puntos más cercanos utilizando un árbol KD.
- Calcular rutas óptimas entre estos pares de puntos considerando la elevación.
- Visualizar las rutas sobre el DEM.
- Exportar las rutas y sus costos asociados a un shapefile para análisis posterior en software GIS.

## Tecnologías Utilizadas

- Python 3.x
- Bibliotecas: `geopandas`, `rasterio`, `numpy`, `matplotlib`, `scikit-image`
- Datos: DEM de Chumbivilcas y un conjunto de puntos de interés específicos.

## Cómo Ejecutar

Para ejecutar este notebook, necesitarás tener Jupyter Notebook o JupyterLab instalado, así como las bibliotecas mencionadas anteriormente. Asegúrate de tener los datos necesarios en el directorio especificado o ajusta las rutas en el código según sea necesario.

1. Clona este repositorio o descarga el archivo `route_optimal.ipynb` directamente.
2. Instala las dependencias necesarias usando `pip`:
3. Abre el notebook en Jupyter y ejecuta las celdas en orden.

## Datos

El análisis se basa en los siguientes datos:
- Un Modelo Digital de Elevación (DEM) para la provincia de Chumbivilcas.
- Un shapefile que contiene un conjunto de puntos de interés en la misma provincia.

Asegúrate de actualizar las rutas de los archivos en el notebook para coincidir con la ubicación de tus archivos de datos.

## Contribuir

Las contribuciones al proyecto son bienvenidas. Por favor, envía un pull request o abre un issue para discutir los cambios propuestos o las adiciones.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.