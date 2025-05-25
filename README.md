# 🌟 HADA – Herramienta Analítica para Detección de Anomalías

🔍 Este repositorio contiene el desarrollo del prototipo funcional HADA, una solución analítica diseñada para facilitar la detección temprana de anomalías operativas en clientes industriales de Contugas, mediante el análisis de presión, temperatura y volumen hora a hora. El sistema integra machine learning (Random Cut Forest), visualización interactiva en Power BI y arquitectura en la nube sobre AWS para lograr un monitoreo casi en tiempo real, escalable y sin supervisión manual.

🎥 Te recomendamos ver primero el video del proyecto en el siguiente [enlace](https://youtu.be/I1b1JT9TBwc?si=n4BB-q7N1lB6LqhT)

📊 [Enlace al dashboard](https://app.powerbi.com/groups/me/reports/51f1a343-1949-4e91-a144-e0dfcac5f369/d4f7cfdfa52b4d24098b?experience=power-bi)

## 📁 Organización 

```
├── 📘 README.md                   <- Este archivo, con descripción general del proyecto.
├── 📂 data
│   ├── contugas.xlsx               <- Datos originales proporcionados por Contugas.
│   ├── df_aggregated.csv           <- Dataset final usado para el dashboard.
├── 📂 notebooks
│   ├── 1.0-eda.ipynb               <- Análisis exploratorio de datos (EDA).
│   └── 2.0-modelo.ipynb            <- Implementación y validación del modelo Random Cut Forest.
├── 📂 dashboard
│   └── Dashboard.pbix              <- Archivo de Power BI con visualización interactiva.
├── 📂 docs
│   ├── manual-de-uso.pdf           <- Manual completo de uso (usuarios y técnicos).
│   └── guia-rapida.pdf             <- Guía rápida para operadores.
│   └── tabla-requerimientos.pdf    <- Evaluación de los requerimientos pactados inicialmente.
├── 📂 reports
│   ├── reporte-modelo.pdf          <- Reporte de selección y ajuste del modelo.
│   └── reporte-datos.pdf           <- Reporte de análisis y limpieza de los datos.
```

📝 *Nota: Por motivos de integración y costos de infraestructura, esta versión del prototipo no se encuentra conectada a sensores en tiempo real. En su lugar, trabaja sobre un archivo .csv con los datos generados por el modelo implementado.*