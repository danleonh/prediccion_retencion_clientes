# Proyecto 14 – Análisis del Comportamiento de Clientes y Predicción de Retención

## 📋 Descripción general
El objetivo de este proyecto fue **analizar los patrones de comportamiento de los clientes y predecir su retención** para una cadena de gimnasios.  
Se desarrollaron modelos de clasificación y segmentación que permitieron identificar los factores que más influyen en la pérdida de clientes, con el fin de **diseñar estrategias efectivas de retención y fidelización**.

---

## 🎯 Objetivos
- Predecir la probabilidad de que un cliente abandone el gimnasio.  
- Identificar los factores con mayor impacto en la cancelación de membresías.  
- Crear **clústeres de usuarios** según características de comportamiento.  
- Formular recomendaciones basadas en datos para mejorar la retención y optimizar campañas de marketing.

---

## 🧮 Datos utilizados
**Dataset principal:**  
- `gym_churn_us.csv` – Información de clientes: características demográficas, uso de servicios y métricas de asistencia.  

Campos principales:  
`gender`, `Near_Location`, `Partner`, `Promo_friends`, `Phone`, `Age`, `Lifetime`,  
`Contract_period`, `Month_to_end_contract`, `Group_visits`, `Avg_class_frequency_total`,  
`Avg_class_frequency_current_month`, `Avg_additional_charges_total`, `Churn`.

---

## 🧰 Herramientas y librerías
- Python  
- pandas, numpy, matplotlib, seaborn, plotly  
- scikit-learn (Logistic Regression, Random Forest, K-means)  
- Jupyter Notebook  

---

## 📊 Etapas del análisis
1. **Carga y limpieza de datos** – detección de valores nulos y revisión de distribuciones.  
2. **Análisis exploratorio (EDA)** – comparación entre clientes activos y cancelados.  
3. **Modelado predictivo** – regresión logística y bosque aleatorio.  
4. **Evaluación de métricas** – precisión, recall y F1-score para comparar modelos.  
5. **Segmentación con K-means** – agrupamiento de clientes en función de su comportamiento.  
6. **Recomendaciones estratégicas** basadas en los resultados del modelo y los clústeres.  

---

## 🔍 Resultados principales
- El modelo de **Bosque Aleatorio** alcanzó una **precisión de 93 %** en la predicción de cancelación.  
- Factores más relevantes: **duración del contrato, frecuencia de visitas y antigüedad del cliente.**  
- Se identificaron **5 clústeres principales** con distintos niveles de riesgo de abandono.  
- Los grupos con menor frecuencia de asistencia y contratos mensuales tuvieron la mayor tasa de cancelación.  

---

## 💡 Conclusiones
- La predicción de cancelación permite anticipar pérdidas y enfocar esfuerzos en clientes de alto riesgo.  
- Los resultados sugieren que los **contratos de largo plazo y la asistencia grupal** reducen la rotación.  
- Se recomienda implementar **campañas personalizadas** según el perfil de cada clúster.  
- Este enfoque puede mejorar la retención general hasta en un **15–20 %**, optimizando los recursos de marketing.  
