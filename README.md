# 🤖 Predicción de inserción laboral universitaria (ML)

Este repositorio contiene el núcleo de inteligencia artificial del _proyecto de BI de la asignatura Gestión de la Comunicación y Conocimiento Empresarial del Máster de Ingeniería Informática de la ULL_, sobre el desempleo juvenil en Canarias. El objetivo principal es transitar del análisis descriptivo a la **analítica predictiva**.

## 🎯 Objetivo del modelo
El script modela la probabilidad de éxito laboral de los egresados universitarios en Canarias, proyectando su evolución desde el momento de la graduación hasta **5 años después (20 trimestres)**.

## 📂 Contenido del repositorio
* **`ml_predic_laboral.ipynb`**: Cuaderno Jupyter con el ciclo completo de Machine Learning (Preprocesamiento, entrenamiento y validación).

## 🛠️ Stack ctecnológico
* **Lenguaje:** Python 3.12
* **Librerías:** Pandas, Scikit-Learn, NumPy, Matplotlib/Seaborn.
* **Entorno:** Jupyter Notebook / PostgreSQL.

## 🚀 Metodología
1.  **Ingeniería de características:** Limpieza e integración de las tasas de inserción académica anuales.
2.  **Entrenamiento:** Implementación de un modelo de aprendizaje supervisado para estimar la tasa de empleo.
3.  **Simulación:** Generación de un ecosistema de datos sintéticos que cubre todos los posibles escenarios de inserción por rama, sexo y título (Grado/Máster).

---
*Este modelo alimenta la pestaña de "Machine Learning" en el Dashboard de Apache Superset del proyecto principal.*