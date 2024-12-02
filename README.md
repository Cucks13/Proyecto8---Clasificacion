# Proyecto - Predicción de Rotación de Empleados

Este repositorio contiene el desarrollo completo de un proyecto orientado a predecir la rotación de empleados en una empresa. A través de un análisis exhaustivo de datos y el desarrollo de modelos de machine learning, se busca identificar factores clave que influyen en la rotación y generar predicciones precisas.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

````
├── data/
│   ├── raw/
│   |  ├── con_duplicados/
│   |  └── sin_duplicados/
│   └── cooked/
├── notebooks/
│   ├── con_duplicados/
│   └── sin_duplicados/
├── src/
├── .gitignore
└── README.md
  ````


---

## **Notebooks**

El análisis y el desarrollo del proyecto se encuentran documentados en los notebooks los cuales estan separados por si se han incluido los duplicados o no 

1. **`01_EDA_y_preprocesamiento.ipynb`**  
   - Contiene un análisis exploratorio general sobre los datos, con visualizaciones y análisis estadísticos clave para entender los patrones en la rotación de empleados.

2. **`02_Mejor_Modelo.ipynb`**  
   - Desarrolla modelos básicos como Árboles de Decisión y Regresión Logística para establecer un punto de referencia inicial en las métricas de predicción.


---



## ✨ Resultados Destacados

Se desarrollaron modelos con un rendimiento notable, basados en métricas como **Accuracy**, **F1-Score** y **AUC**:

- **Modelos menos exactos** (Árbol de Decisión y Regresión Logística):  
  - Accuracy promedio: ~85%.
  - AUC promedio: ~0.71.

- **Modelos más exactos** (Gradient Boosting y XGBoost):  
  - Accuracy promedio: ~87%.
  - AUC promedio: ~0.89.

Consulta los notebooks de modelos para más detalles y comparativas completas.

---

## 📊 Conclusiones

Puedes leer en detenimiento los archivos de ``02_Mejor_Modelo.ipynb`` si quieres comprender que ha ocurrido en cada modelo

---



## 🚀 Next Steps

A continuación, se detallan los próximos pasos sugeridos para expandir y mejorar este proyecto:

1. **Entrenar el modelo con mayor cantidad de datos**:

2. **Despliegue del Modelo**:
   - Crear una API o aplicación interactiva con **Streamlit** para predicciones en tiempo real.
   - Diseñar una interfaz amigable que permita a los usuarios cargar datos y visualizar resultados fácilmente.

3. **Visualización Interactiva**:
   - Implementar dashboards interactivos con **plotly** o **Streamlit** que permitan explorar los resultados y las predicciones del modelo.

5. **Análisis Explicativo**:
   - Utilizar técnicas interpretativas como **SHAP** para identificar los factores más importantes en la rotación de empleados y comunicar estos resultados a las partes interesadas.

---
