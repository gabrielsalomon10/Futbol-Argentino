# Futbol-Argentino
Base de datos del fútbol argentino 2008 - 2022

### 💡 ¿Cómo Obtuve un Accuracy del 100% Utilizando Machine Learning?
En mi proyecto de análisis de datos de fútbol, enfrenté un dataset con valores faltantes y columnas sucias. 

📊 Mediante scikit-learn, implementé Random Forest como técnica principal de machine learning, utilizando su variante Classifier para la imputación categórica y opcionalmente exploré el Regressor para estimaciones numéricas, demostrando la versatilidad de este ensemble de árboles de decisión.

🐍 Un paso clave en el ETL fue la limpieza personalizada con pandas, donde desarrollé una función vectorizada (limpiarColumnaNumerica) que removió símbolos y convirtió strings a numéricos, elevando la precisión de un baseline de 66% a 100%. 

Complementé con LabelEncoder de sklearn para codificar categorías de alta cardinalidad , preparando el dataset para el modelo.

Por último, para validar, usé cross-validation de sklearn.model_selection, obteniendo accuracy de 1.00.
Próximamente voy a realizar el dashboard en Power BI.
