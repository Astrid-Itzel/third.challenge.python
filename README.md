# third.challenge.python

# Análisis de Evasión de Clientes - Telecom X LATAM

Este repositorio contiene el análisis completo del comportamiento de evasión (churn) de clientes para Telecom X LATAM, realizado con técnicas de limpieza, análisis exploratorio y modelos predictivos de machine learning.

---

## Descripción del Proyecto

El objetivo principal es identificar patrones y factores que influyen en la cancelación del servicio por parte de los clientes. Se utilizó un dataset público, que fue limpiado, transformado y analizado para luego entrenar modelos que predicen la probabilidad de churn.

---

## Estructura del Proyecto

- `TelecomX_LATAM.ipynb`: Notebook principal con todo el análisis, visualizaciones y modelos.
- `telecomcorregido.csv`: Archivo CSV con los datos limpios y preparados.
- `README.md`: Documento de presentación y guía del proyecto.

---

## Tecnologías y Librerías

- Python 3
- Pandas, NumPy (manipulación de datos)
- Matplotlib, Seaborn (visualización)
- Scikit-learn (modelos de machine learning: Regresión Logística, Random Forest)
- Jupyter Notebook / Google Colab (entorno de desarrollo)

---

## Cómo usar este proyecto

1. Clonar o descargar el repositorio.
2. Abrir el notebook `TelecomX_LATAM.ipynb` en Jupyter o Google Colab.
3. Ejecutar las celdas para cargar, limpiar y analizar los datos.
4. Explorar los resultados y las métricas de los modelos.
5. Revisar las conclusiones y recomendaciones finales.

---

## Resultados destacados

- La tasa de evasión es aproximadamente 26.58% del total de clientes.
- Modelos utilizados:
  - Regresión Logística con accuracy ~0.777 y F1-score ~0.414.
  - Random Forest con accuracy ~0.
