
# Análisis Exploratorio de Datos (EDA) - Books Details Dataset

Este repositorio contiene un **Análisis Exploratorio de Datos (EDA)** completo realizado en Python sobre un conjunto de detalles de libros (obtenido de Kaggle). El proyecto se enfoca en todo el ciclo de preprocesamiento, limpieza de datos, transformaciones avanzadas y visualización para extraer patrones de comportamiento en la industria literaria.

---

## Objetivos del Proyecto
* **Limpieza y Preparación:** Tratamiento de valores nulos, conversión de tipos de datos complejos y normalización de variables numéricas y categóricas.
* **Transformación Estructural:** Desglose de múltiples categorías contenidas en campos de texto (géneros literarios) para un análisis granular.
* **Análisis Estadístico:** Evaluación de correlaciones entre métricas de popularidad (cantidad de reseñas vs. calificaciones promedio).
* **Identificación de Tendencias:** Descubrimiento de los géneros dominantes y los autores mejor valorados del dataset.

---

## Tecnologías y Librerías Utilizadas
* **Python** (Entorno de programación principal)
* **Pandas** y **NumPy** (Manipulación, limpieza y estructuración de datos)
* **Matplotlib** y **Seaborn** (Visualización gráfica de datos y matrices de correlación)

---

## Principales Hallazgos y Conclusiones
1. **Géneros Dominantes:** Tras normalizar y desglosar los géneros múltiples de cada obra, se identificó que ***Fiction*, *Romance* y *Fantasy*** lideran ampliamente la presencia en el dataset.
2. **El Mito de la Popularidad:** Mediante el análisis de correlación, se comprobó que **no existe una correlación lineal fuerte** entre la cantidad total de reseñas o calificaciones de un libro y su puntaje promedio de calidad (`rating`). Obras con menor volumen de calificaciones pueden mantener promedios excelentes.
3. **Autores Destacados:** El agrupamiento por volumen total de calificaciones permitió perfilar a los autores de mayor tracción masiva en la muestra (como J.K. Rowling, Stephen King y Rick Riordan).

---


