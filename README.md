# ClusterEval: K-means vs DBSCAN on Credit Card Data

## Objetivo del proyecto

Proyecto de agrupamiento no supervisado con K-means y DBSCAN sobre datos de clientes de tarjetas de crédito. Se comparan ambos algoritmos utilizando **Silhouette Score** e **Índice de Calinski-Harabasz**, analizando cohesión de grupos, detección de outliers y forma de los clusters.

## Dataset

- Kaggle: [Credit Card Data](https://www.kaggle.com/arjunbhasin2013/ccdata)

## Tecnologías utilizadas

- Python · Pandas · NumPy  
- Matplotlib · Seaborn  
- Scikit-learn (StandardScaler, PCA, KMeans, DBSCAN)

## Flujo de trabajo

1. **Carga y exploración** del dataset con variables relevantes como gasto total y frecuencia de uso.
2. **Preprocesamiento**: eliminación de valores nulos y atípicos + estandarización con `StandardScaler`.
3. **Reducción de dimensionalidad** opcional con PCA para visualización.
4. **Aplicación de algoritmos de clustering**:
   - `KMeans`: número óptimo de clusters via método del codo.
   - `DBSCAN`: ajuste manual de `eps` y `min_samples`.
5. **Evaluación mediante métricas**:
   - Silhouette Score
   - Calinski-Harabasz Index
6. **Visualización y análisis interpretativo** de la forma de los clusters y detección de outliers.

## Hallazgos Clave

- K-means genera grupos estructurados con buena separación.
- DBSCAN identifica zonas densas y outliers, pero con menor cohesión.
- Visualmente, K-means ofrece fronteras claras; DBSCAN muestra dispersión.

## Conclusión

**K-means** es más eficaz para segmentar clientes de forma homogénea y visualmente interpretable.  
**DBSCAN** es útil cuando se busca detectar comportamientos atípicos o zonas densas sin forzar agrupamiento.

Este proyecto permite comprender cómo elegir entre técnicas de clustering según el tipo de datos y los objetivos del análisis.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.




