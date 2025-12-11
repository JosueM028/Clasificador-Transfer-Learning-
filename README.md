#  Clasificación de Razas de Perros con Transfer Learning

Este proyecto implementa un modelo de Inteligencia Artificial para clasificar imágenes de diferentes razas de perros utilizando la técnica de **Transfer Learning**.

El modelo se basa en la arquitectura **MobileNetV2** pre-entrenada con ImageNet, adaptada para reconocer patrones específicos de razas caninas con alta precisión y eficiencia.

##  Descripción del Proyecto 

El objetivo de este notebook es aplicar los conceptos de Transfer Learning en un problema de clasificación multiclase. A diferencia de un clasificador binario (Gato vs. Perro), este modelo distingue entre múltiples razas específicas.

### Características Técnicas
* **Modelo Base:** `MobileNetV2` (pesos congelados de ImageNet).
* **Técnica:** Transfer Learning (Feature Extraction).
* **Dataset:** [Dog Breeds - Kaggle](https://www.kaggle.com/datasets/mohamedchahed/dog-breeds).
* **Framework:** TensorFlow / Keras.
* **Entorno:** Google Colab.

##  Resultados

El modelo alcanzó resultados sobresalientes con un entrenamiento reducido (10 épocas):

* **Precisión de Validación (Validation Accuracy):** ~99%
* **Pérdida (Loss):** Convergencia rápida cercana a 0.
* **Rendimiento:** Identificación correcta de razas como Beagle, Bulldog, Pastor Alemán, entre otras, con una confianza superior al 95%.

##  Cómo Ejecutar

1.  Abre el archivo `.ipynb` en **Google Colab**.
2.  Asegúrate de tener tu archivo `kaggle.json` configurado (o usa las credenciales incluidas en el código para la descarga automática).
3.  Ejecuta las celdas en orden. El notebook se encargará de descargar el dataset, procesarlo y entrenar el modelo automáticamente.
