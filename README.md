# Clasificador de Canciones de Spotify

## Introducción

Este proyecto se centra en la creación de un clasificador de canciones de Spotify. El objetivo principal es predecir si a un usuario le gustará o no una canción en función de sus atributos musicales. Utilizaremos técnicas de aprendizaje automático y herramientas de inteligencia artificial para lograr este objetivo.

## Pasos del Proyecto

### 1. Importación de Bibliotecas y Carga y Preprocesamiento de Datos

- Se importarán las bibliotecas necesarias para el análisis y la creación de modelos.
- Los datos se cargarán desde un archivo CSV que contiene información sobre las canciones.
- Realizaremos un proceso de preprocesamiento que puede incluir la limpieza de datos, la codificación de variables categóricas y la normalización de datos.
- Dividiremos los datos en conjuntos de entrenamiento y prueba para su posterior modelado.

### 2. Visualización de Datos

- Utilizaremos herramientas como Seaborn y Matplotlib para visualizar los datos y comprender mejor las características de las canciones.

### 3. Función para obtener las métricas de medición y evaluar los modelos.

- Hemos definido una función llamada `evaluar_modelo` que evalúa el rendimiento de los modelos. Calcula métricas clave, como la precisión, la recuperación y el puntaje F1, y rea una matriz de confusión para visualizar las predicciones

- Además de la evaluación simple del modelo, implementamos una función `validacion_cruzada` la cual realiza un cross validation, que nos permite evaluar el rendimiento del modelo en múltiples particiones del conjunto de datos de entrenamiento.

### 4. Creación de Modelos con Scikit-Learn

- Implementaremos varios modelos de aprendizaje automático utilizando la biblioteca Scikit-Learn.
- Evaluaremos el rendimiento de los modelos y seleccionaremos los mejores.

### 5. Creación de Modelos con TensorFlow y Keras

- Implementaremos modelos de redes neuronales utilizando TensorFlow y Keras.
- Ajustaremos y entrenaremos estos modelos para la clasificación de canciones.

### 6. Ajuste de Hiperparámetros

- Utilizaremos técnicas de búsqueda de hiperparámetros para optimizar el rendimiento de nuestros mejores modelos.

### 7. Ensamble y Métricas

- Ensamblaremos los modelos seleccionados para mejorar la precisión de nuestras predicciones.
- Calcularemos métricas de evaluación como precisión, recall, F1-score y matriz de confusión.

### 8. Probando modelos de otras librerías

- En esta etapa se exploraron modelos de clasificación de tres bibliotecas populares de aprendizaje automático: `XGBoost, LightGBM y CatBoost.`

## Conjunto de Datos

Los datos utilizados en este proyecto contienen atributos de canciones de Spotify, como su bailabilidad, energía, volumen, etc. Estos atributos se utilizan para predecir si a un usuario le gustará la canción o no (etiqueta "1" para "gustar" y "0" para "no gustar").

## Librerías y Recursos Utilizados

- Se utilizarán bibliotecas como pandas, numpy, scikit-learn, TensorFlow y Keras.
- Se hará uso de herramientas de visualización como Seaborn y Matplotlib.

## Estructura de Archivos

El proyecto contendrá archivos de código fuente, como archivos Python, y archivos de datos, como el archivo CSV que alberga el conjunto de datos de canciones.

¡Gracias por revisar el proyecto!
