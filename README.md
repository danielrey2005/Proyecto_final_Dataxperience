# 🔧 Mantenimiento Predictivo Industrial — Gemelo Digital

Proyecto final del curso de Ciencia de Datos. Aplica el ciclo completo de análisis de datos
(limpieza, estadística descriptiva, visualización, modelado predictivo y storytelling) sobre
datos reales de sensores de maquinaria industrial, con el objetivo de anticipar el desgaste
de herramienta y el riesgo de falla de un equipo.

## 🎯 Objetivo

Construir y validar un modelo de regresión lineal que prediga el torque de un motor a partir
de variables de sensores (velocidad rotacional, temperaturas, desgaste de herramienta), y
usar esos resultados para contar una historia sobre mantenimiento predictivo aplicada a la
Ingeniería Mecatrónica.

## 📊 Dataset

[AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601) (Matzka,
2020) — 10,000 registros sintéticos que replican el comportamiento de una fresadora
industrial real, con temperatura del aire, temperatura del proceso, velocidad rotacional,
torque, desgaste de herramienta y una etiqueta de falla de máquina.

## 🗂️ Contenido del repositorio

```
├── proyecto_final_Dataxperience.ipynb   # Notebook completo (Google Colab)
├── Dataxperience proyecto final.pbix    # Dashboard interactivo (Power BI Desktop)
├── dataset_power_bi.csv                 # Datos exportados del modelo, para el dashboard
└── README.md                            # Este archivo
```

## 🎥 Video final


## 🚀 Cómo ejecutar

**Notebook (Google Colab):**
1. Abre `proyecto_final_Dataxperience.ipynb` en [Google Colab](https://colab.research.google.com).
2. Ejecuta las celdas en orden — el dataset se descarga automáticamente desde UCI, no requiere
   subir ningún archivo. La última celda exporta `dataset_power_bi.csv` para el dashboard.

**Dashboard (Power BI Desktop):**
1. Abre `Dataxperience proyecto final.pbix` con Power BI Desktop.
2. Si Power BI pide reconectar el origen de datos, apunta a `dataset_power_bi.csv` en esta
   misma carpeta.

## 🧠 Etapas del proyecto

1. **Fundamentos y herramientas** — carga y librerías.
2. **Estadística descriptiva y preprocesamiento** — calidad de datos, distribuciones, escalado.
3. **Modelado y storytelling** — correlaciones, regresión lineal, validación del modelo
   (R², MAE, RMSE, residuales) y narrativa de aplicación profesional.
4. **Dashboard interactivo en Power BI** — KPIs, dispersión torque real vs. predicho, riesgo
   de falla por nivel de desgaste, mapa de correlaciones y segmentadores por tipo de máquina
   y nivel de desgaste.

## 👥 Autores

- Oscar Daniel Rey Arias — Ingeniería Mecatrónica, Universidad EAN
- Ronald Esneider Huérfano Rodríguez — Ingeniería Mecatrónica, Universidad EAN
