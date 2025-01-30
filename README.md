
---

## 📊 **Metodología Aplicada (CRISP-DM)**  
Este proyecto sigue la metodología **CRISP-DM**, estructurando el flujo de trabajo en seis fases:

1️⃣ **Comprensión del Negocio**: Definir el problema y los factores clave en la supervivencia.  
2️⃣ **Comprensión de los Datos**: Exploración y análisis inicial del dataset del Titanic.  
3️⃣ **Preparación de los Datos**: Limpieza, transformación y creación de nuevas variables.  
4️⃣ **Modelado**: Implementación de Machine Learning y Clustering.  
5️⃣ **Evaluación**: Comparación de modelos utilizando métricas de desempeño.  
6️⃣ **Despliegue**: Generación de reportes y visualización de resultados.  

---

## 🔍 **Análisis Exploratorio de Datos (EDA)**
✔️ Visualización de la distribución de pasajeros según **sexo, clase y edad**.  
✔️ Análisis de correlaciones entre variables para la selección de características.  
✔️ Identificación y tratamiento de **valores atípicos** mediante **LOF**.  

---

## 📉 **Reducción de Dimensionalidad**
✔️ Aplicación de **Análisis Factorial** y **PCA** para reducir el número de variables sin perder información clave.  
✔️ Comparación del rendimiento del modelo con y sin reducción de dimensionalidad.  

---

## 🔬 **Clustering con K-Means y t-SNE**
✔️ Implementación del algoritmo **K-Means** para segmentar a los pasajeros en distintos clusters.  
✔️ Visualización en 2D del espacio **t-SNE** para analizar los grupos formados.  
✔️ Uso de la **Métrica de Silueta** para determinar el número óptimo de clusters.  

---

## 🤖 **Modelos de Machine Learning**
| **Modelo**       | **AUC Inicial** | **AUC con PCA** | **AUC sin Outliers** |  
|-----------------|---------------|---------------|------------------|  
| Random Forest   | 0.78          | 0.81          | **0.87**         |  
| Regresión Logística | 0.72      | 0.74          | 0.76             |  

✔️ Ajuste de hiperparámetros con **GridSearchCV**.  
✔️ Evaluación del modelo con la **Curva ROC** y **Matriz de Confusión**.  

---

## 📌 **Resultados Clave**
✔️ La eliminación de outliers mejoró el desempeño del modelo en un **9%**.  
✔️ La reducción de dimensionalidad con **PCA** mantuvo un buen nivel de predicción reduciendo el número de variables.  
✔️ El modelo **Random Forest con optimización de hiperparámetros** obtuvo el mejor desempeño (**AUC = 0.87**).  
✔️ Los clusters generados ayudaron a segmentar grupos con mayor probabilidad de supervivencia.  

---

## 🛠️ **Requisitos para Ejecutar el Proyecto**
Para ejecutar este proyecto en tu entorno local, instala las dependencias necesarias con:

```bash
pip install -r requirements.txt
