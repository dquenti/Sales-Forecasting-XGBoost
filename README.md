# Sales-Forecasting-XGBoost

 🫸🏼⚠️ Working on this project . . . . ⌛️  There is no final version yet... 👩🏻‍💻

Este proyecto utiliza el algoritmo XGBoost para la previsión de ventas utilizando series temporales. Se centra en la creación de un modelo de predicción para estimar las ventas totales de un mes determinado basándose en datos históricos.

## Descripción del Proyecto

El objetivo de este proyecto es predecir las ventas totales del mes de octubre de 2015 para varios artículos en diferentes tiendas y ciudades. El dataset abarca el periodo de enero de 2013 a septiembre de 2015 e incluye un total de 426 series temporales multivariantes, cada una representando las ventas mensuales de un artículo específico en una tienda y ciudad específica.

### Algoritmo Utilizado

El algoritmo principal utilizado en este proyecto es **XGBoost** (Extreme Gradient Boosting). XGBoost es una implementación eficiente y flexible del algoritmo de boosting de gradiente, que ha demostrado ser muy efectivo en diversas competiciones de ciencia de datos.

### Estructura del Proyecto

El proyecto está dividido en varios notebooks para facilitar su seguimiento y comprensión:

1. **Exploratory Data Analysis (EDA)**: Análisis exploratorio de datos para entender mejor el dataset y preparar los datos para el modelado.
2. **Time Series XGBoost**: Implementación del modelo XGBoost para series temporales, incluyendo el preprocesamiento de datos, la creación del modelo, la evaluación y la predicción.

### Análisis Exploratorio de Datos (EDA)

En el notebook de EDA se realizan las siguientes tareas:

- Visualización de las series temporales de ventas.
- Análisis de tendencias y estacionalidades.
- Identificación y tratamiento de valores atípicos y datos faltantes.

### Modelado con XGBoost

En el notebook de modelado se abordan los siguientes pasos:

- **Preprocesamiento de Datos**: Transformación de las series temporales en una estructura adecuada para el modelo XGBoost, creación de características (features) adicionales, y división de los datos en conjuntos de entrenamiento y prueba.
- **Entrenamiento del Modelo**: Configuración y entrenamiento del modelo XGBoost utilizando los datos preprocesados.
- **Evaluación del Modelo**: Evaluación del rendimiento del modelo utilizando métricas como RMSE (Root Mean Squared Error) y MAPE (Mean Absolute Percentage Error).
- **Predicción**: Uso del modelo entrenado para predecir las ventas del mes de octubre de 2015.

## Resultados y Conclusiones

Los resultados obtenidos muestran la eficacia de XGBoost para la previsión de ventas a partir de series temporales. Sin embargo, es importante destacar las limitaciones del modelo, como su incapacidad para extrapolar tendencias a largo plazo sin datos adicionales.

## Recursos

- [XGBoost Documentation](https://xgboost.readthedocs.io)
- [Gradient Boosting](https://interactivechaos.com/en/manual)

## Contacto

Para más información, puedes contactarme a través de [GitHub](https://github.com/dquenti/Sales-Forecasting-XGBoost).
