# REDES NEURONALES V – Verificación Facial

## Descripción
Proyecto académico sobre la implementación de una **Red Neuronal Siamesa (Siamese Neural Network)** para la verificación facial, utilizando Deep Learning con TensorFlow y Keras en Google Colab.

## Objetivo
Implementar un modelo capaz de comparar imágenes faciales mediante embeddings y determinar si pertenecen a una misma persona.

## Tecnologías utilizadas
- Python
- Google Colab
- TensorFlow y Keras
- NumPy
- Matplotlib

## Metodología
- Carga y preprocesamiento de imágenes faciales.
- Construcción de una red neuronal convolucional (CNN).
- Generación de embeddings de 64 dimensiones.
- Entrenamiento mediante Triplet Loss.
- Comparación de rostros utilizando distancia euclidiana.

## Dataset
Se utilizaron 9 fotografías organizadas en tres identidades, con 3 imágenes por persona.

## Resultados
El modelo permitió realizar comparaciones entre fotografías y diferenciar imágenes de una misma identidad y de identidades diferentes en las pruebas realizadas.

## Ejecución
El proyecto fue desarrollado en Google Colab. Para ejecutarlo, se debe abrir el notebook, cargar el archivo `dataset_faces.zip` y ejecutar las celdas en orden.
