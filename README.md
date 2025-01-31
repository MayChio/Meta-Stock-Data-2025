Meta Stock Data 2025: Predicción del Precio de Cierre de Meta
Este proyecto tiene como objetivo predecir el precio de cierre de las acciones de Meta (anteriormente Facebook) utilizando datos históricos de stock (2025). Usamos el algoritmo Random Forest Regressor y GridSearchCV para encontrar los mejores hiperparámetros del modelo y lograr una predicción precisa.

Descripción del Proyecto
Este proyecto analiza datos históricos de precios de acciones de Meta para predecir el precio de cierre en fechas futuras. Se implementó un modelo de aprendizaje automático utilizando Random Forest Regressor para predecir los precios futuros basados en varias características como:

Precio de apertura
Precio más alto
Precio más bajo
Volumen de transacciones
Fecha
Se realizó una optimización de los hiperparámetros utilizando GridSearchCV para mejorar el rendimiento del modelo.

Características del Proyecto
Análisis y limpieza de datos
Visualización de los precios históricos y su distribución
Creación y entrenamiento del modelo Random Forest
Evaluación del modelo utilizando Métricas de Error (MAE, MSE, RMSE)
Predicción de precios futuros para el período de febrero de 2025
Tecnologías Utilizadas
Python
Pandas (para la manipulación de datos)
Matplotlib y Seaborn (para la visualización de datos)
Scikit-learn (para la creación y evaluación del modelo de predicción)
NumPy (para operaciones numéricas)
Cómo Usar el Proyecto
Clonar el Repositorio:

bash
Copiar
Editar
git clone https://github.com/MayChio/Meta-Stock-Data-2025.git
Instalar Dependencias: Asegúrate de tener instaladas las librerías necesarias:

bash
Copiar
Editar
pip install -r requirements.txt
Ejecutar el Notebook: Abre el archivo Meta_Stock_Prediction.ipynb con Jupyter Notebook o VS Code y sigue los pasos en el cuaderno para cargar, procesar los datos y entrenar el modelo.

Explorar los Resultados: Los resultados estarán disponibles en las gráficas generadas y en las métricas del modelo, incluyendo el MAE, MSE y RMSE.

Resultados del Modelo
Mean Absolute Error (MAE): 1.26 USD
Mean Squared Error (MSE): 3.82
Root Mean Squared Error (RMSE): 1.95
Estos resultados indican que el modelo tiene una precisión razonable para predecir el precio de cierre de Meta.

Próximos Pasos y Mejoras
Incorporar más variables: Añadir indicadores técnicos como el RSI, MACD, y el sentimiento del mercado.
Explorar otros modelos: Probar con modelos como XGBoost o LSTM para mejorar las predicciones.
Automatizar el proceso: Crear un sistema que ajuste el modelo con datos en tiempo real.
