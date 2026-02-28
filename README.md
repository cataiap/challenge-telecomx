# challenge-telecomx
Análisis de evasión de clientes (Churn) - Telecom X

# Desafío Telecom X — Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del proyecto
Este proyecto analiza la **evasión de clientes (Churn)** en Telecom X a partir de un dataset en formato **JSON**.  
El objetivo es **identificar patrones** asociados a la cancelación del servicio y proponer **insights y recomendaciones** para reducir la evasión.

El desarrollo se realizó en **Google Colab**, siguiendo un flujo ETL + Análisis Exploratorio (EDA), y finaliza con un informe dentro del mismo notebook.

---

## 🎯 Objetivo
- Medir la distribución de churn (clientes que permanecen vs los que cancelan).
- Limpiar y preparar datos (inconsistencias, tipos de datos, valores vacíos).
- Analizar churn según:
  - Variables categóricas (contrato, método de pago, tipo de internet, etc.)
  - Variables numéricas (tenure, cobros mensuales y totales, etc.)
- Entregar **conclusiones y recomendaciones** basadas en evidencia.

---

## 🗂️ Estructura del repositorio
- `Challenger.ipynb`: Notebook principal con:
  - ETL (carga + normalización + limpieza)
  - EDA (tablas + gráficos)
  - Informe final (introducción, metodología, insights, recomendaciones)
- `README.md`: Este archivo con guía del proyecto

---

## 📊 Dataset (fuente)
Los datos se cargan desde un archivo JSON del desafío (formato RAW/API).

Referencia (RAW) usada en el notebook (copiar/pegar en navegador si se necesita):
```txt
https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json
