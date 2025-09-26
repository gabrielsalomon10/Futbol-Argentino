# Futbol-Argentino
Base de datos del fútbol argentino 2008 - 2022

### 💡 ¿Cómo Obtuve un Accuracy del 100% Utilizando Machine Learning?
En mi proyecto de análisis de datos de fútbol, enfrenté un dataset con valores faltantes y columnas sucias. 

📊 Mediante scikit-learn, implementé Random Forest como técnica principal de machine learning, utilizando su variante Classifier para la imputación categórica y opcionalmente exploré el Regressor para estimaciones numéricas, demostrando la versatilidad de este ensemble de árboles de decisión.

🐍 Un paso clave en el ETL fue la limpieza personalizada con pandas, donde desarrollé una función vectorizada (limpiarColumnaNumerica) que removió símbolos y convirtió strings a numéricos, elevando la precisión de un baseline de 66% a 100%. 

Complementé con LabelEncoder de sklearn para codificar categorías de alta cardinalidad , preparando el dataset para el modelo.

Por último, para validar, usé cross-validation de sklearn.model_selection, obteniendo accuracy de 1.00.
Próximamente voy a realizar el dashboard en Power BI.

![Image](https://github.com/user-attachments/assets/ab8fec12-cf71-4959-acc5-65cd1d2ce3bb)

![Image](https://github.com/user-attachments/assets/98b52377-eee6-4fac-8458-d5afe86b9ae0)

![Image](https://github.com/user-attachments/assets/5cbcc663-e727-4fe7-862e-1d52eb1fde75)

![Image](https://github.com/user-attachments/assets/5d922b67-6b25-4f6b-b15d-bb94f74309aa)

![Image](https://github.com/user-attachments/assets/db07c38b-c360-4928-8456-b2c70143259d)

![Image](https://github.com/user-attachments/assets/0032f07c-8b6d-48d9-ba44-ad826a0cb4f9)
