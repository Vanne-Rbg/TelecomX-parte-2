# README: Proyecto de Análisis de Cancelación - TelecomX

## Objetivo
Identificar los factores que influyen en la cancelación de clientes y construir modelos de predicción utilizando técnicas de ciencia de datos.

## Flujo de Trabajo
1. **Limpieza y preprocesamiento:**
   - Eliminación de columnas irrelevantes
   - Codificación de variables categóricas (One-Hot Encoding)

2. **Análisis exploratorio:**
   - Visualización de correlaciones
   - Boxplots y scatterplots para detectar patrones con la variable de cancelación

3. **Balanceo y normalización:**
   - SMOTE para clases desbalanceadas
   - Normalización para modelos sensibles a escala

4. **Modelado predictivo:**
   - Entrenamiento de modelos: Logistic Regression, KNN, Random Forest, SVM
   - División entrenamiento/prueba (70/30)
   - Evaluación con métricas: exactitud, precisión, recall, F1-score

5. **Interpretación:**
   - Importancia de variables por modelo
   - Análisis crítico (overfitting/underfitting)

6. **Entrega de resultados:**
   - Informes en .ipynb y visualizaciones
   - Recomendaciones de retención

## Requisitos
- Python 3.x
- Pandas, Scikit-learn, Matplotlib, Seaborn
- imbalanced-learn (SMOTE)

## Autores
Proyecto realizado como parte del análisis de cancelación de clientes para TelecomX.
