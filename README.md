# Análisis y Predicción de Transiciones en Fases del Sueño

![Banner de Ciencia de Datos](https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif)

## Resumen del Proyecto

Este repositorio contiene el proyecto final para la materia de Aprendizaje Automático, enfocado en el análisis de datos de conectividad cerebral para predecir las transiciones entre diferentes fases del sueño. Se realizó un preprocesamiento exhaustivo, un análisis exploratorio de datos (EDA) y se evaluaron múltiples modelos de clasificación para determinar la viabilidad de la predicción.

---

### ⚠️ ¡Importante! Sobre los Datos

El conjunto de datos original utilizado para este análisis es de carácter **privado y confidencial**, por lo que no puede ser publicado en este repositorio.

Para permitir la ejecución y revisión del código, se ha incluido una pequeña muestra de datos sintéticos en la carpeta `/sample_data/`. Este archivo (`sample_dataset.csv`) mantiene la misma estructura y columnas que el dataset original, pero con datos generados aleatoriamente. **Los resultados y conclusiones presentados en el notebook se basan en el dataset completo y privado.**

---

### Estructura del Repositorio

* **/sample_data/sample_dataset.csv**: Datos de muestra para ejecutar el notebook.
* **Sleep_Proyect.ipynb**: El Jupyter Notebook que contiene todo el proceso de análisis, desde la limpieza de datos hasta la modelación y conclusión.

---

### Tecnologías Utilizadas

* **Python 3.x**
* **Pandas & NumPy**: Para manipulación y análisis de datos.
* **Matplotlib & Seaborn**: Para visualización de datos.
* **Scikit-learn**: Para el preprocesamiento de datos y la implementación de modelos de Machine Learning.
* **XGBoost**: Para la implementación del modelo de Gradient Boosting.
* **Jupyter Notebook**: Como entorno de trabajo interactivo.

---


###  Análisis y Hallazgos Clave

El análisis de los datos de "Sleep Transitions" mostró un desbalance en la variable objetivo 'Transition', con predominio de transiciones "x_x", lo que llevó a filtrar clases para modelar transiciones reales. El análisis estadístico reveló variabilidad en las conexiones cerebrales, visualizada mediante gráficos de dispersión y box plots. Modelos de clasificación (Regresión Logística, Random Forest, XGBoost) aplicados a datasets filtrados y transformados por PCA arrojaron métricas bajas (<30%), indicando dificultad para predecir transiciones de sueño con las variables de conectividad cerebral. La reducción de dimensionalidad con PCA no mejoró el rendimiento. Se sugiere explorar nuevas técnicas de preprocesamiento, características adicionales o modelos más complejos, ya que las variables actuales podrían no ser suficientes para predicciones precisas.

---

### 👥 Colaboradores y Agradecimientos

Este fue un proyecto colaborativo desarrollado por:

* **Irving Rafael S. F.** - ([@MrChayote](https://github.com/MrChayote))
* **Daniel J. Ocampo. O.** - ([@Daniel27120](https://github.com/Daniel27120))
* **[A. David Catalan V.]** - ([@dadcat-cat](https://github.com/dadcat-cat))

Agradecimientos especiales al Dr Daniel Arzate-  por su guía y apoyo durante el desarrollo de este proyecto.

---
