# Telecom X — Análisis de Evasión de Clientes (Churn)

## Objetivo
Aplicar un proceso ETL (Extracción, Transformación y Carga) desde una API (JSON) y realizar un Análisis Exploratorio de Datos (EDA) para identificar factores asociados al churn.

## Herramientas
Python, Pandas, NumPy, Requests, Matplotlib.

## Resultados principales
- Churn (sin Unknown): ~26.5%
- Mayor churn: contrato Month-to-month (~42.7%)
- Mayor churn: método de pago Electronic check (~45.3%)
- Mayor churn: internet Fiber optic (~41.9%)
- Churn asociado a cargos mensuales más altos y menor tenure.

## Archivos
- `TelecomX_LATAM.ipynb`: notebook con ETL + EDA + conclusiones.
- `TelecomX_clean.csv`: dataset limpio exportado.
