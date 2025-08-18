# Challenge-ONE-Data-Science-Telecom-X-parte-2

Este proyecto analiza la cancelación de clientes (Churn) en una empresa de telecomunicaciones utilizando técnicas de aprendizaje automático. El objetivo principal es identificar los factores que influyen en la evasión de clientes y proponer estrategias de retención basadas en datos.

## Archivos del Proyecto

- **Challenge_Telecom_X_parte_2.ipynb**: Notebook principal que contiene la limpieza de datos, análisis exploratorio, creación y evaluación de modelos de Machine Learning (KNN y Árbol de Decisión/Random Forest), así como visualizaciones y conclusiones.  
- **datos_tratados.csv**: Dataset utilizado para el análisis, ya preprocesado y listo para modelado.  
- **README.md**: Documento descriptivo del proyecto.

## Descripción del Proyecto

El análisis se desarrolló en varias etapas:

1. **Preparación de los Datos**  
   - Limpieza y tratamiento de valores faltantes.
   - Codificación de variables categóricas.
   - Normalización de variables numéricas para modelos sensibles a escala (como KNN).

2. **Análisis Exploratorio de Datos (EDA)**  
   - Visualización de distribuciones y boxplots.
   - Identificación de correlaciones entre variables.

3. **Modelado de Machine Learning**  
   - **K-Nearest Neighbors (KNN)**: análisis basado en la similitud de clientes.  
   - **Árbol de Decisión / Random Forest**: identificación de la importancia relativa de cada variable y predicción de cancelación.

4. **Evaluación de Modelos**  
   - Métricas de desempeño: exactitud (accuracy), precisión, recall y F1-score.  
   - Validación mediante StratifiedKFold y técnicas de oversampling (SMOTE) para balancear las clases.

5. **Insights y Recomendaciones**  
   - Variables más influyentes: tipo de contrato, antigüedad del cliente (tenure), tipo de servicio de internet, cargo mensual y método de pago.  
   - Estrategias de retención basadas en la segmentación y personalización de servicios.

## Resultados Clave

- El modelo con mejor desempeño fue el **Árbol de Decisión** con validación cruzada y oversampling, logrando un recall significativamente mejor para detectar clientes propensos a cancelar.  
- Clientes con contratos mensuales, baja antigüedad y cargos mensuales elevados presentan mayor riesgo de cancelación.  

## Requisitos

- Python >= 3.8  
- Bibliotecas necesarias:
  - pandas
  - numpy
  - scikit-learn
  - imbalanced-learn
  - matplotlib
  - seaborn
  - plotly

**Realizado por:** Ronald J. Varela M.
**Correo**: ronaldvarela852@gmail.com


1. Clonar el repositorio:

```bash
git clone <URL_DEL_REPOSITORIO>
