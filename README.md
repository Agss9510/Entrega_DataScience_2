# 📊 Predicción de Fuga de Clientes - Telco Churn

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es identificar a los clientes con mayor probabilidad de abandonar la empresa de telecomunicaciones. Utilicé un modelo de **Machine Learning (XGBoost)** para predecir el comportamiento basándome en datos históricos.

## 🔍 Hallazgos Clave (EDA)
Durante el análisis inicial, descubrimos que los clientes con mayor riesgo de fuga son aquellos que:
* Tienen contratos **mes a mes**.
* Utilizan **fibra óptica**.
* Pagan mediante **cheque electrónico**.

## 🤖 El Modelo
Implementé un modelo de clasificación con las siguientes características:
* **Algoritmo:** XGBoost.
* **Ingeniería de Variables:** Creé variables personalizadas como `Nivel_Retencion` para mejorar la precisión.
* **Efectividad:** El modelo logra detectar más del **90% de las fugas reales** (Recall).

## 📈 Resultados
El proyecto incluye un **Top 10 de clientes en riesgo inminente**, lo que permite al departamento de marketing actuar de inmediato para retenerlos.
