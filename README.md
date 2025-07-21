# CHA_LLE_GE_REP_TEL_CO_M-_2
readme


# 📊 Predicción de Cancelación de Clientes - TelecomX2 LATAM

Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes de la empresa **TelecomX2 LATAM**, utilizando técnicas de análisis exploratorio, visualización de datos, modelos de clasificación y validación estadística.

---

## 📁 Contenido del Proyecto

- `TelecomX_Data.json`: Base de datos original con información demográfica y de servicio.
- `v9_TelecomX2_LATAM.ipynb`: Notebook con todo el flujo de trabajo del proyecto.
- `v9_TelecomX2_LATAM_GRAFICAS.ipynb`: Versión extendida con visualizaciones finales y conclusiones.
- `modelos/`: (opcional) Carpeta para guardar modelos entrenados.
- `reporte/`: Documentación final y gráficas exportadas.

---

## 🎯 Objetivos del Proyecto

- Identificar patrones en el comportamiento de cancelación de clientes.
- Determinar las variables que más influyen en la evasión.
- Construir un modelo predictivo confiable.
- Proponer estrategias de retención basadas en los hallazgos.

---

## 🧪 Herramientas Utilizadas

- Lenguaje: `Python 3.x`
- Librerías principales:
  - `pandas`, `numpy` → manipulación de datos
  - `matplotlib`, `seaborn` → visualización
  - `scikit-learn` → modelado y evaluación
- Jupyter Notebook para desarrollo interactivo.

---

## ⚙️ Metodología

1. **Carga y limpieza de datos**
   - Conversión de tipos, renombramiento y normalización.
2. **Análisis exploratorio (EDA)**
   - Boxplots, histogramas, matriz de correlación.
3. **Modelado**
   - Árbol de decisión, validación cruzada con `StratifiedKFold`.
   - Balanceo de clases con `Oversampling` y `Undersampling`.
4. **Evaluación**
   - Métricas: exactitud, precisión, sensibilidad, F1 y especificidad.
   - Curvas ROC y precisión vs sensibilidad.
5. **Visualización avanzada**
   - Distribución de tarifas mensuales y contratos vs cancelación.

---

## 🔍 Principales Hallazgos

- **Clientes con contratos mensuales** y **alta tarifa mensual** son más propensos a cancelar.
- El **tiempo de permanencia bajo** (< 10 meses) es un predictor clave de cancelación.
- El uso de **servicios adicionales** (soporte técnico, protección, respaldo) mejora la retención.
- El modelo con validación cruzada obtuvo una sensibilidad promedio aceptable, con oportunidades de mejora.

---

## 🛡️ Recomendaciones

- Incentivar contratos a largo plazo.
- Diseñar programas de fidelización para los primeros meses.
- Personalizar ofertas para clientes de alto valor y riesgo.
- Aplicar el modelo predictivo para intervención proactiva.

---

## 🧠 Autor

**Lisfaver Castro Díaz**  
Proyecto desarrollado con acompañamiento de Nix (ChatGPT AI).  
Fecha: Julio 2025

---

## 📌 Licencia

Este proyecto es de uso académico y formativo. Para uso comercial, contactar al autor.
