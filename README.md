# Clasificación Socioeconómica mediante Machine Learning con base en el uso de servicios de telecomunicaciones 📊

Este proyecto tiene como objetivo desarrollar un modelo predictivo capaz de clasificar el estrato socioeconómico de hogares basándose en variables demográficas y de equipamiento tecnológico. Es una herramienta clave para el análisis de segmentación y diseño de políticas públicas o estrategias de mercado.

## 🚀 Resumen del Proyecto

El desarrollo abarca desde el análisis exploratorio de datos (EDA) hasta la evaluación de múltiples modelos de clasificación, priorizando la precisión y la capacidad de generalización del modelo.

### Características Principales:
* **Dataset:** Análisis basado en la encuesta anual de hogares (ENDUTIH).
* **Modelamiento:** Evaluación de algoritmos supervisados para clasificación multiclase.
* **Ingeniería de Datos:** Limpieza profunda, manejo de valores nulos y transformación de variables.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
* **Entorno:** Jupyter Notebook.

## 💡 Decisiones Técnicas Destacadas

Uno de los puntos críticos del proyecto fue el tratamiento de las variables categóricas. Tras evaluar diferentes enfoques, se optó por la implementación de **Label Encoding**. 

**¿Por qué Label Encoding?**
Dada la naturaleza de las variables y para evitar la expansión excesiva del espacio de características (maldición de la dimensionalidad) que produciría un One-Hot Encoding, se seleccionó esta técnica. Esto permitió mantener un modelo más ligero, eficiente y con un rendimiento superior en la detección de patrones jerárquicos dentro de los estratos.

## 📈 Resultados
* Se realizaron pruebas con distintos clasificadores (Random Forest, entre otros).
* El modelo final logra un equilibrio óptimo entre *precision* y *recall*, permitiendo una clasificación confiable de los diferentes niveles socioeconómicos.

## 📁 Estructura del Repositorio
* `ML_Proyecto2.ipynb`: Notebook principal con todo el pipeline de Ciencia de Datos.
* `tr_endutih_hogares_anual_2024.csv`: Dataset utilizado para el entrenamiento y validación.

---
**Desarrollado por:** [Juan Diego](https://github.com/JuanDiego076)
*Ingeniero de Telecomunicaciones | Data Scientist*
