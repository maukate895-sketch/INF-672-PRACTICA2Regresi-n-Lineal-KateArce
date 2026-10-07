# INF-672-PRACTICA2Regresi-n-Lineal-KateArce
# 📊 Práctica 2: Regresión Lineal Múltiple — INF-672

**Estudiante:** Kate Arce  
**Carrera:** Ingeniería Informática — Universidad Autónoma Tomás Frías  
**Materia:** INF-672 (Inteligencia Artificial / Machine Learning)  

---

## 📌 Descripción del Proyecto

Este proyecto implementa y evalúa un modelo de **Regresión Lineal Múltiple** utilizando Python y Scikit-Learn para predecir los costos anuales del seguro médico individual a partir del conjunto de datos `insurance.csv`.

---

## 🛠️ Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3 (Jupyter Notebook)
* **Librerías Principales:**
  * `pandas` — Carga y manipulación de estructuras de datos
  * `numpy` — Operaciones numéricas
  * `scikit-learn` — Preprocesamiento (`get_dummies`), entrenamiento del modelo (`LinearRegression`) y métricas de evaluación (`r2_score`, `mean_absolute_error`)
  * `matplotlib` & `seaborn` — Visualización de datos y gráficos

---

## 📈 Resultados y Métricas del Modelo

* **Coeficiente de Determinación ($R^2$):** `0.7836` (El modelo explica el **78.36%** de la variabilidad de los costos).
* **Error Absoluto Medio (MAE):** `$4,181.19 USD`
* **Mediana del Costo Real:** `$8,487.88 USD`

### 🔍 Coeficientes Clave
1. **Fumador (`smoker_yes`):** Factor con mayor impacto en el costo, incrementándolo en promedio en **+$23,651.13 USD**.
2. **Edad (`age`):** Cada año adicional incrementa el costo en promedio unos **+$256.85 USD**.

---

## 📉 Visualización: Costo Real vs. Costo Predicho

![Gráfico de Predicciones del Modelo](https://raw.githubusercontent.com/maukate895-sketch/INF-672-PRACTICA2Regresi-n-Lineal-KateArce/main/practica2_Kate_Arce.ipynb)

---

## 📂 Contenido del Repositorio

* `practica2_Kate_Arce.ipynb`: Cuaderno Jupyter con la implementación de los 9 pasos del trabajo práctico.
* `README.md`: Documentación principal del proyecto.
