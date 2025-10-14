# 📈 DATA ANALYTICS: MACHINE LEARNING APLICADO AL MARKETING DIGITAL

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

Este proyecto de Data Analytics se centra en el uso de **Machine Learning para predecir el comportamiento de los usuarios** que navegan en un E-commerce (el Google Merchandising Store). El objetivo principal es **pronosticar la cantidad que los clientes gastarán** basándose en sus características de navegación y actividad en la web.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Preparación y Limpieza de Datos
- **Carga de Datos:** Se utiliza la base de datos de navegación de clientes en formato CSV, proveniente de Google Analytics.
- **Inspección y Conversión de Tipos:** Se identifica el total de clientes únicos (`9996`) y se realiza la corrección de tipos de datos, pasando columnas como `date`, `fullVisitorId` y `visitId` a tipo *object* para un análisis correcto.
- **Ingeniería de Características (*Feature Engineering*):** Se trabaja en la agregación de datos para obtener el número de visitas (`visitNumber`) únicas por cliente (`fullVisitorId`) y se identifica la información de la última visita.

### 2️⃣ Modelado Predictivo (Regresión)
- **Modelos Iniciales:** Se parte de modelos base para la predicción del gasto del cliente (función inferida de la meta de "pronosticar cuánto van a gastar").
- **Optimización con *Gradient Boosting***: Se aplica el algoritmo **Gradient Boosting** para mejorar el método de aprendizaje del modelo, donde múltiples predictores se auto-mejoran continuamente a partir de la predicción anterior.

### 3️⃣ Evaluación de Rendimiento
- **Métrica Clave:** La precisión de las predicciones se mide utilizando el **Error Cuadrático Medio de la Raíz (RMSE)**.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Pandas**     | Carga, inspección y manipulación de DataFrames|
| **NumPy**      | Cálculos numéricos y manejo de estructuras de datos eficientes|
| **Scikit-learn** | Implementación de modelos como Gradient Boosting (inferido) |
| **Matplotlib / Seaborn** | Visualización de datos (uso inferido) |

---

## 🎯 Objetivo del Proyecto
Aplicar y mejorar modelos de Machine Learning para obtener predicciones precisas sobre el **gasto futuro de los clientes** de un E-commerce, demostrando el flujo de trabajo de un científico de datos (70% preparación de datos, 30% modelado) y proporcionando conocimientos útiles para el marketing digital.

---

## 📈 Resultados Clave
- Se demuestra una mejora significativa en la precisión al utilizar **Gradient Boosting**.
- El RMSE inicial de 25 se **reduce a 23** con el modelo optimizado, obteniendo resultados mucho más exactos.
- Se anima a explorar hiperparámetros y modelos *ensemble* para seguir mejorando las métricas de precisión.
