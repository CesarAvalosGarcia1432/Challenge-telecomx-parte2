
# 📊 TelecomX LATAM — Predicción de Churn

## 📌 Descripción del proyecto
Este proyecto tiene como objetivo **analizar y predecir la cancelación de contratos (Churn)** en la empresa **TelecomX LATAM**, con el fin de implementar estrategias efectivas de retención de clientes.  
Se utilizan técnicas de **análisis exploratorio de datos (EDA)**, **preprocesamiento** y **modelos de Machine Learning** para identificar a los clientes con mayor probabilidad de cancelar su contrato.

---

## 🎯 Objetivos
- Identificar los **principales factores** que influyen en la cancelación de clientes.
- Entrenar y evaluar **modelos predictivos** para estimar la probabilidad de churn.
- Proponer **estrategias de retención** basadas en los hallazgos del análisis.
- Implementar un flujo reproducible desde el análisis de datos hasta la recomendación de acciones.

---

## 📂 Estructura del proyecto
TelecomX_LATAM/
│
├── data/ # Datos originales y procesados
├── notebooks/ # Jupyter Notebooks con el análisis y modelos
├── README.md # Descripción del proyecto

## 🛠️ Tecnologías utilizadas
- **Lenguaje**: Python 3.x
- **Bibliotecas principales**:
  - Pandas, NumPy → manipulación de datos
  - Matplotlib, Seaborn → visualización
  - Scikit-learn → modelado predictivo
  - Jupyter Notebook → análisis interactivo

---

## 📊 Modelos utilizados
1. **Regresión Logística**
   - Mejor desempeño general.
   - Accuracy: 0.817  
   - F1-score: 0.815  
   - Alta interpretabilidad y buena calibración de probabilidades.
   
2. **Árbol de Decisión**
   - Accuracy: 0.771  
   - F1-score: 0.771  
   - Posible overfitting leve

---

## 🔍 Principales hallazgos
- Factores que reducen churn:
  - Contratos a largo plazo
  - Mayor antigüedad del cliente (*tenure*)
  - Internet de mejor calidad
  - Servicios adicionales como **OnlineSecurity** y **TechSupport**
- Factores que aumentan churn:
  - Alta mensualidad (*Charges.Monthly*)
  - Alta fricción o incidencias (*Cuentas_Diarias*)

---

## 🚀 Ejecución del proyecto

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/usuario/telecomx-latam-churn.git
   cd telecomx-latam-churn
