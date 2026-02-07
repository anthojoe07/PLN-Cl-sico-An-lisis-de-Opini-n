# Análisis de Opinión en Repositorios Git: Facebook/React

Este proyecto aplica técnicas de Procesamiento de Lenguaje Natural (PLN) para analizar la salud y opinión de la comunidad en el repositorio `facebook/react`.

## Integrantes
* Karla Patricia Solorzano Parra
* Anthony Joel Toalombo Aisabucha
* Mayerly Kristel Veloz Alburquerque

## Estructura del Repositorio
* `data/`: Contiene el dataset `dataset_react.csv` recolectado vía API de GitHub con 900 registros.
* `src/`: Contiene el notebook `Proyecto_PLN.ipynb` con el pipeline de análisis (Limpieza, TF-IDF, Regresión Logística, K-Means).

##  Instrucciones de Ejecución
1. Clonar el repositorio.
2. Abrir el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3. Asegurarse de tener las librerías listadas instaladas (`pandas`, `scikit-learn`, `nltk`).
4. Ejecutar las celdas secuencialmente.

## Metodología
Se utilizó TF-IDF para vectorización, Regresión Logística para análisis de sentimiento y K-Means para detección de temas.
