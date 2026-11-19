# Clasificación de señales de tránsito con Deep Learning

Proyecto de Visión Computacional basado en el dataset **German Traffic Sign Recognition Benchmark (GTSRB)**.

## Objetivo
Comparar tres arquitecturas de redes neuronales convolucionales para clasificar 43 categorías de señales de tránsito.

## Modelos implementados
- CNN personalizada.
- ResNet18.
- MobileNetV2.

## Metodología
- Preprocesamiento de imágenes RGB de 48 × 48 píxeles.
- Data Augmentation.
- Entrenamiento y validación con PyTorch.
- Evaluación independiente sobre 12 630 imágenes de prueba.
- Comparación mediante Accuracy, Precision, Recall y F1-macro.

## Resultados

| Modelo | Accuracy | F1-macro |
|---|---:|---:|
| CNN personalizada | 95.68 % | 93.98 % |
| ResNet18 | 98.12 % | 97.53 % |
| MobileNetV2 | 95.59 % | 93.10 % |

**Mejor arquitectura:** ResNet18.

## Tecnologías
Python, PyTorch, OpenCV, Scikit-learn y Google Colab.

## Autores
- Timoteo Quispe Merma.
- Aracely Fiorela Corampa Palacios.

Proyecto académico de Visión Computacional, UNSAAC.
