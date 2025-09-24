# Machine Learning para Predecir Precios de Coches

## Tabla de Contenidos
- [Descripción](#Descripción)
- [Datos](#Datos)
- [Análisis](#Análisis)
- [Tecnologías y herramientas](#Tecnologías-y-herramientas)
- [Resultados](#Resultados)
- [Contribuciones](#Contribuciones)
- [Licencia](#Licencia)
- [Contacto](#Contacto)

## Descripción
Este proyecto desarrolla un modelo de machine learning para predecir el valor de mercado de autos usados, basándose en especificaciones técnicas, versiones de equipamiento y precios históricos. El objetivo es optimizar calidad, velocidad y tiempo de entrenamiento para apoyar la aplicación comercial Rusty Bargain.

## Datos
Se utilizaron XXX conjuntos de datos principales:  
- **car_data.csv**: DataFrame con 354,369 registros y 16 columnas, que incluye datos técnicos, categóricos y temporales sobre autos usados y sus valores de mercado.

## Análisis
El enfoque incluyó:  
- Importación y preparación de datos, con limpieza y selección de 10 columnas relevantes sobre 354,369 registros.
- Manejo de valores ausentes, duplicados y unificación de categorías para mejorar la calidad del dataset.
- Visualización para detectar distribución de variables clave como tipo de vehículo, transmisión y marca.
- Comparación de modelos de machine learning evaluando precisión y rapidez mediante un índice compuesto.
- Ajuste de hiperparámetros en modelos de gradiente potenciado para optimización.

## Tecnologías y herramientas
- Python 3.9 para desarrollo general y análisis de datos
- Pandas y NumPy para manipulación y procesamiento de datos
- Matplotlib y Seaborn para visualización gráfica
- Scikit-learn para preprocesamiento, partición de datos, modelado y evaluación
- XGBoost, LightGBM y CatBoost para modelos avanzados de boosting
- Jupyter Notebook para desarrollo interactivo y documentación

## Resultados
- Identificada alta variabilidad y valores atípicos en los precios, ajustados para evitar sesgos.
- Los modelos XGBoost y LightGBM mostraron el mejor balance entre precisión y eficiencia.
- XGBoost seleccionado como el modelo definitivo con un índice compuesto de 0.0992 para la predicción.
- El modelo cumple con los requisitos de calidad, tiempo de predicción y entrenamiento establecidos.

## Contribuciones
Bienvenidas sugerencias, correcciones y nuevas visualizaciones. Por favor, abre un issue o pull request para colaborar.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
Nombre: Alejandro M. García  
Email: [alexkhype@gmail.com](mailto:alexkhype@gmail.com)  
LinkedIn: [linkedin.com/in/amggl](https://linkedin.com/in/amggl)
