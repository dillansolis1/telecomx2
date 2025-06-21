# Challenge Telecom X - Parte 2

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir la evasión de clientes en una empresa de telecomunicaciones llamada Telecom X. A partir de un conjunto de datos simulados, se realiza un análisis completo que incluye exploración, limpieza, modelado predictivo y evaluación, con el fin de entregar conclusiones estratégicas útiles para la empresa.

---

## Metodología y Pasos Realizados

### 1. Generación y Preparación de Datos  
Se simulan datos de clientes con características como género, uso de datos, satisfacción, número de llamadas al servicio al cliente, duración del contrato, historial de pagos y si el cliente evadió o no.

### 2. Análisis Exploratorio de Datos (EDA)  
Se examinan las características generales del conjunto de datos, incluyendo distribuciones de variables, posibles valores faltantes y detección de valores atípicos mediante gráficos como histogramas y boxplots.

### 3. Preprocesamiento  
Se codifican variables categóricas en formato numérico y se escalan las variables numéricas para facilitar el entrenamiento de modelos.

### 4. División de Datos  
Se separa el conjunto en entrenamiento y prueba para evaluar el desempeño real de los modelos.

### 5. Validación Cruzada  
Se aplica validación cruzada para obtener una evaluación más robusta y evitar el sobreajuste del modelo.

### 6. Modelado y Comparación  
Se entrenan y comparan varios modelos de Machine Learning, incluyendo Regresión Logística, Random Forest, Support Vector Machine (SVM) y Árbol de Decisión. Se evalúan usando métricas como precisión, recall, F1-score y ROC AUC.

### 7. Ajuste de Hiperparámetros  
Se optimizan los parámetros del modelo de Random Forest mediante búsqueda con Grid Search para mejorar su desempeño.

### 8. Evaluación Final y Visualización  
Se presentan reportes detallados, matrices de confusión, curvas ROC e importancia de las variables para interpretar los resultados.

---

## Conclusiones y Recomendaciones

- La satisfacción del cliente y la duración del contrato son factores clave para predecir la evasión.  
- Clientes con muchas llamadas al servicio de atención y con historial de pagos atrasados tienen mayor riesgo de abandonar.  
- Se recomienda a Telecom X implementar seguimientos a clientes insatisfechos, incentivar contratos más largos y mejorar la atención al cliente para reducir la evasión.

---

## Archivos Incluidos

- Notebook con todo el análisis, modelado y conclusiones detalladas.

---

Gracias por revisar este proyecto.
