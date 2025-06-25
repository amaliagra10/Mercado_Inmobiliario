🏘️ Análisis del Mercado Inmobiliario con Python.
Este proyecto fue realizado en un Jupyter Notebook, utilizando el dataset Datos_Properati.xlsx, que contiene 459.182 registros y 20 columnas sobre propiedades en venta y alquiler en diferentes localidades de América Latina.

📦 Contenido del dataset
El dataset incluye variables como:

- Superficie total y cubierta
- Precio
- Ciudad y localidad
- Habitaciones, baños y ambientes
- Tipo de propiedad
- Tipo y moneda de la operación, entre otros

🔍 Análisis realizado
Se llevó a cabo un análisis exploratorio profundo que incluyó:

1. Revisión de la estructura y contenido del dataset
2. Detección y tratamiento de valores faltantes
3. Análisis de la distribución de las variables numéricas
4. Identificación y eliminación de outliers usando el método de rango intercuartílico (IQR)
5. Estudio de la correlación entre variables

⚙️ Técnicas aplicadas
Para preparar el dataset para futuros modelos de predicción, aplicamos:
a. One-hot encoding para transformar variables categóricas
b. Reducción de dimensionalidad, con el fin de obtener un dataset más compacto y eficiente
c. Clusterización para segmentar mejor el mercado inmobiliario y filtrar datos de forma más inteligente

El objetivo final es contar con una base de datos limpia y estructurada que permita aplicar modelos de aprendizaje automático (machine learning) para predecir el precio de una propiedad según sus características.

❓ Preguntas exploratorias
Durante el análisis también se respondieron preguntas clave para comprender mejor el mercado:

🤔 Pregunta 1: ¿Cuáles son las localidades en las que hay más propiedades disponibles?

🤔 Pregunta 2: ¿Cuáles son las 10 localidades más caras y cuáles son las 10 más baratas?

🤔 Pregunta 3: ¿En qué barrios puedo encontrar propiedades con las siguientes características: precio entre 180.000 y 240.000, 3 baños, 3 habitaciones y 6 ambientes?

🤔 Pregunta 4: ¿Cuáles son las características del registro con índice 53?

📁 Archivos incluidos
Analisis_Mercado_Inmobiliario.ipynb: notebook principal con todo el análisis realizado.

Datos_Properati.xlsx: dataset original utilizado para el estudio.

🚀 Próximos pasos
Se espera continuar el proyecto con:
- Desarrollo de modelos de regresión y clasificación
- Optimización de predicciones con validación cruzada
- Visualización interactiva de los resultados

💡 Requisitos
Para correr el proyecto necesitás tener instalado:

Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
