# 📊 Employee Turnover Prediction with Logistic Regression

Este proyecto utiliza **Regresión Logística** para predecir la rotación (turnover) de empleados en una empresa, a partir de características relevantes del personal.

## 🧠 Objetivo

Predecir si un empleado se quedará o abandonará la empresa, utilizando un modelo de machine learning supervisado.

## 🗂️ Contenido

- `turnover_ml.ipynb`: Notebook principal con todo el análisis.
- Dataset (incluido o cargado desde fuentes externas).
- Modelado con `scikit-learn`.

## 🔍 Descripción del Dataset

El conjunto de datos incluye variables como:

- **Satisfaction_Level**: Nivel de satisfacción del empleado.
- **Last_Evaluation**: Última evaluación de desempeño.
- **Number_Project**: Número de proyectos asignados.
- **Average_Monthly_Hours**: Promedio de horas trabajadas por mes.
- **Time_Spend_Company**: Años en la empresa.
- **Work_Accident**: Si ha tenido accidentes laborales.
- **Left**: Variable objetivo (1 = renunció, 0 = no renunció).
- **Promotion_Last_5years**: Si fue promovido en los últimos 5 años.
- **Department**: Departamento.
- **Salary**: Nivel de salario (`low`, `medium`, `high`).

## ⚙️ Técnicas utilizadas

- Limpieza y preprocesamiento de datos.
- Visualización exploratoria (EDA).
- Codificación de variables categóricas.
- División de datos en entrenamiento y prueba.
- Entrenamiento de modelo de **Regresión Logística**.
- Evaluación del modelo (accuracy, matriz de confusión, etc).

## 📦 Requisitos

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (para visualización)

Instalación de dependencias:

```bash
pip install -r requirements.txt
