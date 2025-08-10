Análisis de Cancelación de Clientes (Churn) - Proyecto TelecomX
Descripción
Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes (churn) para la empresa TelecomX. Utilizando técnicas de machine learning, se desarrollaron modelos para identificar los factores que más influyen en la decisión de cancelar el servicio y ayudar a diseñar estrategias de retención.

Modelos implementados
Regresión Logística: Modelo lineal que permite interpretar la influencia de cada variable en la cancelación.

Random Forest: Modelo basado en árboles de decisión que captura relaciones no lineales y combina variables para mejorar la predicción.

Proceso
Carga y limpieza de datos: Se importaron datos desde una fuente JSON, se limpiaron y codificaron las variables categóricas.

Análisis exploratorio: Se analizaron las variables más relevantes y su relación con la cancelación.

Preparación de datos: División en conjunto de entrenamiento y prueba, imputación de valores faltantes y normalización para los modelos que lo requieren.

Entrenamiento y evaluación: Se entrenaron los modelos y se evaluaron con métricas como exactitud, precisión, recall, F1-score y matriz de confusión.

Análisis de importancia: Se identificaron las variables con mayor impacto en la predicción para cada modelo.

Resultados
Ambos modelos lograron un desempeño adecuado, con Random Forest mostrando mejores resultados en general.

Variables como tiempo de contrato, gasto total y uso de facturación electrónica resultaron clave en la cancelación.

Se proponen estrategias de retención basadas en estos hallazgos.


