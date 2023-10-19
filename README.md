# Red Neuronal Convolucional para Procesamiento de Imágenes

## Descripción
Este proyecto implementa una red neuronal convolucional (CNN) para procesar imágenes. La CNN está diseñada para ser invariante a la rotación, lo que significa que puede reconocer patrones en imágenes independientemente de su orientación.

## Preprocesamiento de Datos con [Data.ipynb](https://github.com/milanPCJ/The_big_proyect/blob/main/Data.ipynb)
1. Se utilizan las bibliotecas `pickle`, `matplotlib` y `numpy` para cargar y visualizar los datos.
2. Se carga el archivo `td_ztf_stamp_17_06_20.pkl` que contiene los datos originales.
3. Se exploran las claves y estructuras de los datos.
4. Se separan las imágenes en sus tres componentes: science, reference y difference.
5. Se verifica que todas las imágenes tengan las dimensiones correctas y no contengan valores NaN.
6. Se recortan las imágenes a una dimensión de 21x21.
7. Se verifica que las imágenes estén normalizadas en el rango [0, 1].
8. Se lleva a cabo una serie de verificaciones para asegurar la integridad de los datos.
9. Finalmente, se guardan los datos procesados en un archivo `processed_data.pkl`.


## Modelo Convolucional
- El modelo consta de varios bloques de convolución seguidos de capas completamente conectadas (MLP).
- Se implementa la invariancia rotacional mediante la rotación de las entradas y el pooling cíclico.
- Se proporciona una función `predict` que permite realizar predicciones con el modelo en un conjunto de datos.
- Se utiliza un dataloader para cargar los datos en lotes y alimentarlos al modelo.
- Se evalúa el rendimiento del modelo utilizando una matriz de confusión, que visualiza las predicciones del modelo en comparación con las etiquetas verdaderas.


## Entrenamiento y Evaluación
- Se define una función de entrenamiento que actualiza los pesos del modelo usando el optimizador Adam.
- Se utiliza la función de pérdida de entropía cruzada para la clasificación.
- Se implementa una lógica de "early stopping" para detener el entrenamiento si no se observan mejoras después de un cierto número de épocas.
- Se visualizan las curvas de pérdida y precisión durante el entrenamiento.

## Instrucciones de Uso
1. Asegúrate de tener todas las dependencias necesarias instaladas (PyTorch, numpy, matplotlib, etc.).
2. Carga tu archivo .pkl con los datos preprocesados.
3. Ejecuta el código para entrenar el modelo con tus datos.
4. Prepara las imágenes para el modelo utilizando la función `preparar_imagenes_para_modelo`.
5. Extrae las etiquetas utilizando la función `extraer_etiquetas`.
6. Define un dataloader para cargar los datos en lotes.
7. Utiliza la función `predict` para obtener las etiquetas verdaderas y predichas.
8. Evalúa el rendimiento del modelo visualizando la matriz de confusión.
9. Ajusta y repite según sea necesario para mejorar el rendimiento del modelo.
