### Proyecto Visualización de Datos

* **Realizado por:** Johan Diaz y David Marquez

* **Objetivo principal:** Desarrollar un modelo de clasificación para predecir si una persona tiene un **buen estado físico** o no, basándose en variables como edad, peso, altura, frecuencia cardíaca, presión arterial, horas de sueño, calidad nutricional e índice de actividad.

* **Fase del proyecto:** **Análisis Exploratorio de Datos (EDA)**.

---

## **Descripción General**

En este *notebook*, exploraremos en detalle el conjunto de datos proporcionado para comprender la distribución, las relaciones y las características de las variables. El objetivo de esta fase es:

1.  **Limpiar y preprocesar los datos**.
2.  **Visualizar las distribuciones** de cada variable.
3.  **Identificar la asimetría y curtosis** de los datos.
4.  **Analizar la relación entre las variables** y la variable objetivo (`estado físico`).
5.  **Detectar valores atípicos** (*outliers*) y datos faltantes.

Los hallazgos de este análisis guiarán la siguiente fase, que se centrará en la selección de características y el desarrollo del modelo de clasificación.

---

## **Contenido del Notebook**

1.  **Carga de datos y preprocesamiento**: Descripción de la carga inicial de los datos y pasos de limpieza.
2.  **Análisis de variables numéricas**: Interpretación de histogramas y diagramas de caja (box plots) para cada variable.
3.  **Análisis de la variable objetivo (`estado físico`)**: Exploración de la distribución de la variable a predecir.
4.  **Análisis de correlaciones**: Medición y visualización de la relación entre las variables.
5.  **Resumen de hallazgos del EDA**: Conclusiones clave extraídas del análisis exploratorio que informarán las decisiones futuras.

```{tableofcontents}
```
